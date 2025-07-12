# 📘 Day 3 Notes – Lists & Tuples in Python

---

## 🔹 Lists in Python

### ✅ What is a List?
- Ordered collection of items
- Mutable (can be changed)
- Can contain different data types

### ✨ Creating a List
```python
marks = [94.4, 87.5, 95.2, 66.4, 45.1]

## List operations:
1.Accessing elements:
student = ["Atharv", "Omkar", "Rohit"]
print(student[0])  # Atharv.

2.Lists mutability:
mix_list = ["karan", 96.8, 17, "delhi"]
mix_list[3] = "google"

3.Slicing:
marks = [10, 20, 30, 40, 50]
print(marks[1:4])  # [20, 30, 40]
print(marks[-3:-1])  # Negative indexing.

4.Append vs Extend:
x.append([4,5])     # Adds [4,5] as one element
a.extend([4,5])     # Adds 4 and 5 separately.

5.Remove/Insert/Pop:
web.insert(4, "fullstack")
python.remove("strings")
table.pop(5)

6.Sorting:
devices.sort()
devices.sort(reverse=True)

7.Reverse:
program.reverse()

💻Tuples in Python

✅ What is a Tuple?

Ordered

Immutable (cannot change)

Uses parentheses ()


✨ Creating a Tuple

my_tuple = (10, 20, 30, 40, 50, 60)


---

🔸 Tuple Operations

Slicing

print(my_tuple[1:5])
print(my_tuple[::-1])
print(my_tuple[::2])

Tuple Methods

tup.index(2)
tup.count(1)

Tuple Arithmetic

a + b  # Concatenation
a * 3  # Repetition


---

🧠 Summary

Lists = Mutable

Tuples = Immutable

Use .append(), .extend(), .sort() with lists

Tuples are faster and safer when data should not change
