# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | They help organize give structure |

02. What is the difference between a `class` and an `interface`?

  > | A class is a blueprint of objects you can make instances of classes. interfaces define methods you can't make instances of interfaces and they  |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | constructor() |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | public |

06. In the Car example what is `string` an indication of?

  > | The type of data that the method will return |

07. In the Car example what is `abstract` preventing?

  > | This will prevent you from creating a new instant of a car class i.e new Car() |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | info in a row is referring to a row of info or info on a specific row. info in a column is a specific type of data e.i. id, title, name |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE IF NOT EXISTS characters
  (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name CHAR(255) NOT NULL,
    age INT NOT NULL,
    description VARCHAR(500) NOT NULL
  ) default charset uft8 COMMENT '' |

10. In SQL how can you query more than a single table? Provide an example.

  > | SELECT h.* o.* FROM homes h JOIN owners o ON o.id = h.ownerId |
