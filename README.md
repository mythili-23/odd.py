# odd.pynum=int(input("enter n value"))
count=0
while(num>0):
    rem=num%10
    num=num//10
    if(rem%2!=0):
        count=count+1
print(count)
