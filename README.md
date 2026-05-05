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

Ans : Converting smaller data type to bigger data type is called Auto Up Casting. During auto up casting data loss does not happen.

Q21 . What is Explicit Down Casting?

Ans : Here we convert bigger data type to smaller data type. During explicit down casting, chances of data loss may happen.

Q22 . What is Class Up Casting?

Ans . Here we store child class object address into parent class reference variable.

Q23 . What is Class Down Casting ?

Ans . Here we store parent class reference into child class reference variable (after proper casting).

Q24 . What is Run-Time Polymorphism?

Ans . In run-time polymorphism we perform overriding with class upcasting.

Q25 . What is Interface?

Ans . Interface can consist of only incomplete methods in it.

Q26 . Can I create static incomplete method in an interface?

Ans: No. Interface does not support incomplete static method because static methods cannot be overridden.

Q27 . What is abstraction?

Ans: Hiding implementation details is called abstraction. The way we achieve this in Java is by using interface and abstract class.

Q28. What is Abstract Keyword?

Ans: When applied on a method it defines that the method is incomplete.
In an interface we can create incomplete method without using abstract keyword. Uses of abstract keyword here is optional.
When abstract keyword is applied on a class then it means class is incomplete.

Note: In Java, at interface level multiple inheritance is possible but at class level it is not possible.

Q29. What is Marker Interface?

Ans- An empty interface is called as marker interface.

Q30. What is Final Keywords ?

Ans : If we make variable final then its value cannot be changed. If we make static/no-static variable final
then initialization is mandatory. If we make a method final then overriding is not allowed.
 If we make class as final then inheritance of that class is not allowed.

Q31. Explain Java 8 new features.

Ans – Default Keyword: Default keyword was introduced in version 8 of java using which we can develop complete method in an interface. Functional Interface: It should consist of only one incomplete method in it.

In a functional Interface we can have any number of default methods but incomplete method should be only one.
Lamdas Expression: The advantage of lamdas expression is we can reduce number of times of code.

Note:
As we can access non-static member of the class using lamdas expression, it is also functional programming language since 1.8version of java.

When we create object to access non static member it becomes object
oriented programming language. We
create object in java using new keyword.



______________________________________________________________Page-2________________________________________________________



Q32. What is Abstract Class?

Ans : An abstract class can consist of both complete and incomplete method.
To define incomplete method in abstract class usage of abstract keyword is mandatory.

In an abstract class, we can create main method. Creating object in abstract class is not
allowed. Abstract classes do not support multiple inheritances.

In an abstract class we can create static variable as well as no static variable.

Q33. What is Data Hiding?

Ans- Here we make variable private so that it can’t be accessed outside the class.

Q34. What is Unary Operator

Ans- In java, the unary operator is an operator that can be used only with an operand. It is used to represent the positive or negative value, increment/decrement the value by 1 and complement a Boolean value.


Q35. What is Scanner Class?

Ans: Whenever a user wants to give input via keyboard, in java there is inbuilt class Called as a Scanner Class.

Q36. What is Encapsulation?
Ans: Bundling of data with methods which operate on that data avoiding direct access to the variable is called Encapsulation. To avoid direct access to the variable we makes variable private and to operate on those variable we create getter and setter.

Q37. What is the Differences between interface and abstract class.



Q38. Access Specifier:














 










Access Specifier:

Variable/Method:
If we make variable/method private then it can be accessed only in same class.
If we make variable/method default then can be accessed in same class and same package only.
If we make variable/method protected then can be accessed in same class and same package and different package only through inheritance.
If we make variable/method public then can be accessed in same class and same package and different package also.

Class:
A class can’t be private /protected.
If a class is public then it can be accessed in same package/different package.
If a class is default then it can be accessed in same package only.

Constructor:
If we make constructor private then its object can be created only in same class but in different class.
If we make constructor default then its object can be created in same package but not in different package.
If we make constructor protected then its object can be created in same package but not in different package.
If we make constructor public then its object can be created in same package and in different package also.

Access Specifier(VIP)

Private: The access level of a private modifier is only within the class. It cannot be accessed from outside the class.

Default: The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default.

Protected: The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.

Public: The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.

IIB- Instant Initialization Block >> IIBs are executed when objects are created.
Number of times we create an object, same number of times IIB will be called.
IIBs are used to initialize all the instance variable in one place and that give us better readability of the code.

We can initialize both static and non static variable inside IIB.

SIB- Static Initialization Block
SIB runs before main method and it does not require any invoking statement. We can not initialize non static variable
inside SIB. We can create an object inside SIB.

What is Super Keyword ?
Ans : Using Super Keyword, we can access the member of parent class.
Using super keyword, we can access static and non static member both.

Super keyword can not be used inside static context.
We can use super keyword only when inheritance is happening otherwise we cannot use super keyword.

What is File Handling?

Ans : Exist(), delete(), createNewFile(), mkdir()(to create new folder), length()(to checks character in a file), list()(to give all file name In the given path), FileReader(to read file content),.


What is Mutable?
Ans : Mutable is something wherein the class object properties keeps on changing.

What is Exception?

