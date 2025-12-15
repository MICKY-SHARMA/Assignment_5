
# 📘 Python List Operations Program

## 📌 Description

This Python program demonstrates basic list operations such as:

* Creating a list of numbers
* Extracting elements using slicing
* Reversing a list
* Printing multiple lists

## 🧾 Program Features

1. Creates a list of numbers from **1 to 10**
2. Extracts the **first five elements**
3. Reverses the extracted elements
4. Prints:

   * Original list
   * Extracted list
   * Reversed list

## 🧑‍💻 Python Code

```python
# Step 1: Create a list of numbers from 1 to 10
numbers = list(range(1, 11))

# Step 2: Extract the first five elements
first_five = numbers[:5]

# Step 3: Reverse the extracted elements
reversed_list = first_five[::-1]

# Step 4: Print all lists
print("Original list:", numbers)
print("Extracted list:", first_five)
print("Reversed list:", reversed_list)

## ▶️ Sample Output

```
Original list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted list: [1, 2, 3, 4, 5]
Reversed list: [5, 4, 3, 2, 1]
```

## 📚 Concepts Used

* Lists
* List slicing
* Reverse slicing
* `range()` function
* Print statements
