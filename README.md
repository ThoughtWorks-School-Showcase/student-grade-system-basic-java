# Student Grading System（Basic OOP）

## Business Requirement:

We are going to develop an application. The application is a command line user interface application. When the program starts, we will see the main menu print at the command console as follows:

```
1. Add Student 
2. Generate Students Score Sheet 
3. Exist
Plase input your choice（1～3）： 
```

If we input 1，the application will display：

```
Please input student info（Format：Name, Number, Subject1: Score1, ...）
Press click Enter key to submit： 
```

If the input format is incorrect，the application will display：

```
Please input the correct format（Format：Name, Number, Subject1: Score1, ...）： 
```

If we input correct message, the application will display:

```
Student xxx's score has been added successfully! 
```

Then the application prints the menu again on the console:

```
1. Add Student 
2. Generate Students Score Sheet 
3. Exist
Plase input your choice（1～3）：
```

Now we come back on the main menu again. 
If we input 2，the application will display：

```
Please input the student number whose information you want to print（Format： number1, number2,...），
Press click Enter key to submit： 
```

If we input the correct message, the view will display:
```
Please input the correct student number（Format： number1, number2,...），
Press click Enter key to submit： 
```

If we input the correct message, the application will display the score sheet, and print the main menu:

```
1.	 SCORE SHEET
2.	 Name|Math|Chinese|English|Program|Average|Total
3.	 ======================== 
4.	 Tom|75|95|80|80|82.5|330 
5.	 Jason|85|80|70|90|81.25|325 
6.	 ======================== 
7.	 The Average of Total Score：xxx 
8.	 The Middle og Total Score：xxx 
```

If the student number that we input does not exist，the number will be ignored in the calculation process.

## Challenges in the Exercise:
a)	Simple OO design base on Java Grammar.
b)	Command line input and output operation.
c)	Flow Command Query Separate principle to design methods in class.
d)	Flow GRASP Pattern: Information Expert to design responsibility for class.     
e)	Output and Input Separate for whole App.
f)	Regex implementation in java for validation.
g)	Unit Test coverage more than 80%.
h)	Mock strategy for different real world implementations.
i)	Data encapsulation due to abstract real world things.

## Practice Requirement:
a)	Define the tasks which includes the functions: input, output and model. 
b)	Draw the tasking graph.
c)	Make the task list for whole app, task list should include all the things for building app. The task list shouldn't be just for coding implementation.
d)	Write the test cases for all modules in task list.
e)	Write test cases.
f)	Apply the TDD process.
g)	Refactor the code with the small steps.
h)	Coding by IDE shortcuts.
i)	Commit the code change by the small steps with meaningful comment.

## Deliverable:
Please push your deliverables and codes to the repository site which coach will tell you. The repository should include：
a)	Tasking file: tasking.md.
b)	Tasking graph: put to the image folder under root.
c)	Code for the unit tests and implementation.
d)	The screenshot of the running app with all operation. Please put them to the result folder under root. (The file name: xxx.png)

## How to Begin:

Get the practice repository:
```
 git clone https://github.com/ThoughtWorks-School-Showcase/student-grade-system-basic-java
```

Stack Initial and build:

```
Mac/Linux: ./gradlew idea   
Whindows:  gradlew.bat idea  
```
```
Mac/Linux: ./gradlew clean build   
Whindows:  gradlew.bat clean build 
```

Test:
```
Mac/Linux: ./gradlew clean test 
Whindows:  gradlew.bat clean test.
```


## Learn Resourse(Chinese Version):
1. [任务分解](https://www.zybuluo.com/jtong/note/504192)
2. [Gradle基础教程](http://tutorials.jenkov.com/gradle/gradle-tutorial.html)
3. [Java 基础](http://www.runoob.com/java/java-tutorial.html)
4. [Git 参考手册](http://gitref.org/zh/index.html)
5. [Junit](http://junit.org/junit5/docs/current/user-guide/#writing-tests-assertions)
6. [Mockito](http://site.mockito.org/)

