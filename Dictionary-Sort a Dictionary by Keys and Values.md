# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~c
my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'cherry': 'dark red',
    'blueberry': 'blue'
}
sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Original Dictionary:")
print(my_dict)
print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)
print("\nDictionary Sorted by Values:")
print(sorted_by_values)
~~~

## Sample Output
![Screenshot 2025-05-11 121912](https://github.com/user-attachments/assets/dd21a240-bb09-4e3e-b45c-742df8eb321a)


## Result
Thus , the program has been executed successfully.

