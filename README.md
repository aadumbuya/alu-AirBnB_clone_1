
# AirBnB Clone

Welcome to the AirBnB Clone project!

## Project Description

This is the first step in building an Airbnb clone web application. In this step, we will create a command interpreter to manage Airbnb objects. This command interpreter will be used as the foundation for the entire project, including HTML/CSS templating, database storage, API, and front-end integration.

## Learning Objectives

By the end of this project, you are expected to be able to explain:

- How to create a Python package
- How to create a command interpreter in Python using the cmd module
- What is Unit testing and how to implement it in a large project
- How to serialize and deserialize a Class
- How to write and read a JSON file
- How to manage datetime
- What is a UUID
- What is *args and how to use it
- What is **kwargs and how to use it
- How to handle named arguments in a function

## Command Interpreter

### What's a Command Interpreter?

A command interpreter is similar to a shell, but it's limited to a specific use-case. In our case, we want to be able to manage the objects of our project, including:

- Creating a new object (e.g., a new User or a new Place)
- Retrieving an object from a file, a database, etc.
- Performing operations on objects (e.g., counting, computing stats, etc.)
- Updating attributes of an object
- Destroying an object

The command interpreter allows you to perform various actions on Airbnb objects, making it a fundamental part of our project.

### How to Start

To start the command interpreter, run the following command in your terminal:

```shell
./console.py
```

### How to Use

Once the interpreter is running, you can use the following commands:

- `create`: Create a new Airbnb object.
- `show`: Retrieve information about an object.
- `update`: Update the attributes of an object.
- `destroy`: Delete an object.
- `all`: List all objects or objects of a specific class.
- `quit` or `EOF`: Exit the program.

## Testing

Unit tests for the HolbertonBnB project are defined in the `tests` folder. To run the entire test suite simultaneously, execute the following command:

```shell
$ python3 -m unittest discover tests
```

Alternatively, you can specify a single test file to run at a time:

```shell
$ python3 -m unittest tests/test_console.py
```

## Authors

- Marie Joselyne NYAMPINGA
- Alhassan Dumbuya

