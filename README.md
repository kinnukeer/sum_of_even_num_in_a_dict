# sum_of_even_num_in_a_dict
#sum of even numbers
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=0
for i in d:
  if i%2==0:
    r=r+d[i]
print(r)
