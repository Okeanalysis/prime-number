# prime-number
#python code to determine if a number is a prime number

num1 = float(input("enter first number:"))
potentialFactor = 2

while num1 % potentialFactor != 0:
	potentialFactor = potentialFactor + 1 
  
  

if potentialFactor == num1:
	print(num1, "is a prime number")
else:
	print(num1, "is not a prime number")
