# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(str, n):
    a = ""
    for i in range(len(str)):
        if i != n:
            a += str[i]
    return a
input_string = input()
index_to_remove = int(input())
if 0 <= index_to_remove < len(input_string):
    result = remove(input_string, index_to_remove)
    print(result)
else:
    print("Invalid index.")
```

## Output

![image](https://github.com/user-attachments/assets/67b4573b-7d2a-4ad5-b186-21ca6e6f49f3)


## Result
Thus the program has been executed successfully.
