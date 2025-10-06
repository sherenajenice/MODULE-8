# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

n = int(input())

arr = list(map(int, input().split()))

arr.sort()

large=arr[-1]

arr.reverse()

for i in range(len(arr)-1):

if arr[i+1]<arr[i]:
  
    print(arr[i+1])

    break

## OUTPUT
![WhatsApp Image 2025-09-15 at 14 28 58_db35a0b0](https://github.com/user-attachments/assets/bd7dce3b-efb2-46df-9166-b3ceaae50d7e)

## RESULT
Thus the program is excuted and verified.
