# Relational Databases #

### What is a Database? ###


Before computers, we still had databases. These were filing cabinets with multiple drawers and lots of bits of paper within the drawers.

A specific cabinet may have held records about a University. One drawer is labelled 'Teachers' and holds slips of paper with information about each teacher. Another is labelled 'Classes' and contains a list of different classes, their times and who teaches them. Another is 'Students' and lists all the students' details as well as what they're studying.

We can do the exact same thing with a modern, computerised database. We have our filing cabinet - the database itself - which we've given a name, like 'University'. We have our drawers - tables - each with its own unique name, like 'Students', 'Classes' or 'Teachers'. In each table, we hold records of data. Now that data isn't on slips of paper, but is held within computer memory.

This also keeps the records more consistent, as each table expects the same data each time.

### But what makes this 'Relational'? ###

What makes a relational database is, as the name suggests, relations.

We have a list of classes. That class will have a teacher. We also have a list of teachers. Therefore, the Classes table and the Teachers table are related.

![Image of 2 boxes that hold headings of data that would be held in them. They are titled Teachers and Classes and have a line joining them on a heading that is the same in both of Class_Id](https://github.com/annemck/SQL_Teaching/blob/RelationalDatabases/images/SimpleRelationalDiagram.png?raw=true)
