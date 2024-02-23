# Exercícios em Python (UNIVESP) - Disciplina de Algoritmos

Exercício 3.1
Implemente um programa que solicita a temperatura atual em graus Fahrenheit
do usuário e exibe a temperatura em graus Celsius:
Seu programa deverá ser executado da seguinte forma:

>>>
Digite a temperatura em graus Fahrenheit: 50
A temperatura em graus Celsius é 10.0

Exercício 3.8
Defina, diretamente no shell interativo, a função média(), que aceita dois
números como entrada e retorna a média dos números. Um exemplo de uso é:

>>> average(2, 3.5)
2.75

Exercício 3.9
Implemente a função perímetro(), que aceita, como entrada, o raio de um círculo
(um número não negativo) e retorna o perímetro do círculo. Você deverá escrever sua
implementação em um módulo chamado perímetro.py. Um exemplo de uso é:

>>> perimeter(1)
6.283185307179586

Exercício 3.10
Escreva a função negativos(), que aceita uma lista como entrada e exibe, um por
linha, os valores negativos na lista. A função não deverá retornar nada.

>>> negatives([4, 0, −1, −3, 6, −9])
-1
-3
-9

Exercício 3.11
Acrescente a docstring retorna a média de x e y à função média() e a docstring
exibe os números negativos contidos na lista lst à função negativos() dos Problemas
Práticos 3.8 e 3.10. Verifique seu trabalho usando a ferramenta de documentação
help(). Você deverá receber, por exemplo:

>>> help(média)
Ajuda sobre a função média no módulo __main__:
média(x, y)
 retorna a média de x e y

Exercício 3.12
Desenhe um diagrama representando o estado dos nomes e objetos após esta execução:

>>> a = [5, 6, 7]
>>> b = a
>>> a = 3

Exercício 3.13
Suponha que uma lista não vazia time foi atribuída. Escreva uma instrução Python ou
instruções que mapeiam o primeiro e último valor da lista. Assim, se a lista
original for:

>>> time = [’Ava’, ’Eleanor’, ’Clare’, ’Sarah’]
  
então a lista resultante deverá ser:
  
>>> time
[’Sarah’, ’Eleanor’, ’Clare’, ’Ava’]
Exercício 3.14

Implemente a função trocaPU(), que aceita uma lista como entrada e troca o primeiro e
último elementos da lista. Você pode considerar que a lista não estará vazia.
A função não deverá retornar nada.

>>> ingredientes = [’farinha’, ’açúcar’, ’manteiga’, ’maçãs’]
>>> trocaPU(ingredientes)
>>> ingredientes
[’maçãs’, ’açúcar’, ’manteiga’, ’farinha’]
