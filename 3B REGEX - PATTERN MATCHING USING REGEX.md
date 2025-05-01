# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
Write a Python program that matches a string that has an a followed by two to three 'b'.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

import re

def text_match(text):

    patterns = 'ab{2,3}?'
    
    if re.search(patterns, text):
    
        return 'Found a match!'
        
    else:
    
        return 'Not matched!'
        
x=input()
print(text_match(x))
```
```
### OUTPUT
![image](https://github.com/user-attachments/assets/075792cb-0542-43e8-9276-72aad9c7ba08)


### RESULT
Thus the program is executed successfully
