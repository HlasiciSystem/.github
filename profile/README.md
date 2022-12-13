# ATA
The system allows the teacher to keep track of which students currently have a question, prioritazing the order of the students in which they "raised" their hand. The teacher can create classes and add students either from groups or individualy. The created class is either active or inactive resulting in the students being able to join only the active calsses. What each user role is capable of doing will be discussed below.[^1]



## Admin
- Has access to endpoints which allow him import new students and teachers. 
- Can create groups including students and teachers.

## Teacher
- Can create a new class and add groups or indivudual users to it.
- Has a permision to activate or deactivate a class.
- Is able to modify the class - adding/removing users, renaming, deleting
- Can see the users with a question inside an active room they own.
- Has the ability to mark student's question as "done", removing the student from the queue.

## Student
- Can enter/leave an active room which they are a part of.
- Can ask a question and be put in a queue.
- Can see his position in the queue.

[^1]: All of the below functionality is a subject to possible change in the 
future.
