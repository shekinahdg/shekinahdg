# Transforming ER Model to Relational Tables

## ***Create the Student Table with Fields***

- username (STRING, VARCHAR(50), PRIMARY KEY)

  ![image](https://github.com/user-attachments/assets/49a46ab5-1098-425e-8959-5df3a6479541)

## ***Create the Assignment Table with fields***

- shortname (STRING, VARCHAR(50), PRIMARY KEY)
- due_date (DATE, NOT NULL)
- url (STRING, VARCHAR(255), NOT NULL)

  ![image](https://github.com/user-attachments/assets/ddd576ae-ca5e-4705-851f-80b74badc0ce)

## ***Create the Submission Table with fields***

- username (VARCHAR(50))
- shortname (VARCHAR(50))
- version (INT)
- Submit_date (DATE, NOT NULL)
- data (TEXT)

  ![image](https://github.com/user-attachments/assets/637655ea-0cd6-4273-85dc-4ad2015e3ac0)

## ***EER Diagram***

  ![image](https://github.com/user-attachments/assets/c150a269-6112-47f2-a7ed-d4e91cfa628c)
