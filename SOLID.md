Guidelines for development using SOLID Principles OOD.

**S - Single responsibility principle**
  a class should have only a single responsibility (i.e. changes to only one part of the software's specification should be able to affect the specification of the class)
  a class should have only one reason to change (i.e. one job. Don't add functionality for logging in your User Class)
  
**O - Open/closed principle**
  “software entities … should be open for extension, but closed for modification.” use inheritance and overide.
  Don't make a new method in a class - make a new class inherit from the old class, in new class overwrite method.
  
**L - Liskov substitution principle**
  “objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.” See also design by contract.
  
**I - Interface segregation principle**
  “many client-specific interfaces are better than one general-purpose interface.”
  Client should not be forced to implement an interface if it doesn't use it.
  
**D - Dependency inversion principle**
  "one should “depend upon abstractions, not concretions."
  High level modules should not depend on low level modules.
      
