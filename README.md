a=int(input())
l=[]
for i in range(a):
    b=list(map(str,input().split(",")))
    b[1]=int(b[1])
    l.append(a)
c=[0]
for i in l:
    if(i[1:]>c[1:]):
        c=i
    elif(i[1:]==c[1:]):
        if i[1]>c[1]:
            c=i
print(c[0])
