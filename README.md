Java Projects Repository
* Java is an object oriented language (OOP). Objects in Java are called "classes"

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

Resources:
http://www.learnjavaonline.org/en/Hello%2C_World%21
