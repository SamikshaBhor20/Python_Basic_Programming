# Python_Basic_Programming
#Writing python basic programing on the Fibonacci series.
#Code:-
from itertools import count


series=int(input("Enter the number, for the Fibonacci series= "))
n1,n2=0,1
count=0

#To check if the enter number is valid to calculate fibonacci serires or not
if series<1:
    print("Please enter the positive integer")
#If there is only 1 number in the series
elif series==1:
    print("\n Fibonacci serires=",series,"=")
else:
    print("\n Fibonacci Seires=")
while count < series:
       print(n1)
       nth = n1 + n2
       # update values
       n1 = n2
       n2 = nth
       count += 1
    
