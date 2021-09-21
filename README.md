# Typewriter / Typing Effect - in Python

### Let's create a program in python to print sentences like someone is actually typing !!

<br>

## Code 

```
import sys, time

def typing(text):
    for character in text:
      sys.stdout.write(character)
			sys.stdout.flush()
			time.sleep(0.05)

typing("Hello _ World !!")
```

<br>

## Run this code online : [Python Editor](https://www.online-python.com/1Sq2ny9WcD)

<br> 

---

<br> 

## Explaination !!
> For people who want to learn & understand what is happening in the code , here is line by line explaination !

<br>

### In the first line of code we are importing 'sys' (abbreviation of 'system') & 'time' packages.
```
1. import sys, time
```
[+] More about : [import](https://bit.ly/3udwI3Y) , [sys](https://bit.ly/3eLiX5T) , [time](https://bit.ly/3xFZD2J)

<br>

### Now on third line we are creating a function , named 'typing' and passing argument 'text' in it.
```
3. def typing(text):
```
[+] More about : [def](https://bit.ly/2PJAxyQ)

<br>

### Next , we are using for loop. This will pass one string to print at a time .
```
4. for character in text:
```
[+] More about : [for loop](https://bit.ly/2QLuiec)

<br>

### Next two lines (5 & 6) our program prints given string , one by one .
```
5. sys.stdout.write(character)
6. sys.stdout.flush()
````
[+] More about : [sys.stdout.write()](https://bit.ly/3ePKiDV) , [sys.stdout.flush()](https://bit.ly/2PJAz9W)

<br>

###  Set the time to print each string . You can change the time within brackets as want.
```
7. time.sleep(0.05)
```
[+] More about : [time.sleep()](https://bit.ly/3ecKeis)

<br>

### Here we are calling the function 'typing()' , and giving argument 'Hello _ World !!' 
```
9. typing("Hello _ World !!")
```
[+] More about : [calling function](https://bit.ly/3nDsVdN)
