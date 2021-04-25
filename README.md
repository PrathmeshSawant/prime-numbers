n=int(input("Enter number : "))
prime = True
for i in range(2,n):
  if n%i==0:
    check = False
    break;
if prime:
  print("It is a prime number")
else:
  print("It is not a prime number")
