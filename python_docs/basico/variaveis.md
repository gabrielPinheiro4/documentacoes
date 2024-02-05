# O que são variáveis em Python ?
Variáveis são espaços reservados na memória do computador com o objetivo de armazenar tipos de dados durante a execução do código.

Para criar uma varíavel devemos passar o seu nome e utilizar o sinal de igual (=) para atribuir um valor.

Diferente de outras linguagens como Java e C++, em Python, não precisamos definir o tipo da variável durante sua criação, podemos apenas nomeá-la e passar seu respectivo valor.


```python
# Váriável do tipo string
variavel_str = "Olá Mundo"

# Váriávél do tipo float
variavel_float = 1.5

# Váriável do tipo boolean
variavel_boolean = True
```

Note que em Java precisamos definir o tipo da variável

```java
// Criação de variável em Java
String variavel_str = "Olá Mundo"
float variavel_float = 1.5
boolean variavel_boolean = true
```

Ao nomear uma variável sempre devemos utilizar letras minúsculas e quando tivermos que separar duas palavras devemos utilizar o underline (_), essa prática tem o nome de Snake Case, essa é a forma recomendada para se criar variáveis em Python. Também é possível separar palavras utilizando letras maiúsculas, pórem não é recomendado. Espaços, hífen e acentuação estão fora de questão.

```python
# Forma correta
variavel_separada = "Olá mundo"

# Forma incorreta
variavelSeparada = "Olá mundo"

#Forma incorreta
variavel separada = "Olá Mundo"

#Forma incorreta
variavel-separada = "Olá Mundo"

#Forma incorreta
variável_separada = "Olá Mundo"
```

# Tipos de dados em Python
Em Python temos diversos tipos de dados que podemos utilizar, aqui estão os principais deles.

## Inteiro (int)
Utilizado para armazenar tipos númericos inteiros, podendo ser valores positivos ou negativos.

```python
variavel_int = 45
variavel_int = -12
```

## Ponto flutuante (float)
Utilizado para armazenar tipos númericos decimais, podendo ser valores positivos ou negativos.

```python
variavel_float = 12.89
variavel_float = -1.5
```

## Strings (str)
Utilizado para armazenar sequências de caracteres, seu início e fim é definido pelas aspas.

```python
variavel_str = "Eu sou uma string"
```

## Booleano (bool)
Utilizado para armazenar valores lógicos, verdadeiro (True) ou falso (False)

```python
variavel_bool = True
variavel_bool = False
```