
l=[]
n=int(input('enter number: '))
for i in range(1,n+1):
    x=int(input())
    l.append(x)
print(l)
min=l[0]
for i in range(1,n):
    if l[i]<min:
        min=l[i]
print(min)
max=l[0]
for i in range(1,n):
    if l[i]>max :
        min=l[i]
print(max)P
