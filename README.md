# random1
from random import choice
import string
aluno1=input('Digite o nome do primeiro aluno: ')
aluno2=input('Digite o nome do segundo aluno: ')
aluno3=input('Digite o nome do terceiro aluno: ')
aluno4=input('Digite o nome do quarto aluno: ')
lista = [aluno1,aluno2,aluno3,aluno4]
aluno=choice(lista)
print('O aluno que irá apagar o quadro é: {}!'.format(aluno))
