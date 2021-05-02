# Typewriter / Typing Effect - in Python

### Let's create a program in python to print sectences like someone is actually typing !!

<br>

## Code 

```
1.	import sys, time
2.
3.	def typing(text):
4.		for character in text:
5.			sys.stdout.write(character)
6.			sys.stdout.flush()
7.			time.sleep(0.05)
8.
9.	typing("Hello _ World !!")
```

<br> 

---

<br> 

## Explaination !!
> For people who want to learn & understand what is happening in the code , here is line by line explaination !

<br>

### In the first line of code we are importing some packages that we need to create typing effect.
```
1.	import sys, time
```
[+] More about : [import]() , [sys]() , [time]()

---

### Now on third line we are creating a function , named 'typing' and passing argument 'text'.
