#approach 1
a=int(input())
f=0
for i in range(1,a+1):
  if(a%i==0):
    f=f+1
if(f==2):
  print("Prime")
else:
  print("Not")
#approach 2
a=int(input())
f=0
for i in range(2,a):
  if(a%i==0):
    f=1
    break
if(f==0):
  print("Prime")
else:
  print("Not")
#approach 3
a=int(input())
for i in range(2,a):
  if(a%i==0):
    print(" not prime")
    break
else:
  print("prime")
#approach 4
n=int(input())
for i in range(2,int(n**0.5)):
  if(n%i==0):
    print("prime")
    break
else:
  print("not")

