# code
5 programs

#1 helloworld
print('Hello world")

#2 factorial
n = int(input())
fact=1
for i in range(n):
  fact = fact*i
print(fact)

#3 fibonacci series
n = int(input())
i=2
a=0
b=1
print(a)
print(b)
while(i<n):
  c=a+b
  print(c)
  a=b
  b=c
  i=i+1

#4 primeno
n = int(input())
for i in range(n):
  if(n%i==0):
    c=c+1
  if(c>2):
    print("not prime")
   else:
    print("prime")

#5 sum of digits
n= int(input())
num = n
sum=0
while(num>0):
  rem= n%10
  sum=sum+rem
  num=num/10
print(sum)
