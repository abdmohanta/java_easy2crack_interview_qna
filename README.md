# java_easy2crack_interview_qna
Java Interview Questions and answers from zero to hero.

Q1. What is Java?

Ans : Java is a high-level, object-oriented, robust, secure programming language. It is platform-independent, high-performance, multithreaded, and portable. It was developed by James Gosling in June 1991. It is also known as a platform because it provides its own JRE and API.

Q2. What is Constructor ?

Ans : Constructors should have the same name as that of the class. Whenever an object is created, constructor is called. Constructors do not have any return type.
We can use access modifiers and keywords in constructors. By supplying values to constructors, we can create multiple constructors. In constructor, method name and class name can be same.

Q3. What is Constructor Overloading ?

Ans : Here we create more than one constructor in the same class provided that they have different number of arguments or different types of arguments.

Q4. What is JDK ?

Ans : JDK stands for Java development kit. It helps us to compile .java file to .class file.

Q5. What is JRE ?

Ans : JRE stands for java runtime environment. It helps us to run .class file.

Q6 . What is New Keyword

Ans : New keyword sends request to the class to create object.
New keyword mandatorily calls constructor. Once object is created, then it gets its address and stores that in a reference variable.

Q7 . What is This Keyword ?

Ans : It is a special reference variable that holds object address. This keyword gets created automatically.
This keyword points to current object running in the program.
We cannot use this keyword inside static method.
Using this keyword we can call constructor.

Q8 . What is Constructor Chaining ?

When we call a constructor from another constructor using this keyword then it is called Constructor Chaining.

Q9 . What is Instance Variables ?

Ans : Instance variables in Java are non-static variables which are defined in a class outside any method, constructor or block.

Q10 . What is Static Variable ?

Ans : Static variables can be accessed using class name.
      Static variables can be accessed by static and non-static methods.
      Static variable is like a global variable and is available to all methods.

Q11 . What is Non-Static Variable ?

Ans : Non-static variables can be accessed using instance of a class.
      Non-static variables cannot be accessed inside a static method directly.
      Non-static variable is like a local variable and can be accessed only through instance of a class.

Q12 . What is Inheritance ?

Ans : Here we inherit the members from parent class to child class with an intention of reusing them.

Q13 . What is Packages ?

Ans : Packages are nothing but folders created in Java where programs can be stored in an organized manner.
Packages resolve naming convention problem.

Q14 . What is Advantages of Inheritance ?

Ans : Inheritance minimizes identical code as it allows sharing of common code among subclasses.
 Inheritance makes the code flexible to change.
 With the help of inheritance, we can override the methods of base class.

Q15 . What is Polymorphism ?

Ans : Here we can develop a feature in a way that it can take more than one form.
Polymorphism is applicable only on methods.

There are two ways we can achieve polymorphism:
i) Overriding
ii) Overloading

Q16 . What is Overriding?

Ans : Here we inherit a method from parent class and modify its logic in child class by once again creating same method in child class.

Advantages of Polymorphism (Overriding)

If we inherit 10 methods but want to modify logic of some methods, then the option is overriding.

@Override
@Override annotation checks whether overriding is happening or not. If not, then it reports an error.

Q17. Can we override static method?

Ans: No. In Java static members are not overridden (they are hidden), because overriding is based on inheritance of instance methods.

Q18. What is Overloading ?

Ans: Developing more than one method in the same class provided that they have different number of arguments or different types of arguments is called Overloading.

Q19. Type Casting / Data Type

Ans: Converting particular data type into required data type is called type casting.

There are two types:
I. Auto Up Casting
II. Explicit Down Casting

Q20 . What is Auto Up Casting ?

Converting smaller data type to bigger data type is called Auto Up Casting. During auto up casting data loss does not happen.


























