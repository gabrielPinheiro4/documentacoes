# Estruturas Condicionais em Python
Estruturas condicionais são responsáveis por executar um bloco de código caso uma condição for verdadeira.

Em Python sua usabilidade é bem simples, iremos utilizar as palavras reservadas if, elif e else.

Exemplo: Se tal coisa for verdadeira faça isso, senão, faça isso

```
if condicao:
    comando caso a condição for verdadeira
else:
    comando caso a condição for falsa
```


```python
admin = True

if admin == True:
    print('Você tem autorização para acessar o sistema')
else:
    print('Você não tem autorização para acessar o sistema')
```

No código acima estamos verificando se a variável 'admin' possui o valor igual a True (verdadeiro), e caso possua daremos acesso ao nosso sistema, caso contrário, não daremos acesso.

Veja que em python sua estrutura é bem simples. Vejamos como ficaria em outra linguagem.

```java
// Estrutura condicional em Java
boolean admin = true

if (admin == true){
    Sistem.out.println('Você tem autorização para acessar o sistema')
}else{
    Sistem.out.println('Você não tem autorização para acessar o sistema')
}
```

Porém podemos melhorar ainda mais nosso código, como uma estrutura condicional verifica se uma condição é verdadeira, não precisamos escrever admin == True, podemos apenas escrever if admin.

```python
admin = True

if admin:
    print('Você tem autorização para acessar o sistema')
else:
    print('Você não tem autorização para acessar o sistema')
```

Também podemos usar operadores matemáticos.

```python
num1 = 12
num2 = 6

if num1 > num2:
    print('num1 é maior que num2')
else:
    print('num2 é maior que num1')
```

No código acima estamos verificando qual é o maior valor entre dois números, e no final imprimindo uma mensagem dizendo qual é maior.

Caso precisemos verificar se mais de uma condição for verdadeira iremos utilizar a palavra reservada elif logo após o if.

```
if condicao:
    comando caso a primeira condição for verdadeira

elif condicao:
    comando caso a segunda condição for verdadeira

else:
    comando caso nenhuma das condições for verdadeira
```

```python
usuario = 'admin'

# Executa se o usuario tiver valor igual a 'admin'
if usuario == 'admin':
    print('Você tem acesso a todo o sistema')

# Executa se o usuario tiver valor igual a 'funcionario'
elif usuario == 'funcionario':
    print('Você tem acesso a uma parte do sistma')

# Executa caso nenhuma das condições acima for verdadeira
else:
    print('Você não tem acesso ao sistema')
```