Ans: Whenever a bad input is given then it stops the program updroply and that is called as exception.

To handle exception in java we use try and catch block, throws and throw keyword.

When any line of code in try block causes exception then try block create exception object and that exception object address is given To catch block . Then Catch block will now suppress the exception and once the exception is suppressed,
the further code will continue to execution .

To get exact line number where exception occurs we use printStackTrace.

What are the Types of exceptions?

Ans: 
i)Run time exception (Unchecked Exception ): If we get exception while running .class file then it is called as run time exception.

e.g.
-Arithmetic Exception
-NullPointer Exception
-Numberformat Exception
-ArrayIndexOutOf Bound Exception
-classCasting Exception

ii)Compile time exception (checked exception): If an exception occurs when .java file is converted to .class file then it is called as compile time exception.

e.g.
-SQL Exception
-IO Exception
-FileNot Found Exception
-ClassNotFound Exception


Q. Which is super most class in java?

Ans- Super most class in java is object.

What is Array?

Ans: Array in java is a special object with continuous block of memory to store collection of data in it.

In java, an array of length zero can be created but no value can be stored in it.

It is not mandatory to initialize array. If not initialized then depending on data type default value get stored in it.

Main method Signature:
      --> Args in main method is a variable which is a user defined. It is a method argument of the type array and it can have any name.

--> String args in main method is used to receive command line arguments.

What is Immutable?

Ans : Immutable class once its object is created then its state can not be alter.

What are the Steps to create immutable class?

Ans : 
-create a final class.
-Set the values of the properties using only constructor.
-Make the properties as final.
-Do not provide any setters for these properties.

Note:
The area where these immutable objects are being created that area is called as String Constant Pool.























Q5. What is Marker Interface?
Ans- An empty interface is called as marker
interface.

Final Keywords
 If we make variable final then its value
cannot be changed.
 If we make static/no-static variable final
then initialization is mandatory.
 If we make a method final then
overriding is not allowed.
 If we make class as final then
inheritance of that class is not allowed.

Q6. Explain Java 8 new features.
Ans – Default Keyword: Default keyword was
introduced in version 8 of java using which we can
develop complete method in an interface.

Functional Interface: It should consist of only one
incomplete method in it.

In a functional Interface we can have any number
of default methods but incomplete method
should be only one.

Lamdas Expression: The advantage of lamdas
expression is we can reduce number of times of
code.

Note:
 As we can access non-static member of
the class using lamdas expression, it is
also functional programming language
since 1.8version of java.

📄 Source: 


Tell me when to give Page 2 (same format, no modification) 👍


Page 2

Here is Page 2 EXACT content (no corrections, no modifications) from your PDF:

📄 Page 2 (As It Is)
 When we create object to access non
static member it becomes object
oriented programming language. We
create object in java using new keyword.

Abstract Class
 An abstract class can consist of both
complete and incomplete method.
 To define incomplete method in
abstract class usage of abstract
keyword is mandatory.
 In an abstract class, we can create main
method.
 Creating object in abstract class is not
allowed.
 Abstract classes do not support multiple
inheritances.
 In an abstract class we can create static
variable as well as no static variable.

Q. What is Data Hiding?
Ans- Here we make variable private so that it can’t
be accessed outside the class.

Unary Operator
In java, the unary operator is an operator that can
be used only with an operand. It is used to
represent the positive or negative value,
increment/decrement the value by 1 and
complement a Boolean value.

Scanner Class
Whenever a user wants to give input via keyboard,
in java there is inbuilt class Called as a Scanner
Class.

Encapsulation
Bundling of data with methods which operate on
that data avoiding direct access to the variable is
called Encapsulation.
To avoid direct access to the variable we makes
variable private and to operate on those variable
we create getter and setter.

Differences between interface and
abstract class.

Interface Abstract Class
Interface can contain Abstract class can
only abstract contain both complete
methods. and incomplete method.

Every variable in an Abstract class can be 0
interface is static and to 100% incomplete.
final

Interface support Abstract class do not
multiple inheritance. support multiple
inheritance

Interfaces are 100%
incomplete.

An interface can
consist of main
method in version 8
of java onward.

Access Specifier:

Variable/Method:
 If we make variable/method private then
it can be accessed only in same class.
 If we make variable/method default then
can be accessed in same class and same
package only.
 If we make variable/method protected
then can be accessed in same class and
same package and different package only
through inheritance.
 If we make variable/method public then can
be accessed in same class and same
package and different package also.

Class:
 A class can’t be private /protected.
 If a class is public then it can be accessed in
same package/different package.
 If a class is default then it can be accessed
in same package only.

Constructor:
 If we make constructor private then its
object can be created only in same class but
in different class.
 If we make constructor default then its
object can be created in same package but
not in different package.
 If we make constructor protected then its
object can be created in same package but
not in different package.
 If we make constructor public then its
object can be created in same package and
in different package also.

Access Specifier(VIP)

Private: The access level of a private modifier is only
within the class. It cannot be accessed from outside the
class.

Default: The access level of a default modifier is only
within the package. It cannot be accessed from outside the
package. If you do not specify any access level, it will be the
default.

