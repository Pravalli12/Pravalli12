def countPno(n):
    count = 0
    
    for num in range(n):
        if num <= 1:
            continue
        for i in range(2, num):
            if (num % i) == 0:
                break
        else:
            count+= 1

    return count
n=int(input ('Enter n:'))
print(countPno(n))
