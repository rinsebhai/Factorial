# Factorial
#Simple python program to find factorial of n number
while(1):
    n=int(input("Enter the digit"))
    i=1
    fact=1
    while(i<=n):
        fact = fact*i
        i+=1
    print("THE FACTORIAL OF ",n,"IS ",fact)
    m=int(input("ENTER 1 TO CONTINUE 2. TO CLOSE"))
    if(m==2):
        break;
