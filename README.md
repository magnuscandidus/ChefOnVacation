# ChefOnVacation
# cook your dish here
t=int(input())
while t:
    x,y,z=map(int,input().split())
    if((x+y)<=z):
        print("Yes")
    else:
        print("No")
    t-=1
