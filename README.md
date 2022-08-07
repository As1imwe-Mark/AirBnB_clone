# AirBnB_clone
![AirBnB-clone](https://user-images.githubusercontent.com/45605340/123508318-7b8d7680-d623-11eb-8a71-0766401ea648.png)
# Background Context
## Welcome to the AirBnB clone project! (The Holberton B&B)
** The Console **
### This is the first step towards building full web application: the AirBnB clone
### The console will be a tool to validate this storage engine. it's first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”. This means: from console code (the command interpreter itself) and from the front-end and RestAPI that will be built later
   * create data model
   * manage (create, update, destroy, etc) objects via a console / command interpreter
   * store and persist objects to a file (JSON file)
    Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
# Installation
### Clone this repository in your terminal:
***

$ git clone https://github.com/Byenkya/AirBnB_clone.git
$ cd AirBnB_clone
---
# Execution
### shell should work like this in interactive mode:
```Python
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
### shell should work like this in non-interactive mode:
```Python
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
# Examples
``` Python
root@5cdda6ce3:/AirBnB_clone# ./console.py                                                                                                                   
(hbnb) help                                                                                                                                                     
                                                                                                                                                                
Documented commands (type help <topic>):                                                                                                                        
========================================                                                                                                                        
EOF  all  create  destroy  help  quit  show  update                                                                                                             
                                                                                          
(hbnb) create                                                                                                      
** class name missing **                                                                                                                
(hbnb)all                                                                                                       
[BaseModel] (b6a6e15c-c67d-4312-9a75-9d084935e579) {'my_number': 89, 'name': 'My First Model', 'updated_at': datetime.datetime(2017, 9, 28, 21, 5, 54, 119434), 'id': 'b6a6e15c-c67d-4312-9a75-9d084935e579', 'created_at': datetime.datetime(2017, 9, 28, 21, 5, 54, 119427)}                                                            
(hbnb)                                                                                              
 ```
# Authors
***
  * Byenkya Joshua Aaron
  * Godwin Brown
---
