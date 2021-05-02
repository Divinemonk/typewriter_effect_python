# Typewriter / Typing Effect - in Python

### H3Y ! Let's create a effect in python to print sectences like someone is actually typing !!

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

---

<br> 

## Explaination !!
> For people who want to learn & understand what is happening in the code !
