# 1015.py
questão 1015 do BeeCrowd


def maior_de_tres(a, b, c):
    x = (a + b) / 2 + abs(a - b) / 2
    x = (x + c) / 2 + abs(x - c) / 2
    return x


n1 = input().split(' ')

a = int(n1 [0])
b = int(n1 [1])
c = int(n1 [2])

maior = maior_de_tres(a, b, c)
maiorx = int(maior)
print(f"{maiorx} eh o maior")
