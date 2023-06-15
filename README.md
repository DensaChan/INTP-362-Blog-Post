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
There are many environments to practice Python. you could easily download the classic notepad++ or use modern IDE's such as VS Code or a replica of Databricks which is Jupiter notebooks. In my second blog post, I will be using Jyuptier notebooks to show a demonstration of data cleaning and how we can simply manipulate tables, create aggregations and clean data to be digested for stakeholders to make data-driven decisions. Before we get into that, we are required to learn the basics. 

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
 
### Summary
This is just a brief introduction how to we can quickly learn python as we are Java Experts. Do you feel like we could have used Python than Java while we were in school?? Maybe there is a much deeper pool of Python but there are only so many hours in a day. So what's next? Let us have some fun and take off one of our previous assignments in our last semester course with algorithms and apply it in Python. I wonder if our hundreds of lines of code could be cut in half. Well, you just have to stay tuned and see.
