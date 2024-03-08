# Object Types / Data Types

- Number : Integers(1234) --- Complex Numbers(3+15j) --- Float(3.14) --- Decimal() --- Fraction()

- String : e.g ---> 'harsh' , "Bob's" , b'a\x01c

- List : Ordered collection of items which can be of different types. [1,2 [3,4], 5]

- Tuple : Ordered collection of items similar to list, but immutable. (1, "two", 3.0)

- Dictionary : An unordered collection of data in a key:value pair form. {"name": "John", "age": 30}

- Set : An unordered collection of unique items.{1, 2, 3, 4, 5}
- frozenset : Immutable form of a set. frozenset({1, 2, 3, 4, 5})

- File : In Python, when discussing "file types," we're generally referring to the mode in which files are opened or the format of the files being handled. Python doesn't have a built-in, explicit "file type" like it does for integers, strings, or lists. Instead, files are dealt with using file objects, and the operations you can perform on these objects depend on how they were opened.

  You open a file in Python using the `open()` function, which returns a file object. This function takes two main arguments: the file path and the mode.

      - file_object = open('path/to/file', 'mode')

  # Modes of opening file in python :

  `'r'`: Read mode (default). Opens a file for reading.

  `'w'`: Write mode. Opens a file for writing, creates the file if it doesn't exist, and truncates the file to zero length if it does.

  `'a'`: Append mode. Opens a file for writing, creating the file if it doesn't exist, and appends to the end of the file if it does.

  `'x'`: Exclusive creation. Fails if the file already exists.

  `'b'`: Binary mode. Opens a file in binary mode (e.g., `'rb'` or `'wb'`).

  `'t'`: Text mode (default). Opens a file in text mode.

  `'+'`: Update mode. Allows reading and writing to the same file

  Example : Reading a text file

      with open('example.txt', 'r') as file:

      content = file.read()

      print(content)

  This example opens `example.txt` in read mode, reads its content into the variable `content`, and then prints that content. The `with` statement ensures that the file is properly closed after its suite finishes, even if an exception is raised at some point.

- Boolean : Represents True or False

- None : In Python, the `None` type is a special data type that represents the absence of a value or a null value.

- Functions : A function is a block of organized, reusable code that is used to perform a single, related action.

- Modules : A module is a file containing Python definitions and statements. The file name is the module name with the suffix `.py` added. Modules can define functions, classes, and variables, and can also include runnable code. They enable you to organize your Python code logically. Sharing and reusing code is simple with modules because you can import a module into your current script or interactive instance of the interpreter.

  Save this code in a file named mymodule.py

      def greeting(name):

      print("Hello, " + name)

- Classes : A class is a code template for creating objects. Objects have member variables and have behavior associated with them. In Python, a class is created by the keyword `class`, and it supports concepts of inheritance and polymorphism, allowing new classes to be derived from existing classes and objects to be treated as instances of their parent class.

- Some advance topics to be covered in future :

  - Decoraters

  - Generators

  - Iterators

  - MetaProgramming
