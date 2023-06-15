# INTP-362-Blog-Post-1

## From Java to Python
If you are reading this blog, you must be a current or new grad from a software development major, comp sci, or software eng student. You may even be a STEM student who wants to learn Python for data analytics. Well, you have found the right place as this is where I will take someone proficient in Java or just even new to programming.

#### Why Python? 
In 2022, Github posted the top programming languages for 2022 with Python overtaking Java. Python is the number 10 top-growing programing language by 22.5%. For those new to programming, python is a user-friendly language as quoted by its creator Guido van Rossum "There's only one way to do it, and that's why it works". Those who have played with previous programming languages, quickly learn there are many ways to write code and often we spend more time debugging than writing code. Python only requires a simple syntax structure and is generally more concise and simply just easier to read.
So what are simular and different in Java and Python??
Lets start with Syntax. They both do have simular syntax structures but java has a few requirements to ensure there are no syntax errors. Java requires the use of semicolons, braces, curly braces to define blocks of code. Python other hand only requires indentation. 
Both language supports object-oriented programming. We are now masters of OOP in java but if we were to look into OOP in python, we will discover a more flexible and expressive approach with OOP in python. How? Well python allows you to define classes and objects in a brief and clear expressive manner. 
Lastly, python offers a collection of libaries for different use cases such as data anlysis such as NumPy or Pandas. Cute names ehhh??? 

### Environments (IDE)
There are many environments to practice Python. you could easily download the classic notepad++ or use modern IDE's such as VS Code or a replica of Databricks which is jupyter notebooks. In VS code, it is as simple as just downloading the python extention in the extention tab. So why did i mention jupyter  notebook/databricks. If being a data anlyst or data engineer, Jetbeans intoduce the adaption of SQL and  python together to manipluate data. As someone who has a background in data analytics, Our previous courses in SQL or evern PLSQL can be done much simpplier in python. Now it is beyond this blog on discussing what data anlaytic tools and their advatnages but in short, it is nice to see your results quickly than to run through a terminal. 

### Writeing your first program: Hello World
Lets get to you to write you first program and to see the difference between Java and Python in the most begginer code. To print hello world. (does this bring you back to your first programming class?).

Java
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Python
```python
print("Hello, World!")
```

You can see how simple python is compared to Java is.

### Java and Python comparision
So in our Intro to programming courses, we learn about variables, datatypes, loops, if statements and methods which are known as functions in Python. Let us view the difference between the two code blocks and then discuss the main differences between the two programming languages.
We are going to write a program that checks if a student is passing their class or not.

Java
```Java
public class HelloWorld {
    public static void main(String[] args) {
        double grade = 0.65;
        String Name: David;

        // If statement
        if (grade >= 0.5) {
            System.out.println(Name + " Is passing school");
            } 
            else {
                System.out.printlin(Name + " Is not passing school");
                }
    }
}
```
Python
```Python
grade = 0.65
name = David

# If statemnt
if grade >=05:
    print(name + " Is passing school")
else:
    print(name + " Is not passing school")
```
Let us start with Java, We notice the additional lines that are required such as announcing a class, the main class for the program to run. Python you can see is much simpler and to some opinions, much easier to read. Additionally, we can notice the lack of data type declaration in the code block of Python. 
What do loops look like in Python compared to Java? Let us have a look below.

In java, we know there are 3 different types of loops. For, While, Do-While loops. Here's a quick reminder of what they look like.

Java
```Java
// For loop
for (int i = 0; i < 5; i++) {
    System.out.println("The current iteration is: " + i);
}

// While Loop:
int j = 0;
while (j < 5) {
    System.out.println("The current iteration is: " + j);
}

// Do-While Loop:
int k = 0;
do (
    System.out.println("The current iteration is: " + k);
    k++;
) while (k < 5);
```

Python
```Python
# For Loop:
for i in range(5):
    print("The current iteration is: ",  i)
    
# While Loop
while i < 5:
    print("the current interation is: ", i)
    i += 1
```

Python is no different than Java with its operators and expressions for calculations. So that's a plus!

### Data Structures
Most likely, any programming student has been through some kind of data structure course. A common data structure used is Array(s). So what are the main differences between Java and Python with Arrays? Well, we know that Arrays are fixed-sized and require explicit initiation. The elements are accessed using [ ] brackets and .length is used to determine the size of the array. Python, lists are dynamic and can be initialized directly with elements. Elements too are accessed by the same square brackets and the len() function I used to determine the size of the list. 
P.S. Do you remember the difference between Arrays and ArrayLists? Great just making sure. We are just going over arrays here.
 Let us go over an example
 
 Java
 ```Java
 // initlization and declaration of a Array in Java
 int[] list = new int[5];
 list[0] = 10;
 list[1] = 20;
 list[2] = 30;
 list[3] = 40;
 list[4] = 50;
 
 // retrieving the elements by their index
 int firstNumber = list[0];
 int fifthNumber = List[4];
 
 // interating through the list
 for (int i = 0; i < list.length; i++) {
    System.out.println(list[i]);
 }
 ```
 
 Python
 ```Python
    # initlization and declaration of a array in Python
    list = [10, 20, 30, 40, 50]
    
    # retrieving the elements by their index
    firstNumber = list[0]
    fifthNumber = list[4]
    
    # iterating through the list
    for list in list:
        print(list)    
 ```
 
 Wow, Look how simple Pythong is compared to Java!
 
