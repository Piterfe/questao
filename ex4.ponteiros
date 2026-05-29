

## 1. Explique com suas palavras o que é um ponteiro em programação.

Um ponteiro é uma variável que armazena o endereço de memória de outra variável. Em vez de guardar diretamente um valor, ele guarda a localização onde esse valor está armazenado na memória do computador.

---

## 2. Em linguagens como C, o que significa dizer que uma variável armazena o endereço de memória de outra variável?

Significa que a variável não contém o valor diretamente, mas sim a posição na memória onde o valor está armazenado. Dessa forma, é possível acessar ou modificar o valor original por meio desse endereço.

```c
int numero = 10;
int *ponteiro = &numero;
```

---

## 3. Python possui ponteiros como C? Explique como Python trabalha com referências a objetos.

Python não possui ponteiros explícitos como C. Em Python, as variáveis armazenam referências para objetos.

```python
x = 10
```

A variável `x` referencia um objeto inteiro com valor 10.

---

## 4. Crie uma variável chamada numero com o valor 10 e uma segunda variável chamada referencia que receba numero. Exiba as duas variáveis.

```python
numero = 10
referencia = numero

print("numero =", numero)
print("referencia =", referencia)
```

---

## 5. Altere o valor da variável numero depois de criar referencia. O valor de referencia também muda? Explique o resultado em Python.

```python
numero = 10
referencia = numero

numero = 20

print("numero =", numero)
print("referencia =", referencia)
```

**Saída:**

```text
numero = 20
referencia = 10
```

Inteiros são imutáveis. Ao alterar `numero`, uma nova referência é criada.

---

## 6. Crie uma lista chamada valores com três números. Crie outra variável chamada ponteiro_lista que receba valores. Altere um elemento usando ponteiro_lista e exiba valores.

```python
valores = [10, 20, 30]

ponteiro_lista = valores

ponteiro_lista[0] = 99

print(valores)
```

**Saída:**

```text
[99, 20, 30]
```

---

## 7. Explique por que, no caso de listas, duas variáveis podem apontar para o mesmo objeto em Python.

Listas são objetos mutáveis. Quando fazemos:

```python
lista2 = lista1
```

As duas variáveis passam a referenciar o mesmo objeto na memória.

---

## 8. Use a função id() para mostrar o identificador de memória de duas variáveis que apontam para o mesmo objeto.

```python
lista = [1, 2, 3]

a = lista
b = lista

print(id(a))
print(id(b))
```

Os valores serão iguais.

---

## 9. Crie duas listas iguais usando valores diferentes. Use id() para verificar se elas são o mesmo objeto.

```python
lista1 = [1, 2, 3]
lista2 = [1, 2, 3]

print(id(lista1))
print(id(lista2))
```

Os identificadores serão diferentes.

---

## 10. Explique a diferença entre usar == e is em Python.

* `==` compara os valores dos objetos.
* `is` compara se são o mesmo objeto na memória.

Exemplo:

```python
a = [1, 2, 3]
b = [1, 2, 3]

print(a == b)
print(a is b)
```

**Saída:**

```text
True
False
```

---

## 11. Crie um programa que compare duas variáveis usando == e is.

```python
lista1 = [1, 2, 3]
lista2 = [1, 2, 3]
lista3 = lista1

print(lista1 == lista2)
print(lista1 is lista2)

print(lista1 == lista3)
print(lista1 is lista3)
```

---

## 12. Crie uma função chamada alterar_lista(lista).

```python
def alterar_lista(lista):
    lista.append(100)

numeros = [1, 2, 3]

alterar_lista(numeros)

print(numeros)
```

**Saída:**

```text
[1, 2, 3, 100]
```

---

## 13. Crie uma função chamada alterar_numero(numero).

```python
def alterar_numero(numero):
    numero += 10

valor = 5

alterar_numero(valor)

print(valor)
```

**Saída:**

```text
5
```

---

## 14. Explique por que objetos mutáveis podem ser alterados dentro de funções.

Porque a função recebe uma referência para o mesmo objeto. Alterações feitas dentro da função afetam o objeto original.

---

## 15. Explique por que objetos imutáveis não são alterados diretamente dentro de funções.

Porque qualquer alteração gera um novo objeto. A variável local passa a apontar para esse novo objeto, sem alterar o original.

---

## 16. Crie um dicionário chamado aluno.

```python
aluno = {
    "nome": "Maria",
    "idade": 20
}

referencia_aluno = aluno

referencia_aluno["idade"] = 21

print(aluno)
```

**Saída:**

```text
{'nome': 'Maria', 'idade': 21}
```

---

## 17. Use o método copy() para criar uma cópia de uma lista.

```python
lista_original = [1, 2, 3]

lista_copia = lista_original.copy()

lista_copia[0] = 99

print(lista_original)
print(lista_copia)
```

**Saída:**

```text
[1, 2, 3]
[99, 2, 3]
```

---

## 18. Crie uma lista dentro de outra lista e faça uma cópia com copy().

```python
lista_original = [[1, 2], [3, 4]]

lista_copia = lista_original.copy()

lista_copia[0][0] = 99

print(lista_original)
print(lista_copia)
```

**Saída:**

```text
[[99, 2], [3, 4]]
[[99, 2], [3, 4]]
```

---

## 19. Explique a diferença entre cópia rasa e cópia profunda.

### Cópia rasa (Shallow Copy)

Copia apenas o objeto principal.

### Cópia profunda (Deep Copy)

Copia o objeto principal e todos os objetos internos.

```python
import copy

original = [[1, 2], [3, 4]]

copia_rasa = copy.copy(original)
copia_profunda = copy.deepcopy(original)

copia_rasa[0][0] = 99

print(original)
print(copia_rasa)
print(copia_profunda)
```

**Saída:**

```text
[[99, 2], [3, 4]]
[[99, 2], [3, 4]]
[[1, 2], [3, 4]]
```

---

## 20. Simule ponteiros usando referências.

```python
dados = [10, 20, 30]

ponteiro1 = dados
ponteiro2 = dados

ponteiro1.append(40)

print("ponteiro1:", ponteiro1)
print("ponteiro2:", ponteiro2)
```

**Saída:**

```text
ponteiro1: [10, 20, 30, 40]
ponteiro2: [10, 20, 30, 40]
```

As duas variáveis referenciam o mesmo objeto na memória.


