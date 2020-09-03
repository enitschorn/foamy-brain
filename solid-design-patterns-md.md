# Solid Design Patterns

##### S - Single Responsibility Principle 
  - A class should have one, and only one, reason to change
  - Do one thing and do it well
  - Focus your methods and classes on one thing and let them do it well
  - Ask yourself: What is the responsibility of your class/component/microservice? - if your answer contains an "and" you're most likely breaking this principle
  
##### O - Open Closed Principle
  - Be open for extension, closed for modification
  - You can add to your classes, but don't modify them
  - Think of a house - if you need an extra bedroom, you can build an extension. If you want a new basement, you make things way more complicated and risk ruining your house
  
##### L - Liskov Substitution Principle
  - Derived classes can stand in for base classes
  - Program to an interface
  - Imagine a beer tab in a bar - if the bar wants to swap out one type of beer, they don't have to rip out the tab, the tubes, etc. They just have to swap out the barrel, flush the tubes and they're good to go

##### I - Interface Segregation Principle
  - Make fine grained interfaces client specific
  
##### D - Dependency Inversion Principle
  - Depend on abstractions, not concrete implementations
