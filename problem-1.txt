#Problem 1

a=float(input("Enter value of a"))
op=input("Enter operator")
b=float(input("Enter value of b"))
if(op=='+'):
print("Result of",a,op,b,"=",a+b)
elif(op=='-'):
print("Result of",a,op,b,"=",a-b)
elif(op=='/'):
print("Result of",a,op,b,"=",a/b)
elif(op=='*'):
print("Result of",a,op,b,"=",a*b)
elif(op=='%'):
print("Result of",a,op,b,"=",a%b)
else:
print("Invalid symbol")
