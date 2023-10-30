#Software Design Methodoligies Research Lab

### 1. What do we mean by coupling and cohesion when discussing structured design?

Structire design follows the approach of creating a well-organised and systematic method before the actual coding begins. One of the key principles of this includes breaking down the software into smaller and more managble modules/compoents. The idea of cohesion is where these components are related to eachother by focusing on a single, clearly defined task or purpose. If the components within a module are closely related and work well together to achive a distince objective, 
we call this High Cohesion. This can helps make the code maintainable and flexible to work with and aligns well with the Single Responsibility Principle (SRP) from SOLID principles. Whereas, coupling,refers to the degree of interdependence between modules/components within a software system. It measures how much one module relies on or is connected to another module. For example, low coupling indicates that the modules are loosely connected and can be modified or replaced with minimal impact on other parts of the system. This relates to the Dependency Inversion Principle (DIP) from SOLID principles.

### 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

Top-down design involves creating the system as a whole, amd then you progressivley break it down into smaller and smaller componenets. So you basically begin with the higher level structure and functionlaity of the systema and then iron out the details at the lower structure levels. Whereas bottom-up design is the opposite, You start the design process by creating individual components or modules. Then you assemble them to form more complex, higher-level structures. This approach involves starting with the specifics and gradually building towards the overarching system architecture. 

Function oriented design focuses on the functionality of individual functions and their interactions in order to accomplish the system's goals. This approach is more closely aligned with top-down design since it places an emphasis on breaking down the system into functions or procedures. For example, it involves initially identifying the primary function and then decomposing it into smaller functions to attain the system's objectives.

### 3. In which design methodology would a class diagram be most useful?

A class diagram would be most useful in an object oriented design. This is because class diagrams are based around objects and are used to represesnt classes, objects' properties and methods. Having a class diagram helps define the object structure of the system and in objected orientated design, software systems are structured around objects. Hnece class diagrams would be most useful for object orientated design.

### 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

In object orineted programming the four pillars are:

* **Encapsulation** - concept of putting together properties and methods that operate on these properties into a single unit known as a class

* **Abstraction** - simplifies complex systems by modelling classes based on their essential properties and behaviors, this hides unnecessary information while keeping what's relevant

* **Inheritance** - allows the creation of new classes based on existing classes, which reuses the coded that establishes a sub-class from the original class

* **Polymorphism** - allows objects of diffrenet classes to be treated as part of a common superclass

### 5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?


The strategy pattern is a s a design pattern that lets you switch between different algorithms, making it easy to change an object's behavior without modifying its structure. It provides flexibility to select algorithms at runtime, reducing the dependency on specific algorithms in code. 

The implementation of the strategy pattern using object oriented system you would create a set of classes that represent different methods. Each class would contain properties and methods and that would implement a common interface or inherit from a common class. One particular class would then need to use a specific method to swith between different strategies. This class assigns the task of executing the algorithm to the presently chosen strategy object. Whereas using function oriented system you don't need classes and objects, you can use higher-order functions to achieve the same behavior decoupling. In a functional system, you define strategies as functions, and you pass them as arguments to other functions. 


### 6. Imagine your creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I would suggest using object oriented system as you can use functionality of data within objects and classes. For example, each class can represent a specific part of the payment system, whethe its a shopping cart or a particular payment methods. This makes the system more flexible and adaptable to change. The ideas of inheritance and polymorphism in object oriented programming allows you to create specialised classes from more general ones, and can enable diverse objects to exhibit distinct responses to identical method calls, a crucial feature for managing a range of payment methods and specific needs in various sectors. Overall, I thik it is a more flexible and scalable approach for thos particular system.













































