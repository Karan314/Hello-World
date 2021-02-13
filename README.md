# Hello-World
My_First_Project
num=int(input("Enter the number :"))
res=[]
i=0
while i<num:
  if num//i==0:
    res=res+i
    res.sort()
print(res[0])
