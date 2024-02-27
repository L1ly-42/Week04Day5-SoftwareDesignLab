1. What do we mean by **coupling** and **cohesion** when discussing structured design?
>Coupling refers to the degree in which modules depend on each other, and cohesion refers to the degree in >which elements within a module group together to perform a specific task. 
>
>Low coupling (in which modules are independent of each other) and high cohesion (in which elements of a module are closely related for the purposes of fulfilling a task) best describes structured design. 

2. What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?
 
>Bottom-up design works by building the lowest level components first and then using them to build larger >and larger components until the whole system has been created.
>
>Top-down design works the opposite way, by first outlining the system as a whole and then gradually breaking this down into smaller and smaller components until you have gotten to the lowest level component. 
>
>Top-down design best describes function-oriented design. 

3. In which design methodology would a **class diagram** be most useful?
>Object oriented design.


4. What are the **four pillars of object oriented programming**? Give a single-sentence description of each.
>The four pillars are abstraction, encapsulation, inheritance and polymorphism. 
>
>Abstraction is the process of hiding the internal details or processes of something. Encapsulation is the process of wrapping certain data and functions into a singular object. Inheritance refers to the creation of a new class from a pre-existing class in which the new (child) class inherits the properties and methods of the pre-existing (parent) class. Finally, polymorphism refers to the ability of an object to take on different forms. 


5. What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?

>Strategy pattern is a behavioural design pattern that allows you to split the behaviour of an object into an encapsulated set of classes with different implementations that can then be swapped in and out at runtime. 
>
>In an object-oriented system this is done by creating an overarching interface over which there will be multiple classes with slightly different implementations of that interface. 
>
>In a functional oriented design this is done by defining multiple functions that implement the different strategies and then using a higher-order function to encapsulate them (either by taking returning the lower-order functions or taking these functions as arguments). 


6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
>I would use object-oriented design as it would allow for more flexibility in implementing my system cross-sector via the use of polymorphism and encapsulation.  

 