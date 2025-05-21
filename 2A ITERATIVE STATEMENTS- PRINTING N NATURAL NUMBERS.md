# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To create a Python program for printing `n` natural numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```
#Reg.NO: 212224230289
#Name: THARUN R

r=int(input())
for a in range(2,r+1):
    k=0
    for i in range(2,a//2+1):
        if(a%i==0):
            k=k+1
    if(k<=0):
        print(a)


```
### OUTPUT
![image](https://github.com/user-attachments/assets/b29de33e-9cbb-49f2-a866-a05d45ac4b76)


### RESULT

Thus the Python program for printing all prime numbers within a given range was syccessfully created.
