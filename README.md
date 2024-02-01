# Reverse_py
x=int(input("Enter a number : "))
rev=0
n=x
while n>0:
    ld=n%10;
    rev=rev*10+ld
    n=n//10
print(f"{x} is reverse to {rev}")    
    
    
