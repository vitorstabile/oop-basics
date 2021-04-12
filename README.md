Object Oriented

THE 4 PILLARS OF OBJECT ORIENTATION: Abstraction, encapsulation, inheritance and polymorphism.

**Abstraction**: How it represents a real object in our system. It must have identity (Class) given by properties (attributes) and methods (functions).

o Class: Structured type that can contain members - Representation of an entity (Product, Customer), service (ProductService, CustomerService), drivers (ProductController), utilities (calculator) and others (views, repositories).
o Attributes (Data or Fields - Ex: Customer has attribute name, email, cpf and etc.)
o Methods (Class functions and operations - Ex: Consult email, consult cpf, change cpf)

• A class can also have:
o Constructors (Special class operation, performed at instantiation of the class. Used to start attribute values ​​or to force the object to receive data or dependency on its instantiation (Dependency injection))
o Overload of constructors or methods (Esoecify more than one constructor or method in the class)
Encapsulation (Getters and Setters)
o Inheritance (from whom this class inherits)
Polymorphism (A class has several forms or functions)

• Object: They are the instance of the class or instance of the type - Ex: Product p1, Client customer1
• Class: It is the definition of the type (Customer Class, Product Class)

• Instantiation: When we instantiate primitive variables (double, int, String ...) it is instantiated in the memory stack. When the command New in Objects, Arrays and Lists is communicated, the dynamic location of memory occurs, where the object is allocated in another area of memory, called Heap and the object will point to the memory address.

• Advantages of object orientation:
o Reuse of the code and delegation of responsibilities

**Encapsulation**: Adds security to an object-oriented application, as it hides class properties.

o An object must not expose any attributes (use of access modifiers - private, protected ...)
o Class attributes are usually accessed by special methods (Getters and Setters), avoiding direct access to the object's property.
o Analogy with a television: When you click on the call button, we do not know what happens internally on the TV. We can say that the methods that connect the TV are encapsulated.


**Inheritance**: Type of association between classes that allows a class to inherit all data and behavior from another
o Can be used for code reuse
o Used for polymorphism - A class has several uses
The whole class java me, inherits from Object (Warper Classes)


**Polymorphism**: A feature that allows variables of the same more generic type to be able to point to objects of different specific types, thus having different behaviors according to each specific type. In some cases, we must perform the upcasting or dowcasting of the object.
