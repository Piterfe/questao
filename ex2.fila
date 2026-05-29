# Exercícios sobre Fila em Python

## 1. Explique com suas palavras o que é uma fila em programação.

Uma fila é uma estrutura de dados onde os elementos são adicionados no final e removidos no início. Funciona como uma fila de pessoas em um banco ou supermercado.

---

## 2. Qual é a principal regra de funcionamento de uma fila? Explique o conceito de FIFO.

A principal regra é FIFO (First In, First Out), que significa “Primeiro a Entrar, Primeiro a Sair”.

Exemplo:
- Entra 10
- Entra 20
- Entra 30

Ao remover, o 10 será removido primeiro.

---

## 3. Crie uma fila vazia usando uma lista em Python.

```python
fila = []
print(fila)
```

---

## 4. Adicione cinco elementos em uma fila usando o método append().

```python
fila = []

fila.append(1)
fila.append(2)
fila.append(3)
fila.append(4)
fila.append(5)

print(fila)
```

---

## 5. Remova o primeiro elemento de uma fila usando pop(0) e exiba o valor removido.

```python
fila = [10, 20, 30]

removido = fila.pop(0)

print("Elemento removido:", removido)
print("Fila:", fila)
```

---

## 6. Crie um programa que adicione os números 10, 20, 30 e 40 em uma fila e depois exiba a fila completa.

```python
fila = []

fila.append(10)
fila.append(20)
fila.append(30)
fila.append(40)

print("Fila completa:", fila)
```

---

## 7. Crie um programa que remova todos os elementos de uma fila, um por vez, mostrando cada elemento removido.

```python
fila = [1, 2, 3, 4, 5]

while fila:
    removido = fila.pop(0)
    print("Removido:", removido)
```

---

## 8. Faça um programa que verifique se uma fila está vazia antes de remover um elemento.

```python
fila = []

if fila:
    print("Elemento removido:", fila.pop(0))
else:
    print("A fila está vazia.")
```

---

## 9. Crie uma fila com nomes de pessoas e mostre quem é o primeiro da fila.

```python
fila = ["João", "Maria", "Carlos"]

print("Primeiro da fila:", fila[0])
```

---

## 10. Faça um programa que leia cinco nomes digitados pelo usuário e armazene todos em uma fila.

```python
fila = []

for i in range(5):
    nome = input("Digite um nome: ")
    fila.append(nome)

print("Fila:", fila)
```

---

## 11. Depois de armazenar cinco nomes em uma fila, remova e exiba os nomes na mesma ordem em que foram digitados.

```python
fila = []

for i in range(5):
    nome = input("Digite um nome: ")
    fila.append(nome)

print("Ordem da fila:")

while fila:
    print(fila.pop(0))
```

---

## 12. Crie uma função chamada enfileirar(fila, valor) que adicione um valor ao final da fila.

```python
def enfileirar(fila, valor):
    fila.append(valor)
```

---

## 13. Crie uma função chamada desenfileirar(fila) que remova e retorne o primeiro elemento da fila.

```python
def desenfileirar(fila):
    return fila.pop(0)
```

---

## 14. Crie uma função chamada primeiro(fila) que retorne o primeiro elemento da fila sem removê-lo.

```python
def primeiro(fila):
    return fila[0]
```

---

## 15. Crie uma função chamada esta_vazia(fila) que retorne True se a fila estiver vazia e False caso contrário.

```python
def esta_vazia(fila):
    return len(fila) == 0
```

---

## 16. Faça um programa que simule uma fila de atendimento. O usuário deve poder adicionar pessoas e atender a primeira pessoa da fila.

```python
fila = []

while True:
    print("\n1 - Adicionar pessoa")
    print("2 - Atender pessoa")
    print("3 - Sair")

    opcao = input("Escolha: ")

    if opcao == "1":
        nome = input("Nome da pessoa: ")
        fila.append(nome)

    elif opcao == "2":
        if fila:
            print("Pessoa atendida:", fila.pop(0))
        else:
            print("Fila vazia.")

    elif opcao == "3":
        break
```

---

## 17. Crie um menu com as opções: enfileirar, desenfileirar, mostrar primeiro, mostrar fila e sair.

```python
fila = []

while True:
    print("\n1 - Enfileirar")
    print("2 - Desenfileirar")
    print("3 - Mostrar primeiro")
    print("4 - Mostrar fila")
    print("5 - Sair")

    opcao = input("Escolha: ")

    if opcao == "1":
        valor = input("Digite um valor: ")
        fila.append(valor)

    elif opcao == "2":
        if fila:
            print("Removido:", fila.pop(0))
        else:
            print("Fila vazia.")

    elif opcao == "3":
        if fila:
            print("Primeiro:", fila[0])
        else:
            print("Fila vazia.")

    elif opcao == "4":
        print("Fila:", fila)

    elif opcao == "5":
        break
```

---

## 18. Use uma fila para organizar a ordem de impressão de documentos digitados pelo usuário.

```python
fila = []

for i in range(3):
    documento = input("Digite o nome do documento: ")
    fila.append(documento)

print("\nOrdem de impressão:")

while fila:
    print("Imprimindo:", fila.pop(0))
```

---

## 19. Crie um programa que simule uma fila de senhas de atendimento, exibindo a senha chamada a cada atendimento.

```python
fila = ["A001", "A002", "A003", "A004"]

while fila:
    print("Chamando senha:", fila.pop(0))
```

---

## 20. Pesquise uma situação do mundo real em que o conceito de fila pode ser aplicado e escreva um exemplo em Python.

Um exemplo do mundo real é a fila de atendimento em um hospital. O primeiro paciente que chega é o primeiro a ser atendido.

```python
fila_pacientes = []

fila_pacientes.append("Pedro")
fila_pacientes.append("Maria")
fila_pacientes.append("João")

print("Paciente atendido:", fila_pacientes.pop(0))
print("Fila restante:", fila_pacientes)
```
