# File Handling in Python: Count Lines Not Starting with 'T'

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
Add code here
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def find_and_replace(file_path, old_word, new_word):
    with open(file_path,'r')as f:
        cr=f.read()
        l=cr.replace(old_word,new_word)
    with open(file_path,'w') as f:
        f.write(l)


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
```

## Output
<img width="1176" height="616" alt="image" src="https://github.com/user-attachments/assets/83e21c89-b743-4174-bf21-40a24f8361cb" />

## Result

Thus the Python function to find and replace a word in a file is executed successfully.
