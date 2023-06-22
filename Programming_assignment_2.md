
1.	Write a Python program to convert kilometers to miles?


```python
kilometers = float(input("Enter kilometers :"))
conversionUnit = 0.621
miles = kilometers * conversionUnit
print("%0.3f kilometers is equal to %0.3f miles"%(kilometers,miles))
```

    Enter kilometers :30
    30.000 kilometers is equal to 18.630 miles
    

2.	Write a Python program to convert Celsius to Fahrenheit?


```python
# Fahrenheit = celsius *(9/5) + 32

celsius = float(input("Celsius : "))
fahrenheit = 9/5 * celsius + 32
print("%0.2f celsius is %0.2f fahrenheit"%(celsius,fahrenheit))
```

    Celsius : 20
    20.00 celsius is 68.00 fahrenheit
    

3.	Write a Python program to display calendar?


```python
import calendar

y = int(input(" Enter Year : "))
m = int(input("Enter Month : "))

try :
    print("Calendar")
    print(calendar.month(y,m))
except:
    print("Out of range")
```

     Enter Year : 2000
    Enter Month : 3
    Calendar
         March 2000
    Mo Tu We Th Fr Sa Su
           1  2  3  4  5
     6  7  8  9 10 11 12
    13 14 15 16 17 18 19
    20 21 22 23 24 25 26
    27 28 29 30 31
    
    

4.	Write a Python program to solve quadratic equation?
- quadratic equation 2x**2 + bx + c
- descriminant = b**2 - (4* a * c)
- x = (-b-sqrt(d))/2 , x = (b-sqrt(d))/2


```python
import math
a = 1
b = 4
c = 1

d = b**2 - (4*a*c)
print("Descriminant : ",d)

sol1 = (-b - math.sqrt(d))/(2*a)
sol2 = b - (math.sqrt(d))/(2*a)

print("Sol1 : ",sol1)
print("Sol2 : ",sol2)
```

    Descriminant :  12
    Sol1 :  -3.732050807568877
    Sol2 :  2.267949192431123
    

5.	Write a Python program to swap two variables without temp variable?


```python
x = int(input("Num1 : "))
y = int(input("Num2 : "))
print("Before swaping x = {}, y = {}".format(x,y))
#swapping
y,x = x,y
print("After swaping x = {}, y = {}".format(x,y))
```

    Num1 : 1
    Num2 : 2
    Before swaping x = 1, y = 2
    After swaping x = 2, y = 1
    
