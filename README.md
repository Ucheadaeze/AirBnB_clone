<<<<<<< HEAD
The AirBnB Clone Project
=======
# The AirBnB Clone Project
>>>>>>> 6cc68fbf0ef45dbdc5fb2e07b2d9297650c0d368


![AIR BNB](https://user-images.githubusercontent.com/111281385/217294692-8bb440e5-ad96-40aa-83ad-c38c53617e20.JPG)
## Project Description
This is the start of the AirBnB clone project, the console will serve as the core of the back-end and would be written in Python. This console will connect directly to storage engines; The database and File storage but we would be focusing on the file storage.

Data generated are stored in a json file and can be accessed with the help of the json module in python.

## Command Interpreter Description:
The interface of the application is just like Shell except this is limited to a specific use-case  because of the limited number of accepted commands that were solely defined for the purposes of the usage of the AirBnB website. In this case, we want to be able to manage the objects of this project.

Some of the commands available are;
- create
- count
- destroy
- show
- update

Below are the objects we need to be able to manage the project;
- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

## How to start it
We would start by cloning the repository of the project from Github, which would contain the simple shell program and its dependants.

After cloning the repository then we change directory into the repository AirBnb_clone. Then create files that would allow the program to run.

## How to use it
There are two different modes that it can work with; Interactive mode and Non-Interactive Mode

### Interactive Mode

In this Mode, the console will display a prompt (hbnb) indicating that the user can write and execute a command. After the command is run, a prompt will appear and wait for a new command. This can go indefinitely as long as the user does not exit the program.

```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit
<<<<<<< HEAD
(hbnb) 

(hbnb) 
=======

(hbnb) 
(hbnb) 
>>>>>>> 6cc68fbf0ef45dbdc5fb2e07b2d9297650c0d368
(hbnb) quit
$
```

### Non-Interactive Mode

 In this mode, the shell will need to be run with a command input piped into its execution so that the command is run as soon as the Shell starts. In this mode no prompt will appear, and no further input will be expected from the user.

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```
  
 ## Examples
 
  ```
user@ubuntu:~/AirBnB$ ./console.py
(hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
user@ubuntu:~/AirBnB$ ./console.py
```

or

```
user@ubuntu:~/AirBnB$ ./console.py $ echo "create BaseModel" | ./console.py
(hbnb)
e37ebcd3-f8e1-4c1f-8095-7a019070b1fa
(hbnb)
user@ubuntu:~/AirBnB$ ./console.py
```
