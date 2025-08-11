a = 8
b = 5
c = 9
nota_soma = a + b + c
nota_divisão = nota_soma // 3
import random
lista_de_nomes = ['indiano', 'Erik', 'memphis']
nome_Aleatorio = random.choice (lista_de_nomes)
print(f'media desse aluno {nome_Aleatorio} e {nota_divisão}')
matriz = [[0,0,0],
          [0,0,0],
          [0,0,0],
]
for l in range(0, 3):
    for c in range(0, 3):
        matriz[l] [c] = int(input(f'digite um valor para [{l},]:'))
for m in zip(matriz):
    print(m)
print(f'media desse aluno {nome_Aleatorio} e {nota_divisão}')
