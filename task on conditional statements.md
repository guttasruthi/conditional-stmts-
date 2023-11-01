1)  Write a Python program that asks the user for their age and prints "You are an adult" if the age is 18 or older, otherwise prints "You are a minor'


```python
age= int(input('enter your age:'))

if age<==18:                  # checks if the age is greater than is equal to 18
    print('you are an adult')
elif age<=18:
    print('you are a minor')# prints the statement if the age is above 18
else:
        print('you are not alive') # prints the statement if the age is less than 18

    
```

    enter your age:20
    you are not alive
    

2)  Write a program that takes a numerical grade (out of 100) as input and prints the corresponding letter grade according to the following scale:
 90-100:A
 80-89: B
 70-79: C
 60-69: D
 Below 60: F



```python
num= int(input('enter the grade'))

if num >=90:  # checks if the num is greater than equal to 90
    print('a') # prints the statement if the num is above 90
#checks if the num is greaterthen equal to 80
elif num >=80:
    print('b')
elif  num >=70:
    print('c')
elif num >=60:
    print('d')
else:
    print('f')
```

    enter the grade55
    f
    

3)  Write a program that calculates the Body Mass Index (BMI) of a person. The user should input their weight in kilograms and height in meters. The program should then print whether the person is underweight, normal weight, overweight, or obese



```python
weight = float(input('enter the weight in kilograms:'))
height = float(input('enter the height in meters:'))
bmi = weight/height**2
print (bmi)
if bmi < 18.5:
    print('underweight')
elif 18.5 < bmi <24.5:
    print('normalweight')
elif 24.5 < bmi <29.5:
    print('overweight')
else:
    print('obese')

```

    enter the weight in kilograms:70
    enter the height in meters:1.73
    23.38868655818771
    normalweight
    

4)  Write a program that asks the user for three numbers and prints the maximum of the three


```python
x= float(input('enter the first number:'))
y= float(input('enter the second number:'))
z= float(input('enter the third number:'))
max = max(x,y,z)

if x>y and x>z:
    print('x is maximum')
elif y>x and y>z:
    print('y is maximum')
else:
    print('z is maximum')

```

    enter the first number:10
    enter the second number:20
    enter the third number:30
    z is maximum
    

5)  Write a program that asks the user for a temperature (in Celsius) and prints "It's freezing" if the temperature is below 0, "It's cool" if it's between 0 and 10, "It's warm" if it's between 10 and 20, and "It's hot" if it's above 20



```python
temp = float(input('enter the temperature:' ))

if temp<0:
    print('it\'s freezing') 
elif temp in range(0,10):
     print('it\'s cool') 
elif temp in range(10,20):
     print('it\'s warm')
else:
     print('it\'s hot')              
                   
```

    enter the temperature:35
    it's hot
    

6)  Write a program that asks the user for a number (1-7) and prints the corresponding day of the week.


```python
day = int(input('enter a number:'))

if day==1:
    print('sunday')
elif day==2:
    print('monday')
elif day==3:
    print('tuesday')
elif day==4:
    print('wednesday')
elif day==5:
    print('thursday')
elif day==6:
    print('friday')
elif day==7:
    print('saturday')
else:
    print('invalid number')
```

    enter a number:5
    thursday
    

7)  Write a program that asks the user for a number and prints "In range" if the number is between 10 and 20 (inclusive), and "Out of range" otherwise.


```python
num= int(input('enter the number:'))

if num in range(10,20):
    print('In range')
else:
    print('out of range')
```

    enter the number:15
    In range
    

8)  Write a program that asks the user for an integer and prints whether it's even or odd.


```python
a = int(input('enter the integer:'))

if a%2==0:
    print('it is even')
else:
     print('it is odd')
```

    enter the integer:2
    it is even
    

9)   Write a Python program to add 'ing' at the end of a given string (string length should be equal to or more than 3). If the given string already ends with 'ing' then add 'ly' instead.If the string length of the given string is less than 3, leave it unchanged



```python
str = input('enter the string:')

if len(str)<=3 :
    print('str')
elif str.endswith('ing'):
    print(str.replace('ing' ,'ly'))
else:
     print((str), 'ing')
```

    enter the string:welcome
    welcome ing
    

10) Create rock-paper-scissors by using the if condition


```python
player1 = (input("player-I : "))   #p1 is player1 ,user input
player2= (input("player-II :  "))   #p2 is player2 , user input
if player1==("paper") and player2==("rock"): 
        print("p1 wins")
elif player1==("rock") and player2==("scissors"):
        print("p1 wins")
elif player1==("scissors") and player2==("paper"):
        print("player1 wins")
else:
        print("player2 wins")
```

    player-I : rock
    player-II :  scissors
    p1 wins
    

