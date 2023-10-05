# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | encapsulation, inheritance, polymorphism, and abstraction |

02. How does `export` differ from `export default`?
  
  > | with export you can export many values, but with export default you can only export one. When importing a default export you can give it a custom name normal exports the name must match. |

03. What is Encapsulation?
  
  > | encapsulation is building out data and methods together usually stored in a class that aren't accessible by methods other than ones in that class |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | ANSWER HERE |

05. What the difference between a `class` and an instance of a `class`?
  
  > | classes are like templates for objects that will tell what the object to do and how to act an instance of a class is an actual object that is based off the template from the class that is essententialy a copy of the actual class that when modified won't actually change your data. |

06. What is a computed Property?
  
  > | ANSWER HERE |

07. What is the purpose of the `MVC` pattern?
  
  > | The purpose of MVC patterns is to separate your code and make it so that everything has a specific job to fulfill. This makes it easier to modify the code, fix any bugs, scale up projects, and create a more secure space for your data and methods. |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | The controllers job is to do exactly that it is a controller for the service and model it tells them what to do and when generally determined by user input the controller is the only one that ever talks back to the view for that reason data is never changed with the controller |

09. What is the job of the `Service` in `MVC`?
  
  > | The service's job is to take in instructions from the controller and change the data appropriately based on those instructions the service doesn't talk to the controller it only changes runs methods and changes data based on what the controller wants |

10. What is the job of the `Model` in `MVC`?
  
  > | The model job is to store and manage the data |
