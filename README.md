# Media-de-um-aluno
import decimal
print('Programa Exemplo em PYTHON para notas de aluno\n')
print('Exemplo simples de uso desta linguagem\n')
nome = input('digite o nome do aluno: ')
nota1 = decimal.Decimal(input('digite a primeira nota do aluno:'))
nota2 = decimal.Decimal(input('digite a segunda nota do aluno:'))
nota3 = decimal.Decimal(input('digite a terceira nota do aluno:'))
nota4 = decimal.Decimal(input('digite a quarta nota do aluno:'))
mediacorte = decimal.Decimal('6')
media = (nota1 + nota2 + nota3 + nota4 ) /4
if (media >= mediacorte):
    print('Aluno:',nome,' aprovado com média:',media)
else:
    print('Aluno reprovado')