11)  Create a dynamic calculator which asks for numbers and operator and return the answers,
             Example
    Input: Type first number: 10",
    Type any of this (+, -, *, /, %, **): ,*
    Assignment-2 ,
   Type second number: 19,
    Output:Answer is 190




```python
a=int(input("Enter  a :"))
b=int(input("Enter b :"))
oper =input("Enter Arithmetic operator : ")
if oper=='+':
    print('answer is ' ,a+b)
elif oper=='-':
    print('answer is ',a-b)
elif oper=='*':
    print('answer is ',a*b)
elif oper=='/':
    print('answer is ',a/b)
elif oper=='%':
    print('answer is ',a%b)
elif oper=='**':
    print('answer is ',a**b)
else :
    print("It is not an arithmetic operator")
```

    Enter  a :10
    Enter b :20
    Enter Arithmetic operator : -
    answer is  -10
    

12) Manoj Kumar has family and friends. Help him remind them who is who. Given a string with a name, return the relation of that person to Manoj Kumar.,
 Person Relation,
 Shiva father ,Letha mother, Tarun brother,Kavitha sister ,,Strange Coder.



```python
# assigning values
a,b,c,d= 'shiva','letha', 'tarun', 'kavitha'
# giving input
x=str(input('enter the name'))
# checking condition
if x==a:
    print('enter the father name')
elif x==b:
    print('enter the mother name')
elif x==c:
    print('enter the brother name')
elif x==d:
    print('enter the sister name')
else:
    print('strange coder')
    
    



          
                




```

    enter the nameletha
    enter the mother name
    

13) Write a python program that takes in a word and determines whether or not it is plural. A plural word is one that ends with “s”


```python
# assigning input
program= str(input('enter the word'))
# checking condition
if program.endswith("s"):
    print('a word is plural')
else:
    print('a word is not plural')

```

    enter the wordpythons
    a word is plural
    

14) A company decided to give a bonus of 5% to employees if his/her year of service is more than 5 years.Ask user for their salary and year of service and print the net bonus amount


```python

```

15) Take values of length and breadth of a rectangle from the user and check if it is square or not.


```python
# assigning inputs
len = float(input('enter the rectangle:'))
breadth = float(input('enter the rectangle:'))
# checking condition
if len == breadth:
    print('it is a square')
else:
    print('it is not a square')

```

    enter the rectangle:10
    enter the rectangle:10
    it is a square
    


```python
len = float(input('enter the rectangle:'))
breadth = float(input('enter the rectangle:'))
if len == breadth:
    print('it is a square')
else:
    print('it is not a square')
```

    enter the rectangle:20
    enter the rectangle:30
    it is not a square
    

16) Accept any city from the user and display the momentum of the city 
Hyderabad  : “charminar”
“Delhi”         : “red fort
“Agra           : Taj mahal
If the city name is not given correctly, give him a warning message



```python
city = int(input('enter the city name:'))

```

17) Write a program to check whether a person is eligible for voting or not  (voting age>=18).


```python
age = int(input('enter the age:'))
# checks the condition age from 18 to 100
if age in range (18,100):
# if the condition is true it prints     
    print('eligible for voting')  
# otherwise it prints    
else:
    print('not eligible for voting')
```

    enter the age:17
    not eligible for voting
    


```python
age = int(input('enter the age:'))
# checks the condition age from 18 to 100
if age in range (18,100):
# if the condition is true it prints     
    print('eligible for voting')  
# otherwise it prints    
else:
    print('not eligible for voting')
```

    enter the age:20
    eligible for voting
    

18) Accept three sides of the triangle and check whether the triangle is possible or not.(Triangle is possible only when the sum of any two sides is greater than 3 rd side).


```python
#giving inputs
side1= float(input('enter the first side:'))
side2= float(input('enter the second side:'))
side3= float(input('enter the third side:'))
# checking condition
if side1+side2>side3 and side1+side3>side2 and side2+side3>side1:
    print('the triangle is possible')
else:
    print('the triangle is not possible')
  
```

    enter the first side:12
    enter the second side:12
    enter the third side:15
    the triangle is possible
    


```python
# assigning inputs
side1= float(input('enter the first side:'))  
side2= float(input('enter the second side:'))
side3= float(input('enter the third side:'))
#checking condition
if side1+side2>side3 and side1+side3>side2 and side2+side3>side1:
    print('the triangle is possible')
else:
    print('the triangle is not possible')
```

    enter the first side:20
    enter the second side:10
    enter the third side:55
    the triangle is not possible
    


```python

```
