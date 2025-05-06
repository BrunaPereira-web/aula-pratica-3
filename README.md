#expressoes booleanas 1
if(2 + 2 <= 4):
  print("Verdadeiro")

#exercicio2
if(7 //3 == 1+1):
  print("Verdadeiro")

#exercicio3
if(3**2 + 4**2 == 25):
  print("Verdadeiro")

#exercicio4
if(2 + 4 + 6 > 12):
  print("Verdadeiro")

#exercicio5
if(1387 % 19 == 0):
  print("Verdadeiro")

#exercicio6
if(31 % 2 == 0):
  print("Verdadeiro") 
#se não deu nada ele é impar

#exercicio7
if(min(34, 29, 31) < 30):
  print("Verdadeiro") 

#CONDICIONAIS SIMPLES 1

idade = 62
if (idade>60):
  print("Você tem direito aos benefícios!")

#CONDICIONAL2
dano = 13
escudo = 0
if(dano > 10 and escudo == 0):
  print("Você está morto!")

#CONDICIONAL3
norte = True
sul = False
leste = False
oeste = False
if(norte == True or sul == True or leste == True or oeste == True):
  print("Você escapou!")

#CONDICIONAIS COMPOSTAS 1
ano = 1993
if(ano % 4 ==0):
  print("Ano pode ser bissexto")
else:
  print("Ano definitivamente não é bissexto")

#EXERCICIO 2
cima = true
baixo = true
if (cima == true and baixo == true):
  print("Decida-se")
else:
  print("Voce escolheu um caminho")

#PROBLEMAS ELABORADOS

A = int(input ('Digite o primeiro lado dos triangulos: '))
B = int(input ('Digite o primeiro lado dos triangulos: '))
C = int(input ('Digite o primeiro lado dos triangulos: '))
if ((A>0 and B>0 and C>0) and A+B>C and A+C>B and B+C>A)):
 #se chegou até aqui é porque o triangulo é válido
if(A !=B and A!=C and B!=C):
  print('Triangulo é escaleno')
else:
  if: (A==B and B==C):
    print('Triangulo equilatero')
 else:
   print('Triangulo isósceles')
else:
  print('ao menos um dos valores indicados não servem para formar um triangulo')

#PROBLEMA 2
print('CALCULADORA')
print('+ adição')
print('- subtração')
print('* multiplicação')
print('/ divisão')
print('Pressione qualquer outra tecla para sair')

op = input
('Qual operação deseja realizar?')
x = int(input('Digite o primeiro valor inteiro: '))
y = int(input('Digite o segundo valor inteiro: '))

if(op == '+'):
  res = x + y
   print(f'resultado: {x} + {y} = {res}')

elif(op == '-'):
 res = x - y
   print(f'resultado: {x} - {y} = {res}')

elif(op == '*'):
 res = x * y
   print(f'resultado: {x} * {y} = {res}')

elif(op == '/'):
 res = x / y
   print(f'resultado: {x} / {y} = {res}')
else:
print('Encerrando o programa...')
