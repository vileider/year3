
# https://www.linkedin.com/learning/software-design-modeling-with-uml/a-picture-is-worth-a-thousand-words?u=56746241
I tried to implement Observer method for the game project . Most of the tutorials were explaining how to do it with UML Unified Modeling Language. Such a complex subject was hard enought by it self so I had to start a UML course at linked in learning.

Models divide in to:
Computotial:
* Computer simulations represaenting tme-varying behavior of system
Analytical:
* Maathematical models of a relationships among variales in a system
Nonalanlitical/descriptive:
* Descriptive components and their relationship in a system

Models of software :
* UML
* SysML
* BPMN

UML is esepcialy for OOP.
UML cna be drawn in 3 diagarms:
1. Structure -Represents static view of the system and components
2. Behavior - Represents dynamic view of the system and its compoenents
3. Interaction - Represents interaction:
    * Among components of the system
    * Between system and external actors

Class Diagram
* Name of the class
* variables
* Methods
Key elements:
* Classifiers (Represents the types of entities in my system)
 An abstract metaclass whose concrete subclasses clasify differend types of values
 - Concrete class
    REGULAR FONT
 - Abstract class
    ITALITALCIZED
 - Interface
    LOLIPOP
 - etc.
* Features (Structural and behavioreal characteristic of these entities)
 Structural and behavioreal characterisitics of a classifier
 - Structural, properties or attributes
    VISIBLITY:
    * "-" private
    * "#" protected
    * "~" friendly
    * "+" public
    MULTIPLICITY:
    * "*" zero or more
    * "1.." one or more
    * "1" one exactly
    * "m..n" between m and n
    PROPERTY-MODIEFIER:
    * id
    * readOnly
    * ordered | unordered
    * unique | ununique
    * etc.
 - Behavioral, Operations or methods
* Relationships (depicts how these entities are related to each other)
 - Associations
    * Agregation, shared ownership(hollow diamond, stays in the system)
    * Composition, not shared(filled diamond, stays only when needed)
 - Generalization
    * inheritance
 - Dependecy
    * relationship between class and interface( dashed arrow)
    * thight copuled class

Object Diagram
* Objects(name underlined)
* Slots (attributes, but not all)
* Relationships

# https://medium.com/@bindubc/association-aggregation-and-composition-in-oops-8d260854a446#:~:text=Aggregation%20is%20a%20specialized%20form,or%20child%20and%20vice%20versa.

# https://www.youtube.com/watch?v=ZWEgBSarE3M

# https://blog.visual-paradigm.com/what-are-the-six-types-of-relationships-in-uml-class-diagrams/

# https://umlboard.com/docs/relations/

# https://www.javatpoint.com/uml-relationship

# (BOOCH, 2017)

# https://www.uml-diagrams.org/composition.html
Relationships:

1. Inheritance:(empty arrow), example[car share vehicle feature with taxi or bus]
* "In the inheritance relationship, the subclass inherits all the functions of the parent class, and the parent class has all the attributes, methods, and subclasses. Subclasses contain additional information in addition to the same information as the parent class."

2. Realization:(filled arrow), example[the functionality go, stop, must be included in vehicle ]
* "interface (including an abstract class )"
* " is a collection of methods. In an implementation relationship, a class implements an interface, and methods in the class implement all methods of the interface declaration."
* "one thing specifies the behavior or a responsibility to be carried out, and the other thing carries out that behavior. "

3. Association:(line with number of associations), example: [student and univerity]
* "one class holds a reference to another, e.g., through a property or a field."
* "connection between one type of object and another type of object."
* " four kinds of associations : two-way associations , one-way associations , self-association , and multiple-number associations ."
* "associations can further be differentiated into Aggregations and Compositions."

4. Composition:(filled diamond), example: [head and body]
* "The combination relationship represents the relationship between the whole and part of the class, and the overall and part have a consistent lifetime. Once the overall object does not exist, some of the objects will not exist, and they will all die in the same life."
* "stronger parent-child hierarchical relationship. They are best used when the class holding the reference owns the referenced object and controls its lifetime."
* "It forms a two-way relationship."
* "The whole and its parts cannot be separated."

5. Aggregation:(empty diamond), example: [book and the student]
* "objects are part of the overall object, but the member object can exist independently from the overall object"
* "association class holds only a shared reference of the other, i.e., both types are connected, but their lifetimes do not depend on each other."
* " it cannot include more than two classes. [book cannot be with two students at the same time]"
* Class B can affect on A and in reverse

6. Dependecies:(dash line and arrow), example: [car and gasoline]
* "dependencies are reflected in methods of a class that use another class’s object as a parameter ."
* "only temporary or restricted to a single method or constructor."
* "change in either the structure or the behavior of the class that affects the other class, such a relationship is termed as a dependency. "
* "A dependency is a using relationship, specifying that a change in the specification of one thing may affect another thing that uses it, but not necessarily the reverse."
* The dependency relationships represent a weaker coupling where the class A relies on the functionality provided by classes B or C without having direct control over their instances.

7. Generalization:
* "concept called inheritance or is-a relationship. It exists between two objects (things or entities), such that one entity is a parent (superclass or base class), and the other one is a child (subclass or derived class). These are represented in terms of inheritance. Any child can access, update, or inherit the functionality, structure, and behavior of the parent."

BOOCH, G. (2017) ‘chapter 5 and 10’, in Unified modeling language user guide. ADDISON-WESLEY. 