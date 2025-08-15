```python
p=int(input("enter the principal amount"))
r=int(input("enter the rate of interest"))
t=int(input("enter the period(in years)"))
SI=(p*r*t)/100
print("simple interest =",SI)
```

    enter the principal amount 2000
    enter the rate of interest 3
    enter the period(in years) 2
    

    simple interest = 120.0
    


```python
a=int(input("enter a number"))
if a<0:
    print("the number is negative.")
elif a>0:
    print("the number is positive.")
else:
    print("the number is zero.")
```

    enter a number -44
    

    the number is negative.
    


```python
n=int(input("enter a number:"))
k=int(input("enter another number:"))
print("the reminder is",n%k)
```

    enter a number: 20
    enter another number: 3
    

    the reminder is 2
    


```python
s = 120
v = 20
print("before swap s,v =",s,v)
temp = s
s = v
v = temp
print("After swap s,v = ",s,v)
```

    before swap s,v = 120 20
    After swap s,v =  20 120
    


```python
s=int(input("enter a number:"))
if s%2==0:
    print("the number is even.")
else:
    print("the number is odd.")
```

    enter a number: 4
    

    the number is even.
    
