# Java Projects Repository
## Basic Java Concepts
* Java is an object oriented language (OOP). Objects in Java are called "classes"
### Example 1
```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

* The first line defines a class called Main (The class and the filename must share the same 'root' class/file, main/main.java)
* The next line is the entry point of our Java program, the main method has to have this exact signature in order to be able to run our program
  * **public** again means that anyone can access it
  * **static** means that you can run this method without creating an instance of Main
  * **void** means that this method doesn't return any value
  * **main** is the name of the method
* The arguments inside the method are what we will get when running the program with parameters, it's an array of strings
  * **System** is a pre-defined class that Java provides us and it holds some useful methods and variables
  * **out** is a static variable within System that represents the output of your program (stdout)
  * **println** is a method of out that can be used to print a line

### Examples 2
Not all types are objects, some are basic variable types called primitives
* Here is a list of all primitives in Java
  * **byte** (number, 1 byte)
  * **short** (number, 2 bytes)
  * **int** (number, 4 bytes)
  * **long** (number, 8 bytes)
  * **float** (float number, 4 bytes)
  * **double** (float number, 8 bytes)
  * **char** (a character, 2 bytes)
  * **boolean** (true or false, 1 byte)
* Java is a strong typed language, which means variables need to be defined before we use them.
Numbers
* To declare and assign a number use the following syntax:
```
int myNumber;
myNumber = 5;
```
* Or you can combine them:
```
int myNumber = 5;
```
* To define a double floating point number, use the following syntax:
```
double d = 4.5;
d = 3.0;
```
* If you want to use float, you will have to cast:
```
float f = (float) 4.5;
```
* Or, You can use this:
```
float f = 4.5f (f is a shorter way of casting float)
```

Characters and Strings
A character is it's own type and it's not simply a number, so it's not common to put an ascii value in it, there is a special syntax for chars:
```
char c = 'g';
```
* **String** is not a primitive. It's a real type, but Java has special treatment for String.
```
// Create a string with a constructor
String s1 = new String("Who let the dogs out?");
// Just using "" creates a string, so no need to write it the previous way.
String s2 = "Who who who who!";
// Java defined the operator + on strings to concatenate:
String s3 = s1 + s2;
```

Boolean
Every comparison operator in java will return the type boolean that not like other languages can only accept two special values: true or false.
```
boolean b = false;
b = true;

boolean toBe = false;
b = toBe || !toBe;
if (b) {
    System.out.println(toBe);
}

int children = 0;
b = children; // Will not work
if (children) { // Will not work
    // Will not work
}
```

Resources:
http://www.learnjavaonline.org/en/Hello%2C_World%21
