n=int(input("enter number range:"))
sum=0
total=0
for i in range (1,n+1):
    if i%2==1:
        sum=sum+i
    if i%2==0:
        total=total+i
sum=sum+total
print('sum of even and odd numbers :' ,sum)



output:
enter number range:16
sum of even and odd numbers:136
