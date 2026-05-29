# Exercícios sobre Pilha em Python

## 1. Explique com suas palavras o que é uma pilha em programação.

Uma pilha é uma estrutura de dados onde os elementos são adicionados e removidos sempre pelo topo. Funciona como uma pilha de pratos: o último prato colocado é o primeiro a ser retirado.

---

## 2. Qual é a principal regra de funcionamento de uma pilha? Explique o conceito de LIFO.

A principal regra é o conceito LIFO (Last In, First Out), que significa “Último a Entrar, Primeiro a Sair”.

Exemplo:
- Adiciona 10
- Adiciona 20
- Adiciona 30

Ao remover, o 30 será removido primeiro.

---

## 3. Crie uma pilha vazia usando uma lista em Python.

```python
pilha = []
print(pilha)
```

---

## 4. Adicione cinco elementos em uma pilha usando o método append().

```python
pilha = []

pilha.append(1)
pilha.append(2)
pilha.append(3)
pilha.append(4)
pilha.append(5)

print(pilha)
```

---

## 5. Remova o último elemento de uma pilha usando o método pop() e exiba o valor removido.

```python
pilha = [10, 20, 30]

removido = pilha.pop()

print("Elemento removido:", removido)
print("Pilha:", pilha)
```

---

## 6. Crie um programa que adicione os números 10, 20, 30 e 40 em uma pilha e depois exiba a pilha completa.

```python
pilha = []

pilha.append(10)
pilha.append(20)
pilha.append(30)
pilha.append(40)

print("Pilha completa:", pilha)
```

---

## 7. Crie um programa que remova todos os elementos de uma pilha, um por vez, mostrando cada elemento removido.

```python
pilha = [1, 2, 3, 4, 5]

while pilha:
    removido = pilha.pop()
    print("Removido:", removido)
```

---

## 8. Faça um programa que verifique se uma pilha está vazia antes de remover um elemento.

```python
pilha = []

if pilha:
    print("Elemento removido:", pilha.pop())
else:
    print("A pilha está vazia.")
```

---

## 9. Crie uma pilha com nomes de livros e mostre qual livro está no topo da pilha.

```python
livros = ["Harry Potter", "Dom Casmurro", "O Hobbit"]

print("Livro no topo:", livros[-1])
```

---

## 10. Faça um programa que leia cinco nomes digitados pelo usuário e armazene todos em uma pilha.

```python
pilha = []

for i in range(5):
    nome = input("Digite um nome: ")
    pilha.append(nome)

print("Pilha:", pilha)
```

---

## 11. Depois de armazenar cinco nomes em uma pilha, remova e exiba os nomes na ordem inversa em que foram digitados.

```python
pilha = []

for i in range(5):
    nome = input("Digite um nome: ")
    pilha.append(nome)

print("Ordem inversa:")

while pilha:
    print(pilha.pop())
```

---

## 12. Crie uma função chamada empilhar(pilha, valor) que adicione um valor na pilha.

```python
def empilhar(pilha, valor):
    pilha.append(valor)
```

---

## 13. Crie uma função chamada desempilhar(pilha) que remova e retorne o elemento do topo da pilha.

```python
def desempilhar(pilha):
    return pilha.pop()
```

---

## 14. Crie uma função chamada topo(pilha) que retorne o último elemento da pilha sem removê-lo.

```python
def topo(pilha):
    return pilha[-1]
```

---

## 15. Crie uma função chamada esta_vazia(pilha) que retorne True se a pilha estiver vazia e False caso contrário.

```python
def esta_vazia(pilha):
    return len(pilha) == 0
```

---

## 16. Faça um programa que simule uma pilha de pratos. O usuário deve poder adicionar pratos e remover o prato do topo.

```python
pilha = []

while True:
    print("\n1 - Adicionar prato")
    print("2 - Remover prato")
    print("3 - Sair")

    opcao = input("Escolha: ")

    if opcao == "1":
        prato = input("Nome do prato: ")
        pilha.append(prato)

    elif opcao == "2":
        if pilha:
            print("Prato removido:", pilha.pop())
        else:
            print("Pilha vazia.")

    elif opcao == "3":
        break
```

---

## 17. Crie um menu com as opções: empilhar, desempilhar, mostrar topo, mostrar pilha e sair.

```python
pilha = []

while True:
    print("\n1 - Empilhar")
    print("2 - Desempilhar")
    print("3 - Mostrar topo")
    print("4 - Mostrar pilha")
    print("5 - Sair")

    opcao = input("Escolha: ")

    if opcao == "1":
        valor = input("Digite um valor: ")
        pilha.append(valor)

    elif opcao == "2":
        if pilha:
            print("Removido:", pilha.pop())
        else:
            print("Pilha vazia.")

    elif opcao == "3":
        if pilha:
            print("Topo:", pilha[-1])
        else:
            print("Pilha vazia.")

    elif opcao == "4":
        print("Pilha:", pilha)

    elif opcao == "5":
        break
```

---

## 18. Use uma pilha para inverter uma palavra digitada pelo usuário.

```python
palavra = input("Digite uma palavra: ")

pilha = []

for letra in palavra:
    pilha.append(letra)

invertida = ""

while pilha:
    invertida += pilha.pop()

print("Palavra invertida:", invertida)
```

---

## 19. Crie um programa que use uma pilha para verificar se uma palavra é um palíndromo.

```python
palavra = input("Digite uma palavra: ")

pilha = []

for letra in palavra:
    pilha.append(letra)

invertida = ""

while pilha:
    invertida += pilha.pop()

if palavra == invertida:
    print("É um palíndromo.")
else:
    print("Não é um palíndromo.")
```

---

## 20. Pesquise uma situação do mundo real em que o conceito de pilha pode ser aplicado e escreva um exemplo em Python.

Um exemplo do mundo real é o recurso de desfazer (Ctrl + Z) em editores de texto. Cada ação realizada é colocada em uma pilha. Quando o usuário desfaz uma ação, a última ação realizada é removida.

```python
acoes = []

acoes.append("Escreveu texto")
acoes.append("Apagou palavra")
acoes.append("Mudou cor")

print("Última ação:", acoes.pop())
print("Ações restantes:", acoes)
```
