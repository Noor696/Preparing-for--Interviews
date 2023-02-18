**1. Is Python a programming language?**

even though scripting can be done in Python, it is thought of as a programming language.

1.1 differences between scripting and programming languages:

- Programming languages: consist of a set of instructions that achieve specific outputs.
- Scripting languages: are programming languages written exclusively for a special run-time.

_____

**2.Could you tell me what are the main features of Python?**

A. Python is an interpreted language. it’s different from C++, which requires the user to compile it before a run.

B. other crucial Python features, there is no requirement to specify particular variables, since Python is classed as a dynamically typed language.

C. functions, which are first-class objects in Python, enable the user to assign them a variable.
______

**3. Explain what are modules in Python?**

modules are critical in Python and are used frequently, modules in Python are best described as files. 
These files hold code, which, in Python, can take the form of a class or a variable.
______

**4. How will you improve the performance of a program in Python?**

There are many ways to improve the performance of a Python
program. Some of these are as follows:

**i. Data Structure:** We have to select the right data structure for our purpose in a Python program.

**ii. Standard Library:** Wherever possible, we should use methods from standard library. Methods implemented in
standard library have much better performance than user implementation.

**iii. Abstraction:** At times, a lot of abstraction and
indirection can cause slow performance of a program. We should remove the redundant abstraction in code.

**iv. Algorithm:** Use of right algorithm can make a big difference in a program. We have to find and select the suitable algorithm to solve our problem with high performance.
____________

**5. What are the benefits of using Python?**

Python is strong that even Google uses it. Some of the benefits of using Python are as follows:

**i. Efficient:** Python is very efficient in memory
management. For a large data set like Big Data, it is much easier to program in Python.

**ii. Faster:** Though Python code is interpreted, still Python has very fast performance.

**iii. Wide usage:** Python is widely used among different organizations for different projects. Due to this wide usage, there are thousands of add-ons available for use with Python.

**iv. Easy to learn:** Python is quite easy to learn. This is the biggest benefit of using Python. Complex tasks can be very easily implemented in Python.

----------
**6. What is Pickling in Python?**

Pickling is a process by which a Python object hierarchy can be converted into a byte stream. The reverse operation of Pickling is Unpickling.

Python has a module named pickle. This module has the implementation of a powerful algorithm for serialization and de-serialization of Python object structure.

Some people also call Pickling as Serialization or Marshalling.

With Serialization we can transfer Python objects over the network. It is also used in persisting the state of a Python object. We can write it to a file or a database.
__________
**7. How does memory management work in Python?**

* There is a private heap space in Python that contains all the Python objects and data structures. In CPython there is a memory manager responsible for managing the heap space. 
* There are different components in Python memory manager that handle segmentation, sharing, caching, memory pre-allocation etc.
* Python memory manager also takes care of garbage collection by using Reference counting algorithm.

----------
**8. How will you perform Static Analysis on a Python Script?**

We can use Static Analysis tool called PyChecker for this purpose.
PyChecker can detect errors in Python code.
PyChecker also gives warnings for any style issues.

Some other tools to find bugs in Python code are pylint and pyflakes.
__________
**9. What is the difference between a Tuple and List in Python?**

* In Python, Tuple and List are built-in data structures.

* Some of the differences between Tuple and List are as follows:

1. **Syntax:** 
A Tuple is enclosed in parentheses:
E.g. myTuple = (10, 20, “apple”)
A List is enclosed in brackets:
E.g. myList = [10, 20, 30]

2. **Mutable:** 
Tuple is an immutable (ثابت) data structure. Whereas, a List is a mutable (متقلب) data structure.

3. **Size:** A Tuple takes much lesser space than a List in Python.

4. **Performance:** Tuple is faster than a List in Python. So it gives us good performance.

5. **Use case:** Since Tuple is immutable, we can use it in cases like Dictionary creation. Whereas, a List is preferred in the use case where data can alter.
____________

**10. What is a Python Decorator?**

A Python Decorator is a mechanism to wrap a Python function and modify its behavior by adding more functionality to it. We can use @ symbol to call a Python Decorator function.
____________

**11. How are arguments passed in a Python method? By value or by reference?**

Every argument in a Python method is an Object. All the variables in Python have reference to an Object. Therefore arguments in Python method are passed by Reference.

Since some of the objects passed as reference are mutable, we can change those objects in a method. But for an Immutable object like String, any change done within a method is not reflected outside.
____________

**12. What is the difference between List and Dictionary data types in Python?**

Main differences between List and Dictionary data types in Python are as follows:

1. **Syntax:** In a List we store objects in a sequence. In a Dictionary we store objects in key-value pairs.

2. **Reference:** In List we access objects by index number. It starts from 0 index. In a Dictionary we access objects by key specified at the time of Dictionary creation.

3. **Ordering:** In a List objects are stored in an ordered sequenc.

4. **Hashing:** In a Dictionary, keys have to be hashable. In a List there is no need for hashing.
