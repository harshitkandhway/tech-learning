# Questions

### Q1) Java Reflection APIs are provided by Java themselves, which breaks abstraction, and other OOP Concepts in Java, why do we have them that?
  - Java is used not just by the application developer but by the people who are developing independent libraries, IDE, servers, etc, which will be used by external users and they will place n class files in the IDE, or library, to introspect the .class file for all members and functions, java provided the java reflection API.

### Q2) How does IDE work?
- IDEs are also runtime environments that use special API to read .class files.
- IDE runs introspections on each class within the loaded .class files which are there in the IDE classpath, so while coding it shows help with all kinds of methods, their arguments, return types, etc.
- This is the feature of Reflection API which is being used in IDEs and libraries. It's there one can use it or misuse it, that depends on us.
