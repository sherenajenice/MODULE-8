# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **counts the number of vowels and consonants** from the given string.

---

## 🎯 Aim

To **count the number of vowels and consonants** from the given string.

---

## 🧠 Algorithm

1. Start
2. Input a string s.
3. Convert the string to lowercase (to handle both uppercase and lowercase letters).
4. Initialize two counters: vowel_count = 0, consonant_count = 0.
5. Define the set of vowels → {A, E, I, O, U, a, e, i, o, u}.
6. For each character ch in the string: If ch is an alphabet: If ch is in vowels, increment vowel_count. Else, increment consonant_count.
7. Display vowel_count and consonant_count.
8. Stop

---


## 🧪 Program
def fun(s):

v,c=0,0

for i in s:
 
    if i in ['A','E','I','O','U','a','e','i','o','u']:
    
        v+=1
    
    else:
    
        c+=1

print("Number of Vowels:",v)

print("Number of Consonants:",c)

s=input()

## Sample Output
![WhatsApp Image 2025-09-15 at 14 41 03_e5b817bf](https://github.com/user-attachments/assets/1cf8ed22-3bed-410b-b6fa-ce3bcffe4b84)

## Result
The program was succesful.
