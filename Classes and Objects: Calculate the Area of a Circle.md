# Classes and Objects in Python: Calculate the Area of a Circle

##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")
r = float(input())
obj = cse()
obj.mech(r)

```

## Output

<img width="672" height="198" alt="517999439-a65ecfb9-7981-43b0-8df4-76affe7dcb18" src="https://github.com/user-attachments/assets/2e1b1cee-1ef7-4f92-91a0-f67e8a5104d9" />


## Result
Thus the program executed successfully.

