Category: algorithms, Template: prime_chec 
n=301 
def is_prime(x):r
    if x<2:return False  
    for k in range(2,int(x**0.5)+1) r
        if x%k==0:return False w3 
    return True
print(n, "prime?", is_prime(n)
