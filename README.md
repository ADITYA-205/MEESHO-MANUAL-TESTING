## MEESHO-MANUAL-TESTING
### 23-09-2026

### Program 1:
```
a=input()
b=a.split(",")
for i in b:
  if (int(i,2))%5==0:
    print(i)
```
### Program 2
```
a=input()
c=0
d=0
for i in a:
  if(i.isalpha()):
    c+=1
  elif(i.isdigit()):
    d+=1
print("LETTERS ",c)
print("DIGITS ",d)
```
### Program 3
```
import math
a=int(input())
b=math.factorial(a)
print(b)
```
