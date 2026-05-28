# 🔤 3.Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

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


## 🧪Program
```
d={'b':'banana','a':'apple','c':'cat'}
print(d)
print(dict(sorted(d.items())))
print(dict(sorted(d.items(),key=lambda item:item[1])))
```

## Sample Output
<img width="625" height="411" alt="image" src="https://github.com/user-attachments/assets/caf68e23-90f5-4a07-9ee4-561b8c5582d9" />

## Result
Thus to write a Python program that sorts a dictionary's is implemented.
