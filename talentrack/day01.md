# Python 
- Created a microservice talentrack-business in python.
- Created an API endpoint /job_posts using FastAPI(), which saves the details of a job post in a ElasticSearch index.

# Elasticsearch
- Downloaded the elastic search code on local to know about the local configurations present.
- Downloaded docker and integrated the image with the python endpoint.

# React
- Created a Form to submit a new job post.
- Defined onSubmit event to call the /job_posts endpoint.

## Things to remember 
1) While working in python we must create a virtual environemnt, and have a requitements.txt file where we can list down all the dependencies used in the project.
    ```
    pip install -r requirements.txt
    ```
2) When working in a python microservice we can create a directory structure similar to the one we create in java with {app/src, -> (api,services,repository,config,domain),tests}
3) We can also place __init__.py file in the directories this makes sure the folders are considered as source folders for python files, this can also be used to define import statements.
4) We can run the elasticsearch image using the docker command below :
  ```
  docker run --rm -p 9200:9200 -p 9300:9300 -e "xpack.security.enabled=false" -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:8.7.0
  ```
5) Once the image is up and running we need to create an index for the elasticsearch, where we can explicitily define all the parameters and their type or keep it dynamic and let elastic search define the type of the parameters.
6) To connect the elasticsearch to python we need to use **http**://localhost:9200, If we use https instead of http we will get error related to SSL certificates.
7) If we do a POST call from browser to python backend API, we might end up getting OPTIONS call instead of POST call, this happens because of the browser's preflight request mechanism where a browser sends a OPTIONS call first to validate the request can only be served if it comes with a origin mentioned in the CORS policy.
8) When you make a request from your web application to a server that is not part of the same origin (domain, scheme, or port), the browser automatically performs a CORS preflight check if the request does not satisfy the "simple requests" criteria. This is to ensure that the server accepts the request from the origin based on its CORS policy.
   A preflight request is sent using the OPTIONS method, and it asks the server for permission to send the actual request. The preflight checks the following:
   The HTTP method (POST, PUT, DELETE, etc.)
   Headers that will be used in the actual request
   The origin of the request
9) 

