# Lab_assignment1
Program 1::
find the smallest of three numbers 121910314029_01

n1=int(input("Enter the first number"));
n2=int(input("Enter the second number"));
n3=int(input("Enter the Third number"));

if(n1<n2)and(n1<n3):
    s_num=n1;
elif(n2<n1)and(n2<n3):
    s_num=n2;
else:
    s_num=n3;

print("the smallest of the 3 numbers is",s_num);

Output:::
Enter the first number23

Enter the second number3

Enter the Third number19
the smallest of the 3 numbers is 3


Program 2::
LCM of two numbers 121910314029_02


def lcm(x, y):  
   if x > y:  
       greater = x  
   else:  
       greater = y  
  while(True):  
       if((greater % x == 0) and (greater % y == 0)):  
           lcm = greater  
           break  
       greater += 1  
   return lcm  
  
  
num1 = int(input("Enter first number: "))  
num2 = int(input("Enter second number: "))  
print("The LCM of", num1,"and", num2,"is", lcm(num1, num2))  


Output::
Enter first number: 3
Enter second number:4
The LCM of 3 and 4 is 12

Program 3::
Find the gcd of two numbers 121910314029_03

def compute_gcd(x, y): 
if x > y: 
smaller = y 
else:
smaller = x 
for i in range(1, smaller+1):
        if((x % i == 0) and (y % i == 0)):
            hcf = i 
    return gcd
    
x= int(input("Enter first number: "))  
y = int(input("Enter second number: "))  
 print("The GCD is", compute_hcf(num1, num2))
 
 Enter first number: 54
 Enter second number:24
 The GCD is 6
 
 
 Program 4::
 find the LCM and GCD of two numbers 121910314029_04


import math
def lcm_gcd(x,y,z):
    gcd2=math.gcd(y,z)
    gcd3=math.gcd(x.gcd2)
    print("the gcd of the three numbers is",gcd3)
    lcm2=y*z
    lcm3=x*lcm2
    return lcm3
x=int(input("number1"))
y=int(input("number2"))
z=int(input("number 3"))
print("the lcm of three nos is" +str(lcm_gcd(x,y,z)))

Output::
Number 1 5
Number 2 10
Number 3 15
The gcd of three numbers is 5
The gcd of three numbers is 30

Program 5
Check whether the number is perfect or not 121910314029_05

import math
num=int(input(“Enter a number:”))

root=math.sqrt(num)
if
int(root+0.5)**2==num:
print(num,”is a perfect square”)
else
print(num,”is not a perfect square”)



Output::
Enter the Number29
29 is not a perfect square


Program 6::
Print twin primes upto a specifed limit 121910314029_06

def prime(n):
for =0
for i in range(2,n//2+1);
if n%I==0;
f=1
break
return f
num=int(input("enter staring”))
num2=int(input("enter ending number”))
print("twin prime numbers are”)
for(i in range(num,num2+1):
if prime(i)==0 and prime(i+2)==0:
print(i,"",i+2)

Output::
Enter Starting 1
Enter Ending 100
Twin prime numbers are
1  3
3  5
5  7
11  13
17  19
29  31
41  43
59  61
71  73

Program 7:
Print prime numbers upto a specified limit 121910314029_07



print("Enter start:")


start = int(input())

print ("Enter end:")
end = int(input())

for i in range(start,end): 
	for j in range(2,i): 
		if(i % j==0): 
			break
	else: 
		print(i) 


Output::


Enter start:

1
Enter end:

29
1
2
3
5
7
11
13
17
19
23

Program 8

Find the sum of digits. Check whether the number is Armstrong or not 121910314029_08
Print(“Enter a number:”)
a=int(input())
b=a
sum=0
add=0
while(a>0):
x=a%10
add=add +x**5
sum=int(sum+x)
a= int(a/10)
print(“sum of the digits “+str(b)+”is”,sum)
if b==add:
Print(str(b))+” is a armstrong number”)
Else:
Print(str(b)+”is not a armstrong number”)
 Output::
Enter a number:
153
Sum of digits is 9
153  is an armstrong number


Program 9 
Swapping of two digits 121910314029_09


print("Swapping of two numbers")
print("Enter first number:")
x=int(input())
print("Enter second number:")
y=int(input())

print("Before Swapping ",+x,+y)
temp=x
x=y
y=temp

print("After Swapping ",+x,+y)

Output::

Swapping of two numbers
Enter first number:

18
Enter second number:

14
Before Swapping  18 14
After Swapping  14 18

Program 10
Perform all arithemetic operations 121910314029_10

print("Arithemetic Operations")

print("Enter first number")
x=int(input())
print("Enter second number")
y=int(input())
sum=x+y
print("sum=",+sum)

diff=x-y
print("diff=",+diff)

mul=x*y
print("mul=",+mul)

div=x/y
print("div=",+div)

mod=x%y
print("mod=",+mod)

Output::
Arithemetic Operations
Enter first number

14
Enter second number

18
sum= 32
diff= -4
mul= 252
div= 0.7777777777777778
mod= 14