### Methods Vs Functions
We know that a clean code is short, readable code. So creating methods or inline methods but in python known as functions are important. Everybody love clean code right??
Lets quickly review the structure or how a method declaration in java would look like:
```Java
public int methodName(int a, int b) {
    // Method body
    // Write some genius code here
    return result;
```

Python
```Python
def function_name(a, b):
    # function body
    # Big brain code goes here
    return result
```
 
 So the biggest diffefence we can see is Python does not require the user to decalre data types. Additionally java methods include modifiers such as public, private, protected while python does not have explicit access modifers. Now naming conversion, in python it is knowns to have a different naming convetion, and you may agree to disagree. I am sure in this blog post I my self have made a few error as I too am trained in Java I am used to the Java namming convention. Python does not fololow camel case as they just use underscores (_). So, how many mistake I have made?
 
 
### Object-Oriented Programming
This might be the most imporant topic/comparision. So before we review on how the code looks, we wnat to talk about the differences in OOP in python comapred to java:
    1. Reminder in python focuses on indentation to define blocks and java uses braces and semicolons
    2. static and dynamic: Java is static and pythong id dynamic. Java requires declarations in variables and method parameters while python being dynamic allows you to assign values to            different types of variables without declariing their data types.
    3. Modifiers. Java has explicit access modifiers that can contorl visability and accessbility of class members. wPython has no explicit cyntax for access modifiers.
    4. Method Overloading. Java supports method overloading which means methods may have the same name but with different paramters requirements. Python does not support overlaoding but can        still be achieved by using different parameter values or using variable-length arguments
    
  Lets take a classic example as seen in one of our courses. Students and courses as we can relate!

Java

Student Object
```Java
public class Student {
    private String name;
    private int age;
    private String studentId;

    public Student(String name, int age, String studentId) {
        this.name = name;
        this.age = age;
        this.studentId = studentId;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }

    public String getStudentId() {
        return studentId;
    }

    public void enrollCourse(Course course) {
        // Add the student to the course enrollment list
        course.addStudent(this);
    }
}
```

Course Object
```Java
import java.util.ArrayList;
import java.util.List;

public class Course {
    private String name;
    private List<Student> students;

    public Course(String name) {
        this.name = name;
        students = new ArrayList<>();
    }

    public String getName() {
        return name;
    }

    public void addStudent(Student student) {
        students.add(student);
        System.out.println(student.getName() + " has been enrolled in " + name);
    }

    public void displayEnrolledStudents() {
        System.out.println("Enrolled students in " + name + ":");
        for (Student student : students) {
            System.out.println(student.getName());
        }
    }
}
```

Main Method
```Java
public class Main {
    public static void main(String[] args) {
        Student student1 = new Student("John", 20, "A001");
        Student student2 = new Student("Jane", 22, "A002");

        Course course = new Course("Programming 101");
        student1.enrollCourse(course);
        student2.enrollCourse(course);

        course.displayEnrolledStudents();
    }
}
```

Now lets do the same in Python to see what it looks like.

```Python
class Student:
    def __init__(self, name, age, student_id):
        self.name = name
        self.age = age
        self.student_id = student_id

    def get_name(self):
        return self.name

    def get_age(self):
        return self.age

    def get_student_id(self):
        return self.student_id

    def enroll_course(self, course):
        course.add_student(self)
 ```
 The main difference is the lack of variable decalartion. additionally the "method" __init__ is known to be the construcotr. This method is to initlize the attributes of an object.
 Lets create the course class
 
 ```Python
 class Course:
    def __init__(self, name):
        self.name = name
        self.students = []

    def get_name(self):
        return self.name

    def add_student(self, student):
        self.students.append(student)
        print(f"{student.get_name()} has been enrolled in {self.name}")

    def display_enrolled_students(self):
        print(f"Enrolled students in {self.name}:")
        for student in self.students:
            print(student.get_name())
 ```
 
 And the "main" program/class to put it all together
 
 ```Python
 from student import Student
from course import Course

if __name__ == "__main__":
    student1 = Student("John", 20, "A001")
    student2 = Student("Jane", 22, "A002")

    course = Course("Programming 101")
    student1.enroll_course(course)
    student2.enroll_course(course)

    course.display_enrolled_students()
 ```
 
 Lets explain the built in function "__name__" as you may have notice
 "__name__" variable commonly used to indentify the difference between a main module and imports. This ensures your included code in the script should only run when the script is ran directly but not when it is imported. So, by using `if __name__ == "__main__":` ensure that a function is only called when a program is ran as the main program, and not when it is imported by another program. This is commonly used when testing or running specific blocks of code.
 
### Summary
This is just a brief introduction how to we can quickly learn python as we are Java Experts. Do you feel like we could have used Python than Java while we were in school?? Maybe there is a much deeper pool of Python but there are only so many hours in a day. So what's next? Let us have some fun and take off one of our previous assignments in our last semester course with algorithms and apply it in Python. I wonder if our hundreds of lines of code could be cut in half. Well, you just have to stay tuned and see.
