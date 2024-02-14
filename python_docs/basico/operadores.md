# Operadores em Python

## Operadores Aritiméticos
Realiza uma operação aritimética entre dois números.

| Operador | Funcionalidade |
|:-------- | :------------- |
| `+ `| Realiza a soma entre dois números |
| `- `| Realiza a subtração entre dois números |
| `* `| Realiza a multiplicação entre dois números |
| `/ `| Realiza a divisão entre dois números |
| `//` | Realiza a divisão entre dois números e retorna um valor inteiro
| `% `| Retorna o resto da divisão entre dois números |
| `**` | Retorna a potenciação de um número para o outro |

```python
valor1 = 12
valor2 = 5

print(valor1 + valor2) # Resultado: 17
print(valor1 - valor2) # Resultado: 7
print(valor1 * valor2) # Resultado 60
print(valor1 / valor2) # Resultado: 2.4
print(valor1 // valor2) # Resultado 2
print(valor1 % valor2) # Resultado: 2 
print(valor1 ** valor2) # Resultado: 248832
```

## Operadores de Atribuição
Com esses operadores podemos atribuir um valor em nossa variável.

| Operador | Funcionalidade | Equivalente a |
| :------- | :--------------|:--------------|
| `= `| Atribuir um valor em uma variável | x = 1 |
| `+=` | Soma o valor atual com o valor desejado e atribui o resultado na variável | x = x + 1 |
| `-= `| Decrementa o valor atual com o valor desejado e atribui o resultado na variável|  x = x - 1 | 
| `*=` | Multiplica o valor atual com o valor desejado e atribui o resultado na variável | x = x * 1
| `/=` | Divide o valor atual com o valor desejado e atribui o resultado na variável | x = x / 1 |
| `%=` | Retorna o resto da divisão entre o valor atual e o valor desejado e atribui o resultado na variável |  x = x % 1 |

```python
valor1 = 12
valor2 = 5

# Variável 'valor1' será 17
valor1 += valor2

# Variável 'valor1' será 7
valor1 -= valor2

# Variável 'valor1' será 60
valor1 *= valor2

# Variável 'valor1' será 2.4
valor1 /= valor2

# Variável 'valor1' será 2
valor1 %= valor2
```

## Operadores de Comparação
Compara dois valores e retorna True ou False dependendo da operação.

| Operador | Funcionalidade |
|:-------- | :------------- |
| `==` | Compara se um valor é igual ao outro |
| `!=` | Compara se um valor é diferente do outro  |
| `> `| Compara se um valor é maior que o outro |
| `< `| Compara se um valor é menor que o outro |
| `>=` | Compara se um valor é maior ou igual ao outro |
| `<=` | Compara se um valor é menor ou igual ao outro |

```python
valor1 = 12
valor2 = 5

print(valor1 == valor2) # Resultado: False
print(valor1 != valor2) # Resultado: True
print(valor1 > valor2) # Resultado True
print(valor1 < valor2) # Resultado: False
print(valor1 >= valor2) # Resultado True
print(valor1 <= valor2) # Resultado: False
```

## Operadores Lógicos
Usado para juntar duas ou mais expressões condicionais.

| Operador | Funcionalidade |
|:-------- | :------------- |
| `and` | Retorna True se todas as expressões forem verdadeiras |
| `or` | Retorna True se uma expressão for verdadeira|
| `not` | Retorna o valor booleano contrário |


```python
usuario = 'admin'
senha = 'admin123'

# Se a variável usuario for igual a 'admin' e a variável 
# senha for igual a 'admin123' libere o acesso ao sistema.

# Caso uma das variáveis esteja errada, não terá acesso ao sistema

if usuario == 'admin' and senha == 'admin123':
    print('Pode acessar o sistema')
else:
    print('Acesso negado')
```