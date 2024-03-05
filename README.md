# cost-of-groceries in python
# cost of groceries
# Approach-1
t=int(input())
for _ in range(t):
  n,x=map(int,input().split())
  a=list(map(int,input().split()))
  b=list(map(int,input().split()))
  c=0
  for i in range(n):
    if a[i]>=x:
      c=c+b[i]
  print(c)
