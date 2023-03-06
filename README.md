# java_interview_preparation
This is special type of entry in the series, my current girlfriend is learning java, so I will need to remember java so I can help her when the moment of bugs arrive

## Theorical Questions Section

### Theorical Question 1

Do you understand what the javac program is for ?

<details><summary><b>Answer</b></summary>

Turning java source code (file .java) to java classes. these classes are then turned into bytecode

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 2

Do you understand what the javadoc program is for ?

<details><summary><b>Answer</b></summary>

For extracting comments and create documentation in html files

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 3

Do you know what these special words used for ?

abstract
break
finally
implements
interface
this
instanceof
null


<details><summary><b>Answer</b></summary>

...

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 4

Do you know the difference between int, float y double ?

<details><summary><b>Answer</b></summary>

...

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 5

Do you know the outcome of these operations in java ?

7%3

i = 1;
j = ++i;

i = 1;
j = i++;

(byte) 28
(int) (x + 3.14f)
(String)h.get(k)

<details><summary><b>Answer</b></summary>

...

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 5

Do you know the understand what public, private and protected means for variables and functions ?


<details><summary><b>Answer</b></summary>

...

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 6

Do you know what method overloading is ?


<details><summary><b>Answer</b></summary>

Defining multiple methods with the same name (different behaviours explain this better)

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 7

Do you understand what a abstract, final, native, synchronized and static method are ?

<details><summary><b>Answer</b></summary>

![Image](img/java_abstract_final_native.png "java_abstract_final_native")

![Image](img/java_static_syncronized.png "java_static_syncronized")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 8

Do you understand the difference between checked and unchecked exceptions ?


<details><summary><b>Answer</b></summary>

![Image](img/java_checked_and_unchecked_exceptions.png "java_checked_and_unchecked_exceptions")

![Image](img/java_checked_uncheckedexceptions_pt2.png "java_checked_uncheckedexceptions_pt2")

![Image](img/java_checked_unchecked_exceptionspt3.png "java_checked_unchecked_exceptionspt3")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 9

Do you know what the ellipsis (...) mean in the arguments of a method ?


<details><summary><b>Answer</b></summary>

![Image](img/variable_lenght_argList_pt1.png "variable_lenght_argList_pt1")

![Image](img/variable_lenght_argList_pt2.png "variable_lenght_argList_pt2")

![Image](img/variable_lenght_argList_pt3.png "variable_lenght_argList_pt3")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 9

Do you know what lambda is and how to define it in lambda ?


<details><summary><b>Answer</b></summary>

![Image](img/lambda_function.png "lambda_function")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>


### Theorical Question 10

If an array called array_! has ten elments, do you understand why are we getting a ArrayIndexOutOfBoundsException message when we try to access array_1[10] ?


<details><summary><b>Answer</b></summary>

because they are zero indexed (start at 0)

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 11

Do you understand what the difference between a deep copy and a shallow copy in java?


<details><summary><b>Answer</b></summary>

https://howtodoinjava.com/java/array/java-array-clone-shallow-copy/

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 12

wrapper classes,,,, boxing and unboxing conversion, ,,,, they explain this better in head first java

<details><summary><b>Answer</b></summary>

...................................

</details>

<details><summary><b>Source</b></summary>
head first java
</details>

### Theorical Question 13

Do you understand what packages are

<details><summary><b>Answer</b></summary>

![Image](img/java_packages.png "java_packages")

![Image](img/java_package2.png "java_package2")

![Image](img/java_package3.png "java_package3")

</details>

<details><summary><b>Source</b></summary>
head first java
</details>

### Theorical Question 15

Do you know how to especify a different classpath ?

<details><summary><b>Answer</b></summary>

The Java runtime knows where the class files for the standard system classes are located and can load them as needed. When the interpreter runs a program that wants to use a class named com.davidflanagan.examples.Point, it knows that the code for that class is located in a directory named com/davidflanagan/examples/ and, by default, it “looks” in the current directory for a subdirectory of that name. In order to tell the interpreter to look in locations other
than the current directory, you must use the ­classpath option when invoking the interpreter or set the CLASSPATH environment variable.

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 16

Do you know what public static void main(String[] args) is for ?

<details><summary><b>Answer</b></summary>

![Image](img/running_java_program.png "running_java_program")

![Image](img/running_java2.png "running_java2")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 17

Can you create java programs outside of classes ?

<details><summary><b>Answer</b></summary>

Classes are the most fundamental structural element of all Java programs. You cannot write Java code without defining a class. All Java statements appear within classes, and all methods are implemented within classes.

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 18

Do you understand what implementing and extending a class means ,,,,,,,,,,,,,,,,,, head first java explain this better ?

<details><summary><b>Answer</b></summary>

![Image](img/java_extending_class.png "java_extending_class")

![Image](img/java_exteninng_pt2.png "java_exteninng_pt2")

![Image](img/java_extending_pt3.png "java_extending_pt3")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 19

Do you know what transient and volatile variables are ?

<details><summary><b>Answer</b></summary>

...........................

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 20

Do you understand what the super() function is for ?

<details><summary><b>Answer</b></summary>

![Image](img/subclass_constructor.png "subclass_constructor")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>

### Theorical Question 21

Do you understand what overriding a superclass means ?

<details><summary><b>Answer</b></summary>

![Image](img/overriding_in_java.png "overriding_in_java")

![Image](img/java_overriding_pt2.png "java_overriding_pt2")

![Image](img/java_overriding_pt3.png "java_overriding_pt3")

![Image](img/java_overriding_pt4.png "java_overriding_pt4")

![Image](img/java_overriding_pt5.png "java_overriding_pt5")

</details>

<details><summary><b>Source</b></summary>
java in a nutshell, 7th edition
</details>