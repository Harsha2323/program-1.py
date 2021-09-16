#Problem 3

inp = int(input())
if(inp%2==0):
inp-=1
out=-1
for i in range(inp):
out+=2
print(out,end=" ")