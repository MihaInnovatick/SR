# SR 1
num = int(input('Введите 3-х  значное число: '))
n = num // 100
u = (num // 10) % 10
m = num % 10
c = n * u * m
if (max(n,u,m) - min(n,u,m,) == n + u + m - max(n,u,m) - min(n,u,m)) and 150<c<400:
    print('Это число интересное и магическое!: ')
    b = len(input('Введите строку: '))
    a = float(input('Введите число: '))
    x = (a - b)**2 / (a * (b / 3))
    print('X= ',x)
elif 150<c<400:
    print('Это число магическое!')
    s = str(input('Введите строку: '))
    if 'маг' in s:
        print('Заколдовано!')
    else:
        print('Нет эффекта')
elif max(n,u,m) - min(n,u,m,) == n + u + m - max(n,u,m) - min(n,u,m):
    print('Это число интересное!')
    z = len(input('Введите строку: '))
    z1 = num / z
    print(z1**2)
else:
    print('Это обычное число')
    
