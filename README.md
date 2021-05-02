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

### In the first line of code we are importing 'sys' (abbreviation of 'system') & 'time' packages.
```
1.	import sys, time
```
[+] More about : [import](https://www.google.com/search?q=python+import&client=firefox-b-d&sxsrf=ALeKk00pNa9YBhDCqEtnyvcZxd5dClaHXw%3A1619953862216&ei=xoiOYKbbDOmF1fAPoYmTyAk&oq=python+import&gs_lcp=Cgdnd3Mtd2l6EAMyBwgjELADECcyBwgjELADECcyFAgAELADEIoDELcDENQDEOUCEIsDMhQIABCwAxCKAxC3AxDUAxDlAhCLAzIUCAAQsAMQigMQtwMQ1AMQ5QIQiwMyFAgAELADEIoDELcDENQDEOUCEIsDMhQIABCwAxCKAxC3AxDUAxDlAhCLAzIUCAAQsAMQigMQtwMQ1AMQ5QIQiwMyFAgAELADEIoDELcDENQDEOUCEIsDMhQIABCwAxCKAxC3AxDUAxDlAhCLA1AAWABg1BZoAXACeACAAfQDiAH0A5IBAzUtMZgBAKoBB2d3cy13aXrIAQq4AQHAAQE&sclient=gws-wiz&ved=0ahUKEwim1om07qrwAhXpQhUIHaHEBJkQ4dUDCA0&uact=5) , [sys](https://www.google.com/search?q=python+import+sys&client=firefox-b-d&sxsrf=ALeKk02mPZ94a1Avrktd9KLAuuYKCYXMJw%3A1619953912263&ei=-IiOYLy8D-XUxgPJyq-4DQ&oq=python+import+sys&gs_lcp=Cgdnd3Mtd2l6EAMyBwgAEIcCEBQyAggAMgIIADIGCAAQBxAeMgYIABAHEB4yAggAMgIIADICCAAyAggAMgIIADoUCAAQsAMQigMQtwMQ1AMQ5QIQiwM6EQgAELADEIoDELcDEOUCEIsDUMQsWJA1YKhGaAFwAngAgAHYBIgB2B2SAQU0LTQuNJgBAKABAaoBB2d3cy13aXrIAQq4AQLAAQE&sclient=gws-wiz&ved=0ahUKEwi8mPjL7qrwAhVlqnEKHUnlC9cQ4dUDCA0&uact=5) , [time](https://www.google.com/search?q=python+import+time&client=firefox-b-d&sxsrf=ALeKk02Yh6vcMC7eX-_t7zFST1O1cyb42g%3A1619953923164&ei=A4mOYIGeCaGj1fAP8qOyuAI&oq=python+import+time&gs_lcp=Cgdnd3Mtd2l6EAMyBwgAEIcCEBQyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAMgoIABCHAhDJAxAUMgIIADoUCAAQsAMQigMQtwMQ1AMQ5QIQiwM6EQgAELADEIoDELcDEOUCEIsDUNR6WLyCAWCYjgFoAXACeACAAdgEiAGoFJIBAzUtNZgBAKABAaoBB2d3cy13aXrIAQq4AQLAAQE&sclient=gws-wiz&ved=0ahUKEwjBq5HR7qrwAhWhURUIHfKRDCcQ4dUDCA0&uact=5)

<br>

### Now on third line we are creating a function , named 'typing' and passing argument 'text' in it.
```
3.	def typing(text):
```
[+] More about : [def](https://www.google.com/search?q=python+functions&client=firefox-b-d&sxsrf=ALeKk0109_gX3dtN4oJy_1_vL4-N0zrXYQ%3A1619953969917&ei=MYmOYOrJN-KF1fAPpamgwAc&oq=python+functions&gs_lcp=Cgdnd3Mtd2l6EAMyCggAEIcCELEDEBQyBwgAEIcCEBQyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAMgIIAFD8EVj8EWDYHWgAcAJ4AYABoAaIAewOkgEFNS0yLjGYAQCgAQGqAQdnd3Mtd2l6wAEB&sclient=gws-wiz&ved=0ahUKEwiqprfn7qrwAhXiQhUIHaUUCHgQ4dUDCA0&uact=5)

<br>

### Next , we are using for loop. This will pass one string to print at a time .
```
4.		for character in text:
```
[+] More about : [for loop](https://www.google.com/search?q=python+for+loop&client=firefox-b-d&sxsrf=ALeKk03Q5F7VTeN0faWDDpiP-mp3QZlknQ%3A1619953975882&ei=N4mOYMuvNd3P1fAP0ZGN2AE&oq=python+for+loop&gs_lcp=Cgdnd3Mtd2l6EAMyCAgAELEDEJECMgIIADICCAAyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAOhEIABCwAxCKAxC3AxDUAxDlAjoUCAAQsAMQigMQtwMQ1AMQ5QIQiwM6EQgAELADEIoDELcDEOUCEIsDOgUIABCRAjoFCAAQsQM6AgguOgUILhCxA1DweVjYgQFghIQBaAFwAngAgAG8BYgBrBuSAQc0LTIuNC4xmAEAoAEBqgEHZ3dzLXdpesgBCrgBAsABAQ&sclient=gws-wiz&ved=0ahUKEwiLp6Pq7qrwAhXdZxUIHdFIAxsQ4dUDCA0&uact=5)

<br>

###
