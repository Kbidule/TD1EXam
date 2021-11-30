1)

from math import *

a = float(input())
b=float(input())
p=2*a+2*b
A=a*b
d=sqrt(a*a+b*b)
R=d/2
print(p,A,d,R)



2)
a=int(input())
t=a+62
print(a+62)
v=t%100+t//100
print(v)
print(a-v)



3)
a=int(input())

h=int(input())
if a>=8 or a<=0: 
    print("Donnee(s) non valide(s)")
elif h>=23 or h<0 : 
     print("Donnee(s) non valide(s)")
elif a==6 or a==7 : 
    print("Bus toutes les 15 minutes")
elif 7<h<10 or 17<h<19 : 
    print("Bus toutes les 7 minutes")
else: 
    print("Bus toutes les 10 minutes")
