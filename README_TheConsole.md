0x00. AirBnB clone - The console
By Guillaume, CTO at Holberton School
Weight: 5
Project to be done in teams of 2 people (your team: Andrea Castrillón Puerta, Brian Zapata
Project over - took place from 06-24-2021 to 07-01-2021 - you're done with 73% of tasks.
Manual QA review was done by Andres Ariza on 07-01-2021.
QA review fully automated.
Concepts
For this project, students are expected to look at these concepts:

Python packages
AirBnB clone
Background Context
Welcome to the AirBnB clone project! (The Holberton B&B)
Before starting, please read the AirBnB concept page.

First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine
What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object
Resources
Read or watch:

cmd module
packages concept page
uuid module
datetime
unittest module
args/kwargs
Python test cheatsheet
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
How to create a Python package
How to create a command interpreter in Python using the cmd module
What is Unit testing and how to implement it in a large project
How to serialize and deserialize a Class
How to write and read a JSON file
How to manage datetime
What is an UUID
What is *args and how to use it
What is **kwargs and how to use it
How to handle named arguments in a function
