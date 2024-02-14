I tryied to understand the abstract clases interfaces and protocols to enhance 
coding practices related to game project.

I looked at :
# Interfaces
https://www.youtube.com/watch?v=3ajdzrx5NNk
In Python, interfaces are used to define a set of methods that a class must implement. While Python does not have built-in support for interfaces as some other languages like Java, the concept can still be applied through abstract base classes (ABCs) or by using the typing module's Protocol class (introduced in Python 3.8). Protocols allow for duck typing, letting you specify which methods and properties are expected without forcing a class to inherit from a specific superclass. This approach is useful for ensuring a class adheres to a particular interface without strict inheritance, promoting flexibility and dynamic type checking.

# Abstract class
https://www.youtube.com/watch?v=UDmJGvM-OUw
The video is about how to use abstract classes and abstract methods in Python. Abstract classes are classes that cannot be instantiated, but can be inherited by other classes. Abstract methods are methods that are declared in an abstract class, but do not have any implementation. They must be overridden by the subclasses that inherit from the abstract class. The video explains the concept and purpose of abstract classes and methods, and shows how to use the abc module to create and use them in Python1.

# Abstract classes vs Interface
https://www.youtube.com/watch?v=BNrCFrrXn3Q

# Protocols vs Abstract classes
https://codingshortcuts.com/abc-vs-protocol-python/

The difference between Python abstract class and Python protocol is that abstract class defines a strict interface for a set of related classes, while protocol defines a flexible interface for any object that implements the required methods or attributes

We managed to create a inheritance and dependency flowchart after design session
http:\\bitbucket\year3\images\12_02_2024_design_chart.png

I also have found a data class

https://www.youtube.com/watch?app=desktop&v=CvQ7e6yUtnw

Data classes are a simplified way to create classes with data and various features, such as default values, post_init, and freezing. Python 3.10 adds new capabilities to data classes, such as kw_only, match_args, slots, and structural pattern matching, which improve their functionality and performance.