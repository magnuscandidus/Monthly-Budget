# Monthly-Budget
t=int(input())
while t:
    x,y=map(int,input().split())
    if((y*30)<=x):
        print("YES")
    else:
        print("NO")
    t-=1
