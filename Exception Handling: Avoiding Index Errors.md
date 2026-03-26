# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
Add code here
```
try:
    a = []
    n = int(input())
    for i in range(n):
        b=int(input())
        a.append(b)
    print(a)
    print(a[10])
  

except IndexError:
   
    print("10 is not accepted")
```
## Output
<img width="1147" height="310" alt="image" src="https://github.com/user-attachments/assets/babbd231-06c0-4dd7-b20d-454785fca477" />

## Result

Thus the a Python program that handles an IndexError is executed successfully.
