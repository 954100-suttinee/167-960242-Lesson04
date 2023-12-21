## [Lesson04](../readme.md) > Exercise02:

1. Open class [Main](../src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code to call run() method from `exercise02`.


2. Edit class [Lesson](../src/main/java/org/dii/oop/exercise02/Lesson.java) in package `main.javaorg.dii.oop.exercise02` and follow the instructions below:
    
   * Write a program to print out the student names by following the instruction below: 
      * Create a `Student` class in the `main.java.org.dii.oop.exercise02` package.
      * If no argument name is passed to the constructor while creating an object of the `Student` class.  The name of a student should be "Unknown", otherwise the name of a student should be the passed String value. 

    ```
   ...
   
   public class Lesson {
     public static void run() {
       Student s = new Student("James");
       Student a = new Student();

       System.out.println(s.name);
       System.out.println(a.name);
     }
   }
   ```

3. Run the code. The output should be: 
   ```
   James
   Unknown
   ```
   
4. Modify the `Student` class
   * add more attribute to store more information e.g. lastname. 
   * modify constructor to accept a new argument(s)
   * create a new method in the class, which is called as `displayStudentInfo`. This method prints all the values of the attributes. 
   * Test by creating five new instances(objects) and print out the information. 
   