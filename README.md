Akshaya Sree G
212225230011
# 1.Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
 def mech(self,r):
  print(3.14*r*r)
r=float(input())
x=cse()
x.mech(r)
```
## Output
<img width="352" height="597" alt="image" src="https://github.com/user-attachments/assets/c8271b26-65bf-4d27-9e04-1d1d80e67d32" />

## 2.Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1={'a':1,'b':2}
dict2={'c':3,'d':4}
def merge():
 print({**dict1,**dict2})
merge()
```
## Output
<img width="371" height="361" alt="image" src="https://github.com/user-attachments/assets/f25238d7-7464-467f-abad-b1b4f237054a" />

## Result
Thus to write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is implemented.

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

# 4.Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1=[1,2,3]
try:
 print(list1[5])
except IndexError:
 print("You're out of list range")
```
## Output
<img width="508" height="355" alt="image" src="https://github.com/user-attachments/assets/5f050f9b-b857-417b-b596-b7508d5dee90" />

## Result
Thus to write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is implemented.

# 5.File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
f=open("story.txt","r")
count=0
for i in f:
 if i[0]!='T':
  count=count+1
print(count)
f.close()
```

## Output
<img width="413" height="358" alt="image" src="https://github.com/user-attachments/assets/690ee636-462c-4402-984d-c7904bee096d" />

## Result
Thus to write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` is implemented.
