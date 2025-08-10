# assignment-2-for-python
# week2.py-assignment
Create an empty list called my_list. Append the following elements to my_list: 10, 20, 30, 40. Insert the value 15 at the second position in the list. Extend my_list with another list: [50, 60, 70]. Remove the last element from my_list. Sort my_list in ascending order. Find and print the index of the value 30 in my_list.
"""
README
------
This Python script demonstrates various list operations step-by-step.

Steps performed:
1. Create an empty list named `my_list`.
2. Append the elements 10, 20, 30, and 40 to the list.
3. Insert the value 15 at the second position in the list.
4. Extend the list with another list: [50, 60, 70].
5. Remove the last element from the list.
6. Sort the list in ascending order.
7. Find and print the index of the value 30 in the list.
8. Print the final list to verify the result.

Expected output:
Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]

Author: Your Name
License: MIT
"""

# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend my_list with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element from my_list
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)

# Step 8: Print the final list
print("Final list:", my_list)
