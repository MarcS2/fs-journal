# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows us to inherit properties and methods from other classes. Which can provide be code reusability among other things. |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | A child class inherits all the members that the parent class allows. Access modifiers allow the parent to control the visibility and accessibility of the members that the child class inherits. |

3. How does ***accessibility*** affect inheritance?

  > | It allows a class to control visibility and accessability when being inherited from. For example a private property on a class will not be accessible through inheritance unless the child class in nested in the parent class. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is the primary key of a specific table foreign key refers to another tables primary key and sets it to the current tables foreign key|

5. What is an ***alias***?

  > | A substitute name for something i.e const shortName = longName; |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | 
  SELECT 
  p_d.*,
  doc.*,
  pat.*
  FROM patient_doctors
  JOIN doctors doc ON doc.id = p_d.doctorId
  JOIN patients pat ON pat.id = p_d.patientId
  
   |
