
### Object Oriented Programming

It is a type of programming in which programmers define not only the data type of a data structure, but also the types of operations (functions) that can be applied to the data structure. In this way, the data structure becomes an object that includes both data and functions. In addition, programmers can create relationships between one object and another. For example, objects can inherit characteristics from other objects.

One of the principal advantages of object-oriented programming techniques over procedural programming techniques is that they enable programmers to create modules that do not need to be changed when a new type of object is added. A programmer can simply create a new object that inherits many of its features from existing objects. This makes object-oriented programs easier to modify.
Object

Objects are the basic run-time entities in an object-oriented system. Programming problem is analyzed in terms of objects and nature of communication between them. When a program is executed, objects interact with each other by sending messages. Different objects can also interact with each other without knowing the details of their data or code.

An object is an instance of a class. A class must be instantiated into an object before it can be used in the software. More than one instance of the same class can be in existence at any one time.
Class

A class is a collection of objects of a similar type. Once a class is defined, any number of objects can be created which belong to that class. A class is a blueprint, or prototype, that defines the variables and the methods common to all objects of a certain kind.
Instance

The instance is the actual object created at runtime. One can have an instance of a class or a particular object.
State

The set of values of the attributes of a particular object is called its state. The object consists of state and the behaviour that's defined in the object's class.
Method

Method describes the object’s abilities. A Dog has the ability to bark. So bark() is one of the methods of the Dog class.
Message Passing

The process by which an object sends data to another object or asks the other object to invoke a method. Message passing corresponds to "method calling".
Abstraction

Abstraction refers to the act of representing essential features without including the background details or explanations. Classes use the concept of abstraction and are defined as a list of abstract attributes.
Encapsulation

It is the mechanism that binds together code and data in manipulates, and keeps both safe from outside interference and misuse. In short, it isolates a particular code and data from all other codes and data. A well-defined interface controls the access to that particular code and data. The act of placing data and the operations that perform on that data in the same class. The class then becomes the 'capsule' or container for the data and operations.

Storing data and functions in a single unit (class) is encapsulation. Data cannot be accessible to the outside world and only those functions which are stored in the class can access it.
Inheritance

It is the process by which one object acquires the properties of another object. This supports the hierarchical classification. Without the use of hierarchies, each object would need to define all its characteristics explicitly. However, by use of inheritance, an object need only define those qualities that make it unique within its class. It can inherit its general attributes from its parent. A new sub-class inherits all of the attributes of all of its ancestors.
Polymorphism

Polymorphism means the ability to take more than one form. An operation may exhibit different behaviours in different instances. The behaviour depends on the data types used in the operation.

It is a feature that allows one interface to be used for a general class of actions. The specific action is determined by the exact nature of the situation. In general, polymorphism means "one interface, multiple methods", This means that it is possible to design a generic interface to a group of related activities. This helps reduce complexity by allowing the same interface to be used to specify a general class of action. It is the compiler's job to select the specific action (that is, method) as it applies to each situation.
Generalization

Generalization describes an is-a relationship which represent a hierarchy between classes of objects. Eg:- a "fruit" is a generalization of "apple", "orange", "mango" and many others. animal is the generalization of pet.
Specialization

Specialization means an object can inherit the common state and behavior of a generic object. However, each object needs to define its own special and particular state and behavior. Specialization means to subclass. animal is the generalization and pet is the specialization, indicating that a pet is a special kind of animal.
Advantages of OOP

Object-Oriented Programming has the following advantages over conventional approaches:

    OOP provides a clear modular structure for programs which makes it good for defining abstract data types where implementation details are hidden and the unit has a clearly defined interface.
    OOP makes it easy to maintain and modify existing code as new objects can be created with small differences to existing ones.
    OOP provides a good framework for code libraries where supplied software components can be easily adapted and modified by the programmer.
