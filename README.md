# AirBnB Clone - The console
the console for airbnb project. Create a command interpreter that can modify or delete the database
The users like the administrator of the app Airbnb clone has the posibility of the manipulate objects and data of the application, this objects are:
 
 * Users
 * Places
 * States
 * Cities
 * Amenities
 * Reviews


![alt text](https://i.ibb.co/RSzZ5yh/815046647d23428a14ca.png)

 
 
## Installation
 
 For use this console you need to have:
 * Linux ubuntu 14.04.3 LTS or higger
 * Python 3.7 or higger

## Files



 -  HBNHCommand: console.py
 -  Amenity: models/amenity.py
 -  BaseModel: models/base_model.py
 -  City: models/city.py
 -  models.init : models/__init__.py
 -  Place: models/place.py
 -  Review: models/review.py
 -  State: models/state.py
 -  User: models/user.py
 -  FileStorage: models/engine/file_storage.py
 -  engine.init: models/engine/__init__.py

```
How To run the command interpreter:
```
$ ./console.py


## Examples

Interactive mode:
```
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
Non-interactive mode:
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

## AUTHORS
 
* **Boumaiza Kais** - [Boumaiza-kais](https://github.com/Boumaiza-kais)
* **Lafine Sami** - [afinesami](https://github.com/afinesami)