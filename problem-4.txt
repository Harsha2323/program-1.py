#Problem 4

mult={1:0,2:0,3:0,4:0,5:0,6:0,7:0,8:0,9:0}
inp = [1,2,8,9,12,46,76,82,15,20,30]
mult[1]=len(inp)
for i in range(2,10):
count=0
for j in inp:
if(j%i==0):
count+=1
mult[i]=count
print(mult)