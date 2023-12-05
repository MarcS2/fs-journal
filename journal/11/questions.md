# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | ANSWER HERE |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | ANSWER HERE |

3. How does ***accessibility*** affect inheritance?

  > | ANSWER HERE |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is the primary key of a specific table foreign key refers to another tables primary key and sets it to the current tables foreign key|

5. What is an ***alias***?

  > | ANSWER HERE |

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
