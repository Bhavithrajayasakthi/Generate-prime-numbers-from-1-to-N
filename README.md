# Generate-prime-numbers-from-1-to-N
def generate_primes(n):
    for num in range(2, n + 1):
        for i in range(2, num):
            if num % i == 0:
                break
        else:
            print(num)

n = int(input("Enter the range: "))
generate_primes(n)
output:
Enter the range: 20
2
3
5
7
11
13
17
19
