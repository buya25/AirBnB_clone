# AirBnB Clone Project - Command Interpreter

Welcome to the AirBnB Clone project! This project is the first step towards building a full web application, an AirBnB clone. In this initial step, we will create a command interpreter to manage AirBnB objects, such as users, states, cities, and places.

## Table of Contents

- [Description of the Project](#description-of-the-project)
- [Description of the Command Interpreter](#description-of-the-command-interpreter)
- [How to Start the Command Interpreter](#how-to-start-it)
- [How to Use the Command Interpreter](#how-to-use-it)
- [Examples](#examples)

## Description of the Project

The AirBnB Clone project aims to build a web application by completing several tasks, including:
- Creating a parent class (BaseModel) for object initialization, serialization, and deserialization.
- Establishing a flow for serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Creating classes for AirBnB objects (User, State, City, Place, etc.) that inherit from BaseModel.
- Implementing the first abstracted storage engine of the project: File storage.
- Writing unit tests to validate all classes and the storage engine.

## Description of the Command Interpreter

The command interpreter in this project is designed to help manage AirBnB objects. It allows you to perform the following operations:
- Create a new object (e.g., a new User or a new Place).
- Retrieve an object from a file, database, etc.
- Perform operations on objects (e.g., count, compute stats, etc.).
- Update attributes of an object.
- Destroy an object.

## How to Start It

To start the command interpreter, follow these steps:

1. Clone the AirBnB Clone repository from GitHub.

2. Navigate to the project directory.

3. Run the command interpreter by executing the `console.py` script:

   ```
   $ ./console.py
   ```

## How to Use It

Once the command interpreter is running, you can interact with it by entering commands. The basic format of the interpreter prompt is `(hbnb)`. You can type your commands after the prompt.

For example:
```
(hbnb) create User
```

To get help on available commands, you can use the `help` command:

```
(hbnb) help
```

## Examples

Here are some examples of how to use the command interpreter:

1. Creating a new User object:
   ```
   (hbnb) create User
   ```

2. Listing all available commands:
   ```
   (hbnb) help
   ```

3. Quitting the command interpreter:
   ```
   (hbnb) quit
   ```
