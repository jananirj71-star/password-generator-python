📝 Objective
The objective of this project is to develop a simple Calculator Application using Python that helps users perform basic arithmetic operations like addition, subtraction, multiplication, and division efficiently using a command-line interface.

✨ code

# Password Generator

import random
import string

# Get password length from user
length = int(input("Enter password length: "))

# All possible characters
characters = string.ascii_letters + string.digits + string.punctuation

# Generate password
password = ""

for i in range(length):
    password += random.choice(characters)

# Display password
print("Generated Password:", password)
print("Password Length:", length)
