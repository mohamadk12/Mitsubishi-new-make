Category: algorithms, Template: prime_chec
n=301 y
def is_prime(x):
    if x<2:return False
    for k in range(2,int(x**0.5)+1)
        if x%k==0:return False
    return True
print(n, "prime?", is_prime(n))
