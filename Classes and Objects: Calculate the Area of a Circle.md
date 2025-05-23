# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
~~~c
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        return area
circle = cse()
try:
    r = float(input("Enter the radius of the circle: "))
    result = circle.mech(r)
    print(f"The area of the circle with radius {r} is {result:.2f}")
except ValueError:
    print("Please enter a valid number for radius.")
~~~

## Output
![Screenshot 2025-05-11 121226](https://github.com/user-attachments/assets/2375c626-8d14-4f5a-91a9-ca135db1596d)


## Result
Thus,the program has been executed successfully.
