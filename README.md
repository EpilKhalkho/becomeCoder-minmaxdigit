# becomeCoder-minmaxdigit
num=int(input())
max=0
min=9
while num:
    x=num%10
    num=num//10
    if x>max:
        max=x
    elif x<min:
        min=x
print("maximum digit is", max,"minimum digit is", min)

