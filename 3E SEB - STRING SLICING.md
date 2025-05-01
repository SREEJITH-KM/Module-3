# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
Write a python program to create the tuple by the multiples of 9 up to N and the print length of the tuple. Get the N value from the user.
---

### ALGORITHM
Start

Prompt the user to enter a positive integer N

Initialize an empty list to store the multiples of 9

Use a loop (e.g., for i in range(9, N+1, 9)) to generate multiples of 9 up to N

Append each multiple to the list

Convert the list to a tuple

Print the tuple and its length

End
---

### PROGRAM

```
n=int(input())

L=list(range(9,n,9))

print(tuple(L))

print("Length of the tuple is",len(L))

```

### OUTPUT
![image](https://github.com/user-attachments/assets/5465d20d-bf9b-4400-a14b-c174fdfe38b1)


### RESULT
Thus the program is executed successfully
