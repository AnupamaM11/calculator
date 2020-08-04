# calculator
a=float(input("Enter 1st Number"))
op=input("Enter Operation")
b=float(input("Enter 2nd Number"))
if op=="+":
  print(a+b)
elif op=="-":
  print(a-b)
elif op=="/":
  print(a/b)
elif op=="%":
  print(a%b)
else:
  print(invalid Operation)
