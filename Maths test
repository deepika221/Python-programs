import math

def is_prime(num):
    if num <= 1:
        return False
    if num == 2:
        return True
    if num % 2 == 0:
        return False
    for i in range(3, int(math.sqrt(num)) + 1, 2):
        if num % i == 0:
            return False
    return True

def next_prime(N):
    candidate = N + 1
    while True:
        if is_prime(candidate):
            return candidate
        candidate += 1

# Input reading
N = int(input())
result = next_prime(N)
print(result)
