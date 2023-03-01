# math
import math
x = int(input("Enter a number: "))
y = int(input("Enter a number: "))
ax = math.gcd(x, y)
print(f"The greatest common divisor of  {x} and {y} is {ax}.")

from math import gcd
x = int(input("Enter a number: "))
y = int(input("Enter a number: "))
ax = gcd(x, y)
print(f"The greatest common divisor of  {x} and {y} is {ax}.")
