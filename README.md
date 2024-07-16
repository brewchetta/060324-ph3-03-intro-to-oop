# Object Oriented Programming in Python

## Learning Goals

- Importing modules

- Benefits and Principles of OOP Design

- Classes

- Instances

- Initializing with attributes using init

- Instance methods

- Showing instances using repr

- Self

- Stretch Topics: Object properties

- Stretch Topics: Class attributes and methods

## Exercises:

1. Humans initialize with a `first_name` and `last_name`.

2. Humans initialize with an `_age` of 0. This will be a property (`age`) later.

3. Give humans a `__repr__` that adequately shows their characteristics. You decide what this looks like.

4. Give humans a method `say_full_name` which returns their concatenated `first_name` and `last_name`.

6. Give humans a property `age`. When someone attempts to set a human's `age` directly it instead doesn't change and returns the string `"Quit lying about your age!"`.

5. Give humans a method `happy_birthday` which increments that human's age by 1.

## Can You Answer:

1. What is the difference between a class and an instance?

2. What is a magic method?

3. When does `__init__` happen?

4. When does `__repr__` happen?

5. What is a property?

6. Why is it important to use a private attribute inside a property?