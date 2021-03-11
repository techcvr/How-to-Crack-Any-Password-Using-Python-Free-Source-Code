# How-to-Crack-Any-Password-Using-Python-Free-Source-Code


<p>Today we will see a basic program which is basically a hint to&nbsp;brute force attack&nbsp;to crack passwords. In other words, we will make a program to&nbsp;<strong>Crack Any Password Using Python</strong></p>

<p>So, we will use&nbsp;brute force&nbsp;attack with the help of while loop.</p>

<p>Now, If you don't know about brute force?</p>

<p>Brute force&nbsp;is defined as an attack to crack passwords where we submit many passwords guessing that any of the passwords which we are submitting may work.</p>

```python
# importing random
from random import *

# taking input from user
user_pass = input("Enter your password")

# storing alphabet letter to use thm to crack password
password = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j','k', 'l',
'm', 'n', 'o', 'p', 'q', 'r', 's', 't','u','v', 'w', 'x', 'y', 'z',]

# initializing an empty string
guess = ""

# using while loop to generate many passwords untill one of them does not matches user_pass
while (guess != user_pass):
  guess = ""
  for letter in range(len(user_pass)):
  guess_letter = password[randint(0, 25)]
  guess = str(guess_letter) + str(guess)
  print(guess)
    
# printing the matched password
print("Your password is",guess)
```

## Connect With Me
Telegram - https://t.me/techcvr <br>
Discord - https://discord.gg/bcH8nGU <br>
YouTube - https://www.youtube.com/techcvr <br>
Instagram - https://www.instagram.com/vishalgaire/
