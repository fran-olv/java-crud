# Management People Project ☕
Project of Java Foundations using Lists manipulation using CRUD actions (Creat, Read, Update and Delete), user interaction with input/output APIs, string manipulation, differences between list types in Java. 

### ✔️ What this application do: 
-  This Java app enables a user to input an infinit number of names and retrieves a list that matches the inputed search string. 


## 🖥️ Stack utilizada

**Back-end:** Java, Maven


## ⚙️ Features

- Operations can be executed before receive at least 3 names;
- The data was saved in-memory data storage.
- The data structure used was Java Collection type: Set - because it doesnt allow Duplicates 
- The manipulation permited in this list is save, delete and update; 
- Delete operations swill ask for user confirmation before execution a delete operation. 
- It was built with Java & Maven. 


## ▶️ Usage/Example

1. User: executes in terminal `java -jar management-people-project.jar` 

2. Application: asks, on the CLI (terminal), for name inputs. 

3. User: Inputs the required number of names, three names.

4. Application: asks what the user wants to do next: 
- add new name
- search
- update
- delete
- list all

## How it works: 

The application main option is to allow searching the stored names based on a string. 
The search is case insensitive, therefore, a search for “kar” should return, for example, “Karina” and “KARen”. 
The user can also access the maintenance mode, where names can be added and updated. 
The delete function allows deleting a single name, or deleting a set of names that matches the inputed search string.

Important: The description for the behaviors below are for guidance only. You can decide how your application will behave and interact with the user. Just make sure you have in mind the core goals: adding/updating/searching/deleting one/deleting many. 




## 🔛 Run Locally

Clone the project's repository 

```bash
  git clone git@github.com:fran-olv/management-people-project

```

Use the terminal to go file repository 

```bash
  cd management-people-project

```

Install the dependencies

```bash
  mvn install
  mvn clean package
```

Run the application 
```bash
java -jar management-people-project.jar
```


##  🔛 🤖 Run tests

Using Junit to run tests with the command: 

```bash
????
```


## 📖 License: 

The open-source license add in my application was: 
because of

> explore different open source licenses what the differences between them. E.g. Will you use Apache License or LGPL? Why?


## 📚 Passed Projects

That's some of my projects that are related and helps me do this one:

- [Java Basics](https://github.com/fran-olv/dio-java-basico)
- [Java Collection](https://github.com/fran-olv/dio-java-collections)
- [Java Challenges](https://github.com/fran-olv/DesafiosOnline/tree/main/Prepare%20Java)


## 📚 What did I learned?

1. Java Foundations: 
Lists manipulations 
user interaction using input/output APIs
string manipulation
differences between list types in Java


2. IDE Familiarization: 
I tryed three famous: VScode, Eclipse, IntelliJ. 
Then chosen was:  

3. Maven: 
What's? Used for? 
Usability of Dependency Management with
 application packaging 

4. Unit Testing
Automated Testing for Java Operations
Optional: TDD - If you want to try TDD, you can start the development of every feature by first writing a failing unit test, and then, creating the code that will make that test pass;

5. Development best practices backed by Open Source:
Version Control & Collaboration practices 
Documentation for users and collaborators;


## Demonstration

Gif or Youtube link with demonstration of app:
[Link]()


## Contributions

Contributions are always welcome!
if you are Developer and you want to contruiting with this:
You have to pay attencion of this Pre-requisites:
- java 21
- IDE
- Maven
- Junit

