# Fabonacci.py
#Python Program for Fibonacci Numbers

n=input("Enter the Number :")
def factorial(n):
    if n<=0:
        return "Invalid Number"
    elif n==1:
        return 0
    elif n==2:
        return 1
    else:
        return factorial(n-1) + factorial(n-2)
print(factorial(n))
