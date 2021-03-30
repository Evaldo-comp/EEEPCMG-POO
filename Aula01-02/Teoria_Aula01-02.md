# Introdução - Variáveis e Operadores

Python é uma linguagem fracamente tipada e dinâmica, sendo assim não precisamos definir o tipo de dado que a variável vai receber ao criá-la, sendo assim 
basta definir o nome da variável e atribuir o seu respectivo dado através do operador ` = `:

```python
# Linguagem fracamente tipada
a = 3                       # dado do tipo Inteiro
b = "Computação"            # dado do tipo String
c = 3.5                     # dado do tipo Float
d = True                    # dado do tipo Booleano
e = None                    # variaǘel inicializada sem valor definido

```

Quando vamos nomear uma variável, devemos tomar alguns cuidados, por convenção os nomes de variáveis devem ser claros, simples e devem estar ligados diretamente
a função ou a informação que essa variável vai receber. Ao fazer isso, facilitamos a leitura do código. Seguem alguns cuidados.

- Devem ser claras e diretas
- Evitar ambiguidades
- Evitar nomes muito extensos
- Variáveis com nome composto deve seguir a seguinte estrutura
  - `primeiro_segundo = valor` , essa estrutura é chamada camel case.  

Outros cuidados além dos citados acima devem ser tomados, anteriormente citamos algumas convenções, ou seja, são acordos da comunidade, para padronizar o código
mas que não geram erro no código, mas a linguagem possui casos em que a nomeação incorreta pode gerar erros e devemos evitar. São eles:

- Nomes iniciados com números
- Utilizar palavras chave da linguagem (class, list, tuple)
- Caracteres especiais (@, $, #)

---

## Comentários

O comentário é utilizado para documentar o código, melhorar a leitura pra você ou para outra pessoa que venha ler seu código no futuro.

Os comentários podem ser de uma ou múltiplas linhas.
- Para delimitar um cometários de uma linha usa-se o símbolo `#`
```python

# Esse é um comentário de linha única e não será interpretado pela linguagem
```

- Para delimitar um comentáiro de múltiplas linhas, usa-se `"""` ou `'''`.
```python
""" Esse é 
um 
comentário
de múltiplas linhas
"""
```

---

## Operadores Aritméticos:

Podemos realizar operações matemáticas utilizando operadores da linguagem, esses operadores em sua maioria são iguais aos utilizados na matemática, com algumas
adaptações como podemos notar abaixo:

```python

# Adição  +
ad = 2 + 2

# Subtração - 
sub = 10 -8

# Divisão / ou //
div = 4 / 2

# Multiplicação
mul = 3 * 4

# Módulo %
mod = 9  % 3

# potencia **
pot = 2 ** 2
```


---
:house:[Home](https://github.com/Evaldo-comp/Python-Mombaca)
---
