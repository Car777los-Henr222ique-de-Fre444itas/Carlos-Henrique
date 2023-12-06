# Carlos-Henrique

# Famoso Olá mundo 

print("Olá, mundo!")

# Codigos que aprendi no curso de Python 

carrinho = []
produto = ''
while produto !="sair":
    print("Adicione um pruduto na lista ou digite 'sair' para sair: ")
    produto = input()
    if produto != 'sair':
        carrinho.append(produto)
# -------------------------------------------------------------------------------------------------
cidade = ['Belo Horizonte', 'São Paulo', 'Campo Grande', 'Campo Grande', 'São Paulo', 'Cuiaba']

print(cidade)
# ------------------------------------------------------------------------------------------------
Lista = []
lista.append(42)
lista.append(42)
lista.append(33)
lisra.append(33)
lista.append(42)

print(lista) 
# --------------------------------------------------------------------------------------------------
lista = [1,2,3]
print(lista)

nova = lista.copy

print(nova)

nova.append(4)

print(lista)
print(nova)
# ------------------------------------------------------------------------------------------------------
Tupla1=(1,2,3,4,5,6)
print(tupla1)

print(type (tupla1))

tupla2 = 1,2,3,4,5,6
print(tupla2)

print (type (tupla2))

# Isso não e uma Tupla!

tupla3=(4)
print(tupla3)

print(type(tupla3))

# Isso e uma Tupla!

tupla4 = (4)
print(tupla4)


print (type(tupla 4))

tupla = tuple(range(11))

print(tupla)
print(type(tupla))
-----------------------------------------------------------------------

#Random: Possui varias funções para geração de números pseudo-aleatorio

#Forma1
import random
print(random.random)

from randondom import random
form i in range(10)
    print(random())

#Forma2

from random import random
for i in range(10)
    print(random())

Uniform: Gerar um numero real pseudo aleatorio entre os valores estabelecidos

from random importuniform
for i in range (10)
    print(uniform(5,10)

#randint: Gera valores inteiros psiudo-aleatórios entre os valores estaberlecidos 

from random import randint

for i in range(6)
    print(randint(1,61),end' , ')

#Choice: mostra um valor aleatorio entre um iteravel

from random import choice

jogadas=['pedra','papel','tesoura']
print(choice(jogada))

#Shuffle: Tem a função de embaralhar dados 

cartas=['k','q','j','a','2','3','4','5','6','7']

print(cartas)
shuffle(cartas)
print(cartas.pop())
