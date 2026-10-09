# A-simple-Python-project-demonstrating-the-difference-between-immutable-strings-and-mutable-lists.
It explains how strings cannot be modified in place, while lists allow elements to be updated and new items to be added using list operations. 
# Immutable Strings and Mutable Lists in Python

## Description
This project demonstrates the difference between immutable strings and mutable lists in Python. It shows how strings cannot be changed after creation, while lists can be modified by updating elements and adding new items.

## Code Example

```python
name = "London"

module = ["java", "database", "networks"]
module[0] = "python"
module.append("web development")

print(module)
```

## Output

```text
['python', 'database', 'networks', 'web development']
```

## Key Concepts

### 1. Immutable Strings
A string is immutable in Python, which means its characters cannot be changed in place after the string has been created.

For example:

```python
name = "London"
# name[0] = "M"  # This would raise a TypeError
```

You can assign a new string to the variable, but you cannot modify the existing string itself.

### 2. Mutable Lists
A list is mutable, which means its contents can be changed after creation.

In this example:
- `module[0] = "python"` replaces `"java"` with `"python"`.
- `module.append("web development")` adds a new item to the end of the list.
- `print(module)` displays the updated list.

## Conclusion
Python strings are immutable, whereas lists are mutable. Understanding this difference helps you work with Python data types effectively.

## Technologies Used
- Python 3
