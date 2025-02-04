# Python Project - Task List

This project contains a series of Python tasks focused on object-oriented programming concepts such as inheritance, classes, and methods.

## Task Descriptions

### `0-lookup.py`
- **Task:** Write a function that returns the list of available attributes and methods of an object.
- **Description:** This function takes an object as input and returns a list of all attributes and methods (including inherited ones) of the object.

### `1-my_list.py`
- **Task:** Write a class `MyList` that inherits from `list`.
- **Description:** Define a custom class `MyList` that inherits from the built-in `list` class. This class can be extended with additional functionalities as needed.

### `2-is_same_class.py`
- **Task:** Write a function that returns `True` if the object is exactly an instance of the specified class; otherwise, return `False`.
- **Description:** This function checks whether an object is an exact instance of a specified class, excluding inheritance.

### `3-is_kind_of_class.py`
- **Task:** Write a function that returns `True` if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class; otherwise, return `False`.
- **Description:** This function checks if the object is an instance of the specified class or any class that inherits from it (including indirect inheritance).

### `4-inherits_from.py`
- **Task:** Write a function that returns `True` if the object is an instance of a class that inherited (directly or indirectly) from the specified class; otherwise, return `False`.
- **Description:** This function checks if the object's class is a subclass of the given class, considering both direct and indirect inheritance.

### `5-base_geometry.py`
- **Task:** Write an empty class `BaseGeometry`.
- **Description:** Define a class `BaseGeometry` with no attributes or methods. This is a base class for future extensions.

### `6-base_geometry.py`
- **Task:** Write a class `BaseGeometry` (based on `5-base_geometry.py`).
- **Description:** Implement the class `BaseGeometry` by adding relevant methods (e.g., area calculation) in this version.

### `7-base_geometry.py`
- **Task:** Write a class `BaseGeometry` (based on `6-base_geometry.py`).
- **Description:** Refine the `BaseGeometry` class further by improving its functionality, adding additional checks or attributes.

### `8-rectangle.py`
- **Task:** Write a class `Rectangle` that inherits from `BaseGeometry` (7-base_geometry.py).
- **Description:** Implement the `Rectangle` class that inherits from `BaseGeometry`. This class should implement methods specific to the rectangle, such as setting dimensions.

### `9-rectangle.py`
- **Task:** Write a class `Rectangle` that inherits from `BaseGeometry` (7-base_geometry.py). (task based on 8-rectangle.py)
- **Description:** Refine the `Rectangle` class further, improving functionality such as initialization and validating inputs.

### `10-square.py`
- **Task:** Write a class `Square` that inherits from `Rectangle` (9-rectangle.py).
- **Description:** Define the `Square` class, inheriting from the `Rectangle` class. This class should ensure that both the width and height are equal.

### `11-square.py`
- **Task:** Write a class `Square` that inherits from `Rectangle` (9-rectangle.py). (task based on 10-square.py)
- **Description:** Refine the `Square` class further to enforce specific behavior or properties unique to squares.