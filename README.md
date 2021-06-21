Task 3:
With while loop
table_of = int(input("enter table of"))
times = int(input("enter upto"))
i = 1
while i<=times:
    print(table_of,'x', i,'=',table_of*i)
    i=i+1
with for loop
table_of = int(input("enter table of"))
times = int(input("enter upto"))
for i in range(1 , times+1):
    print(table_of,'x', i,'=',table_of*i)
task 9: with for loop
sum = 0
for i in range(100 , 201):
    sum = sum+i
    print(sum)

with while loop
sum = 0
x =  100
while x<=200:
    sum=sum+x
    x = x+1
print(sum)

task 4:
print("enter 10 values\n")
count1 = 0
count2 = 0
count3 = 0
for i in range(1,11):
    x=int(input())
    if x<0:
        count1= count1+1
    elif x>0:
        count2 = count2+1
    elif x== 0:
        count3 =count3+1
print("positive numbers are:",count2)
print("negative numbers are:", count1)
print("zeros are:",count3)
with while loop
print("enter 10 values\n")
count1 = 0
count2 = 0
count3 = 0
i = 1
while i <= 10:
    x=int(input())
    if x<0:
        count1= count1+1
    elif x>0:
        count2 = count2+1
    elif x== 0:
        count3 =count3+1
    i=i+1
print("positive numbers are:",count2)
print("negative numbers are:", count1)
print("zeros are:",count3)

