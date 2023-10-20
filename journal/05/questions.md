# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, Destroy |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Create-Post, Read-Get, Update-Put, Destroy-Delete |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | ORM stands for Object-Relational Mapping. we use Mongoose when interacting with MongoDB |

04. Which two `HTTP` request types include a body?

  > | Post and put |

05. In a/an __1._____ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an ____2.___ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | 1. synchronous
      2. asynchronous |

06. What are the three types of data relationships? Provide an example of each.

  > | One To One: a person only has one SSN 
      One To Many: one person with many books
      Many To Many: students courses at a university students can have many courses and the university can have many students |

07. What is middleware?

  > | It's a piece of software that is in the middle of parts of our application(s) that allows the components of the application(s) to talk to each other and connect |

08. The ___1.___ pipeline delivers information from the client while the __2.____ pipeline returns it. Fill in the blanks. 

  > | 1. request
      2. response |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | https://localhost:3000/api/weather?season=winter |

10. What is a ***virtual property***?

  > | It's a property that isn't stored in the database or set up in the Schema but rather computed from other properties or data |
