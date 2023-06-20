

```python
1.Write a Python program to print "Hello Python"?
```


```python
print("Hello Python")
```

    Hello Python
    


```python
2.Write a Python program to do arithmetical operations addition and division.?
```


```python
a = 10
b = 20

print("Addition {}+{} = {}".format(a,b,a+b))
print("Division {}/{} = {}".format(b,a,b/a))
```

    Addition 10+20 = 30
    Division 20/10 = 2.0
    


```python
3.Write a Python program to find the area of a triangle?
```


```python
# Area of triangle = (base*height)/2

b = int(input("Enter base :"))
h = int(input("Enter height :"))

area = (b*h)/2

print("Area of Triangle = ", area)
```

    Enter base :10
    Enter height :20
    Area of Triangle =  100.0
    


```python
4.Write a Python program to swap two variables?
```


```python
a = 10
b = 20

print("Before swaping a = {}, b = {}".format(a,b))
temp = a
a = b
b = temp

print("After swaping a = {}, b = {}".format(a,b))
```

    Before swaping a = 10, b = 20
    After swaping a = 20, b = 10
    


```python
5.Write a Python program to generate a random number?
```


```python
import random

randomNum = random.randint(0,100)
print(randomNum)
```

    83
    
