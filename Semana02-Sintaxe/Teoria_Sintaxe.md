1- Sintaxe

Python possui algumas particularidades em comparação com outras linguagens, 
as principais diferenças podem ser notadas no aprendizado de fundamentos da linguagem.


- Indentação
- Variáveis
- Comentários de uma e múltiplas linhas
- Entrada e saída - (input e fstrings)
- Strings
- Operadores
 

# Indentação:
No python o bloco é delimitado apenas pela indentação das sentenças, não utilizamos chaves como em outras linguagens. Não é uma boa prática misturar espaços com TAB para identar

```python
if a < 2:
    print(a)
print(b)
# OBS: Não misturar espaços com tabs, ou um, ou outro
 ```

# Variáveis:

Python é uma linguagem dinâmica e fracamente tipada, em resumo isso quer dizer que não precisamos
indicar na declaração de uma variável, o tipo de dado que ela vai receber, o Pyrhon reconhece isso
de forma automática.

```python
a = 3
b = "Computação"
c = 3.5
d = True
e = None
type(e) # a função type() serve para retornar o tipo de dado
 ```



## Nomeando variáveis:

Alguns cuidados que devemos tomar na hora de nomear variáveis:
- Devem ser claras e diretas
- Evitar ambiguidades
- Evitar nomes muito extensos
- Nome de variável não pode começar com número
- Devemos evitar caracteres especiais (#, %, @, $)
- Evitar palavras chaves 
  - Palavras chaves, são palavras que já são utilizadas pela linguagem como (`class`, `for`, `while` e etc)
  

#1valor = 12 # erro de sintaxe (nome iniciado com número)
#v@lor = 12  # erro de sintaxe (nome com caractere especial)
#classe = 12 #erro de sintaxe  (utilização de palavras chaves do Python)



## Padronização na nomeação de variáveis:

A comunidade segue alguns padrões para nomeação de variáveis com nomes compostos, esse padrão é um consenso da 
comunidade e não uma obrigação da sintaxe, e pode variar de linguagem para linguagem. Veja alguns exemplos

## Camel Case: primeira palavra com inicial minúscula e as demais com inicial maiúscula
minhaNotaSemestral  = 8.0  

## Pascal Case: todas as palavras com inicial maiúscula
MinhaNotaSemestral  = 8.0

## Cada palavra inicia com letra minúscula e são separadas por underscore
minha_nota_semestral  = 8.0
 
---


## Comentários
Os comentários podem ser de um ou mais múltiplas linhas para delimitar um cometários de uma linha usa-se o símbolo # para delimitar comentário de múltiplas linhas usa-se """ ou '''

#Comentários não são exibidos e não são compilados
'''
os comentários
também podem ser de múltiplas
linhas
'''
 
--- 

# Entrada e saída
Para receber um dado utilize a função `input()`. Essa função por padrão retorna um dado do tipo string. Utilize a função type() para verificar o tipo de dado

## Entrada 

por padrão o método input retorna um dado do tipo string

```python

nome = input("Digite seu nome")
type(nome)
idade  =  input("Digite sua idade")
type(idade)
 
 ```
 
## Casting:

O valor de uma variável pode ser alterado utilizando uma conversão de tipo que chamamos de casting

## Para que o dado de outro tipo seja coletado, é necessário fazer a conversão no ato da entrada

```python
idade = int(input("digite sua idade"))
type(idade)
altura = float(input("Digite sua altura"))
 ```

## Saída:

```python
print(nome)
# Saída simples concatenando a string com a variável
print("Meu nome é : ", nome)
# A função format é utilizada para especificar algum comportamento da saída
print("Meu nome é {} e minha altura é {}".format(nome, altura) )
# Teste com a função format
t = input("Digite uma frase\n")
# Testes com format()
print("{0:>100}".format(t))  # Alinha a esquerda
print("{0:@>100}".format(t)) # Alinha a esquerda sem espaços
print("{0:^100}".format(t))  # Centraliza
print("{0:.^100}".format(t)) # Centraliza sem espaços
# Utilizando f'strings
print(f"Meu nome é {nome} e eu tenho {altura} de altura")
 
```
 

# Operações, Operadores e operandos:

- Aritméticos
- Atribuição
- Comparação
- Lógicos
- Relacionais O python utiliza quase todos os operadores matemáticos com algumas exceções
- Operadores Aritméticos


```python
# Adição +
2 + 2
"Evaldo" + " Pereira"
"K" * 7
# Divisão / ou //
4 /2
# Subtração - 
10 -8
# Multiplicação
3 * 4
# Módulo %
9  % 3
# potência **
2 ** 2
 ```

---


## Operadores de Atribuição:

Utilizados para atribuir um valor a um operando

```python
num1 = 2
num2 = 3

num1 = num2
print(num1)

num1 +=  num2
print(num1)

num1 -= num2
print(num1)

num1 *= num2
print(num1)

num1 /= num2
print(num1)

num1 %= num2
print(num1)

num1 **= num2
print(num1)
 ```
 
 ---
 
 
# Operadores de Comparação

Comparam dois valores retornando um tipo de dado booleano

```python
num3 = 6
num4 = 7

print(num3 == num4) # igualdade

print(num3 != num4) # diferença

print(num3 >= num4) # Maior ou igual

print(num3 <= num4) # menor ou igual

print(num3 > num4) # Maior

print(num3 < num4) # Menor
 ```
 
 
# Operadores Lógicos

São três:
- `and`: retorna True se os dois operandos forem verdadeiros
- `or` : retorna False se os dois operandos forem Falsos
- `not`: retorna a negação da sentença

# Operadores lógicos:

```python
num5 = 2
num6 = 3
(a % 2 == 0) or (a % 2 != 0)       # disjunção
(a % 2 == 0) and (a % 2 != 0)    # disjunção
not (True)                                  #negação
 ```
 
 
Francisco Evaldo


