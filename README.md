# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```

## Output
<img width="271" height="159" alt="517428550-bf8ca470-93b1-4014-ac4e-a988b7b95d0d" src="https://github.com/user-attachments/assets/440cdbce-81d5-40c7-94ea-7d871cd855df" />

## Result
Thus the program executed successfully.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```
## Output
<img width="527" height="178" alt="517429032-7868b775-0061-429f-8c1c-d96ebe4a7a6d" src="https://github.com/user-attachments/assets/83789f2b-6760-48e1-b547-cddb8d564e94" />

## Result
Thus the program executed successfully.
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
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output
<img width="634" height="189" alt="517433779-1a10c8ee-fa46-4f73-8b8e-f2eb3d490fa4" src="https://github.com/user-attachments/assets/cbe6600e-5369-48f2-9661-c074abaad1cd" />

 ## Result
Thus the program executed successfully.# Module-3
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
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output
<img width="634" height="189" alt="517433779-1a10c8ee-fa46-4f73-8b8e-f2eb3d490fa4" src="https://github.com/user-attachments/assets/cbe6600e-5369-48f2-9661-c074abaad1cd" />

 ## Result
Thus the program executed successfully.
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
```
## Output
<img width="767" height="231" alt="517434702-7ba9c2ac-01a0-44d2-a793-4f6caee9301b" src="https://github.com/user-attachments/assets/b662aebf-531e-4554-9a34-3cf17eb1dd5c" />

## Result
Thus the program executed successfully.
