## Write a python function "convert" to accept a string and converts the alphabets into "#" , numbers with "A", symbols with "5"


#Aim 
```
 To Write a python function "convert" to accept a string and converts the alphabets into "#" , numbers with "A", symbols with "5"


```
#algorithm.
```
1. Start.
2. Input `a` string `s`.
3. Loop through each character: convert alphabets to `#`, digits to `A`, and symbols to `5`.
4. Output the modified string
```
##program
```
def convert(num):
    
    result = ''
    for i in num:
        if i.isalpha():
            result+='#'
        elif i.isnumeric():
            result+="A"
        else:
            result += "5"
    print(result)    

   
```

#output
![image](https://github.com/user-attachments/assets/25650a98-2b82-4a3c-ad7f-800dccc81234)


#result
```
The expected output is Achieved.
```
