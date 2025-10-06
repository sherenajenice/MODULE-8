# 🎓 Hackerrank:Python Program to Find the Simple Interest

This program reads the Principal amount, Rate of interest and Time and calculates the Simple Interest.

---

## 🎯 Aim

To write a Python program to:
- Read Principal amount, Rate of interest and Time.
- Calculate the Simple Interest.

---

## 🧠 Algorithm

1. Start
2. Input the Principal amount P from the user.
3. Input the Rate of interest R (per annum) from the user.
4. Input the Time T in months from the user.
5. Convert Time into years:
      Tyear=T/12
6. Apply the formula for Simple Interest:
      SI=PRTyear/100
7. Display the value of SI.
8. Stop

---

## 💻  Program

p=int(input())

t=float(input())

r=eval(input())

def simpleInterest(p,t,r):

    si = (p*t*r)/100
   
    return si

## Output
<img width="1117" height="290" alt="image" src="https://github.com/user-attachments/assets/cda51d27-bdc8-483e-8663-eea846500334" />
 
## Result
The program was succesful.

