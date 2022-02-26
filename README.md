# 25-2-2022-3
n=int(input())

l=[]

t=[]

for i in range(n):

      x= int(input())

      l.append(x)

print(l)

c=0

for i in range(n):

    if l[i]!=0:

        t.append(l[i])

        c=c+1

print(c,'',t)
