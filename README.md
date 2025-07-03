# armstrong-nujmber
num=int(input("Enter the number:"))
temp=num
n=len(str(num))
sum=0
while temp>0:
    digit=temp%10
    sum+=digit**n
    temp//=10
print("Latest value of sum:",sum)
print("Latest value of temp:",temp)
if sum==num:
    print(num,"is a armstrong number")
else:
    print(num,"is not a armstrong number")
