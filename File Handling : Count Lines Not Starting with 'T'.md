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
