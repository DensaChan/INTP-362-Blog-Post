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

### Java and python comparision
So in our intro to programming courses we learn about variables, datatypes, loops, if statements and methods which are known as functions in python. Lets view the difference between the two code blocks then discuss the main differnece between the two programming languages.
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

Lets start with Java, We notice the additional lines that are required such as annouceing a class, the main class in-order for the program to run. Python you can see it is much simuplier and to some opinion, much easier to read. Additionally, we are able to notice the lack of data stype declaration in the code block of python. 
What does loops look like in python compared to java. Lets have a look below.

In java we know there are 3 different types of loops. For, While, Do-While loops. Heres a quick reminder of what they look like.
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
