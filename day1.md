# OOPS Concepts
### 1) Encapsulation
  - keeping data and functionality together is called encapsulation 
    - data -> member variables
    - functionality -> method
  - Class is an implementation of the encapsulation concept of OOPS
  - This term comes from medicine capsule -> capsule needs a runtime env(human body) where it can show its behavior(to take away some issues), it will not work if you keep a capsule in an almirah, as it has small particles which can be treated as data.
  - When data changes the behaviour also changes

### 2) Abstraction
  - Hiding the data(data members not functions) from the external world is abstraction.(making data variable as private)
  - Hiding methods is not abstraction.(creating a private method is never a part of abstraction)
  - When there is a class there is abstraction, hence abstraction comes into the picture when there is encapsulation
### 3) Inheritance
### 4) Polymorphism 

# Questions

### Q1) Java Reflection APIs are provided by Java themselves, which breaks abstraction, and other OOP Concepts in java, why do we have them that?
  - Java is used not just by the application developer but by the people who are developing independent libraries, IDE, servers etc, which will be used by external users and they will place n class files in the IDE, or library, to introspect the .class file for all members and functions ,java provided the java reflection API.

