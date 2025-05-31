# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
      if n == 0:
          return
      fun(n - 2) 
      print(n, end=' ')  

  num = int(input())
  if num % 2 != 0:
      num += 1
  fun(num)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/403e0d31-a6f1-4963-9711-f53c5f92e414)

## RESULT
Thus, the program has been execueted successfully.
