# Final  Task Lab 1: MySQL Basis

## ***Create an events table with fields***

- event_id (int, auto-increment, primary key)

- event_name (VARCHAR, up to 255 characters, not null)


![image](https://github.com/user-attachments/assets/c328ba0b-3dea-4d73-8ce0-7179a7eba54b)


## ***Create an attendees table with fields***

- attendee_id (int, auto-increment, primary key)

- attendee_name (VARCHAR, up to 255 characters, not null)


![image](https://github.com/user-attachments/assets/8f03e3ab-68e2-4d6e-9912-49b02854c60c)





## ***Create an event attendees table with fields***

- event_id (int, foreign key to events.event_id)

- attendee_id (int, foreign key to attendees.attendee_id)

- Composite primary key on (event_id, attendee_id)
  

![image](https://github.com/user-attachments/assets/aed5b3e1-cf83-49a3-8d33-7ac6e75789ae)





## ***Create an event sponsors table with fields***

- sponsor_id (int, auto-increment, primary key)

- event_id (int, foreign key to events.event_id)

- sponsor_name (VARCHAR, up to 255 characters, not null)


![image](https://github.com/user-attachments/assets/652b46db-af74-471f-9272-51139eb0ec13)


 ## ***EER DIAGRAM***
![image](https://github.com/user-attachments/assets/c043820b-369b-4fbe-8c68-ac5dfba101fb)
