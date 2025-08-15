```python
p=float(input("enter the principal amount"))
r=float(input("enter the rate of interest"))
t=float(input("enter the period(in years)"))
SI=(p*r*t)/100
print("simple interest =",SI)
```

    enter the principal amount 2000.5
    enter the rate of interest 22
    enter the period(in years) 3
    

    simple interest = 1320.33
    


```python
a=float(input("enter a number"))
if a<0:
    print("the number is negative.")
elif a>0:
    print("the number is positive.")
else:
    print("the number is zero.")
```

    enter a number 3.3
    

    the number is positive.
    


```python
n=int(input("enter the dividend:"))
k=int(input("enter the divisor:"))
print("the reminder is",n%k)
```

    enter the dividend: 20
    enter the divisor: 3
    

    the reminder is 2
    


```python
s=input("enter the first variable:")
v=input("enter the second variable:")
print("before swap :",s,v)
temp=s
s=v
v=temp
print("After swap: ",s,v)
```

    enter the first variable: 2
    enter the second variable: 4
    

    before swap : 2 4
    After swap:  4 2
    


```python
s=int(input("enter a number:"))
if s%2==0:
    print("the number is even.")
else:
    print("the number is odd.")
```

    enter a number: 4
    

    the number is even.
    
