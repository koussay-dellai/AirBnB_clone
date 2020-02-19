# AirBnB_clone

#Testing
This project uses python library, unittest to run tests on all python files. All unittests are in the ./tests directory with the command:

    File Storage Engine Model:
        $ python3 -m unittest discover -v ./tests/

#All tests
The bash script init_test.sh executes all these tests for both File Storage & DataBase Engine Models:

    checks pep8 style

    runs all unittests

    runs all w3c_validator tests

    cleans up all __pycache__ directories and the storage file, file.json

    Usage init_test.sh:

$ ./dev/init_test.sh

#CLI Interactive Tests
This project uses python library, cmd to run tests in an interactive command line interface. To begin tests with the CLI, run this script:

./console.py


#For a detailed description of all tests, run these commands in the CLI:

(hbnb) help help
List available commands with "help" or detailed help with "help cmd".
(hbnb) help

Documented commands (type help <topic>):
========================================
Amenity    City  Place   State  airbnb  create   help  show
BaseModel  EOF   Review  User   all     destroy  quit  update

(hbnb) help User
class method with .function() syntax
        Usage: User.<command>(<id>)
(hbnb) help create
create: create [ARG] [PARAM 1] [PARAM 2] ...
        ARG = Class Name
        PARAM = <key name>=<value>
                value syntax: "<value>"
        SYNOPSIS: Creates a new instance of the Class from given input ARG
                  and PARAMS. Key in PARAM = an instance attribute.
        EXAMPLE: create City name="Chicago"
                 City.create(name="Chicago")

