# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:

Start the program and import the required libraries.

Seed the random number generator using the current time(i.e) rand(time(0));

Get the number of randon number to generate.

Pass the value for number of iterations and print the numbers.

End the program.

# PROGRAM:

#### Developed by: ARSHATHA
#### RegisterNumber:  212222230012
``` 
import random

seed_value = int(input("Enter the seed value: "))
num_random_numbers = int(input("Enter how many random numbers to generate: "))

random.seed(seed_value)

print("Random numbers:")
for _ in range(num_random_numbers):
    print(random.randint(1, 4294967295))  

```
# OUTPUT:

![image](https://github.com/user-attachments/assets/040fddcb-c996-407f-830a-d6d043ae3caa)


# RESULT:

The program for Pseudorandom Number Generation using the standard library is executed successfully.

