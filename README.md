# INTP-362-Blog-Post-1

## From Java to Python
If you are reading this blog, you must be a current or new grad from a software development major, comp sci, or software eng student. You may even be a STEM student who wants to learn Python for data analytics. Well, you have found the right place as this is where I will take someone proficient in Java or just even new to programming.

#### Why Python? 
In 2022, Github posted the top programming languages for 2022 with Python overtaking Java. Python is the number 10 top-growing programing language by 22.5%. For those new to programming, python is a user-friendly language as quoted by its creator Guido van Rossum "There's only one way to do it, and that's why it works". Those who have played with previous programming languages, quickly learn there are many ways to write code and often we spend more time debugging than writing code. Python only requires a simple syntax structure and is generally more concise and simply just easier to read.

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
