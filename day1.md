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
  - When there is a class there is an abstraction, hence abstraction comes into the picture when there is encapsulation

### 3) Inheritance
  - When a class A wants to use the functions of class B, it can do that using inheritance
  - This is a parent-child relation
  - Single, Multi-level and hierarchical inheritance is allowed in Java
  - No Multiple Inheritance and no Hybrid Inheritance are required.
   
### 4) Polymorphism 
  - Having the same name but many forms
  - In OOP language there are 2 types of polymorphism :
      -  Object level polymorphism
      -  Function level polymorphism
   
  - Further, we have compile time polymorphism and runtime polymorphism.

# Questions

### Q1) Java Reflection APIs are provided by Java themselves, which breaks abstraction, and other OOP Concepts in Java, why do we have them that?
  - Java is used not just by the application developer but by the people who are developing independent libraries, IDE, servers, etc, which will be used by external users and they will place n class files in the IDE, or library, to introspect the .class file for all members and functions, java provided the java reflection API.

### Q2) How does IDE work?
- IDEs are also runtime environments that use special API to read .class files.
- IDE runs introspections on each class within the loaded .class files which are there in the IDE classpath, so while coding it shows help with all kinds of methods, their arguments, return types, etc.
- This is the feature of Reflection API which is being used in IDEs and libraries. It's there one can use it or misuse it, that depends on us.

