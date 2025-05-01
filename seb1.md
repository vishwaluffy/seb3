## Write a Python program to find sequences of lowercase letters joined with a underscore.

#Aim 
```
To Write a Python program to find sequences of lowercase letters joined with a underscore.
```
#algorithm.
```
1. Start.
2. Input a string from the user.
3. Use regex to find pattern: lowercase letters + underscore + lowercase letters.
4. Output all matching sequences


```
##program
```
import re

num = input()

pattern=r'^[a-z]+_[a-z]+$'

if re.match(pattern,num):
    print("Found a match!")
else:
    print("Not matched!")    
```

#output
![image](https://github.com/user-attachments/assets/9978c9a9-dd97-4978-898f-a618ac434513)




#result
```
The expected output is Achieved.
```
