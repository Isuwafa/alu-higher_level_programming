This project is part of the **ALU Higher Level Programming** curriculum.  
It focuses on learning how to work with **lists** and **tuples** in Python, understanding their similarities and differences, and manipulating data within these structures.

You will practice:
- Accessing and modifying list elements
- Using loops to iterate through lists
- Copying and replacing list elements
- Working with tuples and returning multiple values
- Handling matrices (lists of lists)

All files in this project are Python scripts that demonstrate these concepts.

---

## 🧠 Learning Objectives
By the end of this project, you should be able to explain:
- What lists are and how to use them
- Differences and similarities between strings and lists
- Common list methods and how to use them
- How to use lists as stacks or queues
- What list comprehensions are
- What tuples are and when to use them
- How to use tuples for multiple assignments
- How to return multiple values from a function
- How to work with sequences
- How to use the `del` statement

---

## 🧩 Requirements
- All files will be interpreted/compiled on **Ubuntu 20.04 LTS** using **python3 (version 3.8.5)**
- Your code should follow **pycodestyle** (version 2.7.*)
- All files must be **executable**
- The length of your files will be tested using `wc`
- You are **not allowed to import any module** unless specified

---

## 📂 Project Structure
Repository: `alu-higher_level_programming`  
Directory: `python-data_structures`

| File | Description |
|------|--------------|
| `0-print_list_integer.py` | Prints all integers of a list using `str.format()` |
| `1-element_at.py` | Retrieves an element from a list like in C |
| `2-replace_in_list.py` | Replaces an element of a list at a specific position |
| `3-print_reversed_list_integer.py` | Prints all integers of a list in reverse order |
| `4-new_in_list.py` | Replaces an element in a list without modifying the original |
| `5-no_c.py` | Removes all characters 'c' and 'C' from a string |
| `6-print_matrix_integer.py` | Prints a matrix of integers |
| `7-add_tuple.py` | Adds two tuples and returns a new tuple |
| `8-multiple_returns.py` | Returns a tuple with the length and first character of a string |
| `9-max_integer.py` | Finds the biggest integer in a list |
| `10-divisible_by_2.py` | Finds all multiples of 2 in a list |
| `11-delete_at.py` | Deletes an item at a specific position in a list |
| `12-switch.py` | Switches the value of two variables (`a` and `b`) |

---

## 🚀 How to Run
To execute any of the scripts, make sure they are executable:

```bash
chmod +x filename.py
./filename.py
Or run with Python3:

bash
Copy code
python3 filename.py
🧪 Example
Example for 0-print_list_integer.py:

bash
Copy code
$ cat 0-main.py
#!/usr/bin/python3
print_list_integer = __import__('0-print_list_integer').print_list_integer

my_list = [1, 2, 3, 4, 5]
print_list_integer(my_list)

$ ./0-main.py
1
2
3
4
5
✨ Author
Suwafa Lizaa
Student at African Leadership University (ALU)
Project: Python - Data Structures: Lists, Tuples