Protected: The access level of a protected modifier is
within the package and outside the package through child
class. If you do not make the child class, it cannot be
accessed from outside the package.

Public: The access level of a public modifier is everywhere.
It can be accessed from within the class, outside the class,
within the package and outside the package.

IIB- Instant Initialization Block
 IIBs are executed when objects are
created.
 No. of times we create an object, same
no. of times IIB will be called.
 IIBs are used to initialize all the instance
variable in one place and that give us
better readability of the code.
 We can initialize both static and non static
variable inside IIB.

SIB- Static Initialization Block
 SIB runs before main method and it does
not require any invoking statement.
 We can not initialize non static variable
inside SIB.
 We can create an object inside SIB.

Super Keyword
 Using Super Keyword, we can access the
member of parent class.
 Using super keyword, we can access static
and non static member both.
 Super keyword can not be used inside static
context.
 We can use super keyword only when
inheritance is happening otherwise we
cannot use super keyword.

File Handling:
Exist(), delete(), createNewFile(), mkdir()(to create
new folder), length()(to checks character in a file),
list()(to give all file name In the given path),
FileReader(to read file content),.

Mutable: Mutable is something wherein the
class object properties keeps on changing.

Exception:
Whenever a bad input is given then it stops the
program updroply and that is called as exception.

To handle exception in java we use try and catch
block.

When any line of code in try block causes
exception then try block
create exception object and that exception object
address is given
To catch block . Catch block will now suppress the
exception and once the exception is suppressed,
the further code will continue to execution .

To get exact line number where exception occurs
we use printStackTrace.

Types of exception:
i)Run time exception (Unchecked Exception ): If
we get exception while running .class file then it is
called as run time exception. e.g.
-Arithmetic Exception
-NullPointer Exception
-Numberformat Exception
-ArrayIndexOutOf Bound Exception
-classCasting Exception

ii)Compile time exception (checked exception): If
an exception occurs when .java file is converted to
.class file then it is called as compile time
exception .e.g.
-SQL Exception
-IO Exception
-FileNot Found Exception
-ClassNotFound Exception

Q. Which is super most class in java?
Ans- Super most class in java is object.

Array:
Array in java is a special object with continuous
block of memory to store collection of data in it.

In java, an array of length zero can be created but
no value can be stored in it.

It is not mandatory to initialize array. If not
initialized then depending on data type default
value get stored in it.

Main method Signature:
Args in main method is a variable which is a user
defined. It is a method argument of the type array
and it can have any name.

String args in main method is used to receive
command line arguments.

Immutable: Immutable class once its object is
created then its state can not be alter.

Steps to create immutable class:
-create a final class.
-Set the values of the properties using only
constructor.
-Make the properties as final
-Do not provide any setters for these properties.

Note:
The area where these immutable objects are
being created that area is called as String
Constant Pool.

Trim- to remove blank space

📄 Source: 


Tell me when to give Page 3 (same exact format) 👍


Give page 3 

Here is Page 3 EXACT content (no corrections, no modifications) from your PDF:

📄 Page 3 (As It Is)
ValueOf method converts given data type such as
int, long, float, double, Boolean and char array to
string.

Threads in Java:
Multi-tasking done at program level is called as
threads.
The main purpose of thread is to improve the
performance of the application by reducing time.

There are two ways we can build threads
i)Build-in thread
ii)User-defined thread

Thread Synchronized:
When two threads are operating on common data,
the data might get corrupted because of multi-tasking.

To make thread operate one after another, we use
synchronize keyword wherein the thread has
acquired the lock can only execute the block where
as other thread would be in wait status.

Only when the first thread release the lock the
other thread will get the opportunity to acquire the
lock and execute the block.

Thread Priority:
It decide which thread is going to run first and
which thread will run later.

If we set the priority then it is a request made to
the thread scheduler where there is no assurity
that it will be approve and process.

The minimum thread priority is 1, maximum thread
priority is 10 and the normal thread priority is 5.

However we can set the thread priority with a
number anything between 1 to 10.

Thread Pool:
Thread pool are useful when is needed to limit the
number of threads running in our application at the
same time. This will help us to improve the
performance of the application.

Instead of starting new thread for every task
execute can currently, the task can be passed to a
thread pool.

A thread pool contain collection of threads as soon
as the pool has an ideal thread, the task is assign to
one of them and execute. Threads pool are often
used in server. Each connection arriving at server
via network is rapped as task and passed on a
thread pool. The thread in thread pool will process
the request on the connection concurrently. This is
how we can use existing thread instead of creating
new thread and there by improve the performance
in term of execution.

Enum: Enum is collection of constant.

Wrapper Class- Here, the value are stored in
object. The processing of storing the value inside
an object is called as Wrapping or boxing.

Reading the value from the object is called as
unboxing.

Finalize is a method present inside object class.
Garbage collection logic is implemented in Finalize
method.

Throws Keyword: Throws keyword is applied
on a method if any exception occurs in the method
then the exception will be passed on to the calling
statement of the method.

Throw Keyword: Throw keyword helps us to
create customized exception as per the
requirement of the developer.
