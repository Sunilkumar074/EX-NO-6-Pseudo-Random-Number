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
~~~
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  # randint to mimic C's rand() range
if __name__ == "__main__":
    main()
~~~
# OUTPUT:
<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/7edeaae6-b279-46b9-9f32-bf1d859596c5" />

# RESULT:
the above program is executed in Implementation of Pseudorandom Number Generation Using Standard library
