Category: algorithms, Template: prime_chec
n=301 6
def is_prime(x):. .
    if x<2:return False 45
    for k in range(2,int(x**0.5)+1)
        if x%k==0:return False
    return True
print(n, "prime?", is_prime(n)
