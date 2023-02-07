AirBnB cloneDescription
This is the first phase of the Airbnb Clone: the console. This repository holds a command interpreter and classes (i.e. BaseModel class and several other classes that inherit from it: Amenity, City, State, Place, Review), and a command interpreter. The command interpreter, like a shell, can be activated, take in user input, and perform certain tasks to manipulate the object instances.

How to Use Command Interpreter
Colons can be used to align columns.

| help        | help                     | display all command available                                |
| ------------|:-----------------------: | ------------------------------------------------------------:|
| create      | create <class>           | creates new object (ex. a new User, Place)                   |
| update      | User.update              |   updates attribute of an object                             |
| destroy     | User.destroy('123')      |    destroys specified object                                 |
| show        | User.show('123')         | retrieve an object from a file, a database                   |
| all         | User.all()               | display all objects in class                                 |
| count       | User.count()             | returns count of objects in specified class                  |
| quit        | quit                     | exits                                                        |

  Usage
Interactive Mode

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
  
  
  Non-Interactive Mode

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
  
  Environment
Language: Python3
OS: Ubuntu 20.04 LTS
Style guidelines: [PEP 8 (version 3.10)](https://peps.python.org/pep-0619/) || [Google Style Python Docstrings](https://sphinxcontrib-napoleon.readthedocs.io/en/l%5Catest/example_google.html) || [WC3 Validator](https://github.com/holbertonschool/W3C-Validator)
Authors
Jenyo Olumide & Osaze Nwandibie
