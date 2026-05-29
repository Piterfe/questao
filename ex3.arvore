# Exercícios sobre Árvores em Estrutura de Dados

## 1. Explique com suas palavras o que é uma árvore em estrutura de dados.

Uma árvore é uma estrutura de dados organizada de forma hierárquica. Ela é formada por nós conectados entre si, semelhante a uma árvore genealógica.

---

## 2. O que é o nó raiz de uma árvore? Dê um exemplo.

O nó raiz é o primeiro nó da árvore, de onde todos os outros nós se originam.

Exemplo:

```text
       A
      / \
     B   C
```

O nó raiz é o A.

---

## 3. Explique o que são nós filhos em uma árvore.

Nós filhos são os nós que estão ligados abaixo de outro nó.

Exemplo:

```text
       A
      / \
     B   C
```

B e C são filhos de A.

---

## 4. Explique o que é um nó folha em uma árvore.

Um nó folha é um nó que não possui filhos.

Exemplo:

```text
       A
      / \
     B   C
```

B e C são nós folha.

---

## 5. Qual é a diferença entre uma árvore e uma lista?

A lista organiza elementos em sequência linear, enquanto a árvore organiza os dados de forma hierárquica.

---

## 6. Crie uma representação simples de uma árvore usando dicionários em Python.

```python
arvore = {
    "A": ["B", "C"],
    "B": ["D", "E"],
    "C": []
}

print(arvore)
```

---

## 7. Crie uma árvore com um nó raiz e dois filhos, depois exiba todos os valores.

```python
arvore = {
    "raiz": {
        "esquerda": "Filho 1",
        "direita": "Filho 2"
    }
}

print("Raiz:", "raiz")
print("Filho esquerdo:", arvore["raiz"]["esquerda"])
print("Filho direito:", arvore["raiz"]["direita"])
```

---

## 8. Crie uma árvore que represente uma família com avô, filhos e netos.

```python
familia = {
    "Avô": {
        "Filho 1": ["Neto 1", "Neto 2"],
        "Filho 2": ["Neto 3"]
    }
}

print(familia)
```

---

## 9. Explique o que é uma árvore binária.

Uma árvore binária é uma árvore em que cada nó pode ter no máximo dois filhos: um filho à esquerda e outro à direita.

---

## 10. Crie uma árvore binária simples usando uma classe No em Python.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None

raiz = No(10)
raiz.esquerda = No(5)
raiz.direita = No(20)

print(raiz.valor)
```

---

## 11. Crie uma classe No com os atributos valor, esquerda e direita.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None
```

---

## 12. Insira valores manualmente em uma árvore binária e exiba o valor da raiz.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None

raiz = No(50)
raiz.esquerda = No(30)
raiz.direita = No(70)

print("Valor da raiz:", raiz.valor)
```

---

## 13. Exiba o filho esquerdo e o filho direito da raiz de uma árvore binária.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None

raiz = No(100)
raiz.esquerda = No(50)
raiz.direita = No(150)

print("Filho esquerdo:", raiz.esquerda.valor)
print("Filho direito:", raiz.direita.valor)
```

---

## 14. Explique o que significa percorrer uma árvore.

Percorrer uma árvore significa visitar todos os nós da árvore seguindo uma determinada ordem.

---

## 15. Pesquise e explique o percurso em pré-ordem.

No percurso em pré-ordem, o nó raiz é visitado primeiro, depois a subárvore esquerda e por último a subárvore direita.

Ordem:
1. Raiz
2. Esquerda
3. Direita

---

## 16. Pesquise e explique o percurso em ordem.

No percurso em ordem, primeiro é visitada a subárvore esquerda, depois a raiz e por último a subárvore direita.

Ordem:
1. Esquerda
2. Raiz
3. Direita

---

## 17. Pesquise e explique o percurso em pós-ordem.

No percurso em pós-ordem, primeiro é visitada a subárvore esquerda, depois a subárvore direita e por último a raiz.

Ordem:
1. Esquerda
2. Direita
3. Raiz

---

## 18. Faça um programa que conte quantos nós existem em uma árvore binária.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None

def contar_nos(no):
    if no is None:
        return 0

    return 1 + contar_nos(no.esquerda) + contar_nos(no.direita)

raiz = No(10)
raiz.esquerda = No(5)
raiz.direita = No(20)

print("Quantidade de nós:", contar_nos(raiz))
```

---

## 19. Faça um programa que calcule a altura de uma árvore binária.

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.esquerda = None
        self.direita = None

def altura(no):
    if no is None:
        return 0

    esquerda = altura(no.esquerda)
    direita = altura(no.direita)

    return 1 + max(esquerda, direita)

raiz = No(10)
raiz.esquerda = No(5)
raiz.direita = No(20)
raiz.esquerda.esquerda = No(2)

print("Altura da árvore:", altura(raiz))
```

---

## 20. Pesquise uma situação do mundo real em que o conceito de árvore pode ser aplicado e escreva um exemplo em Python.

Um exemplo do mundo real é a estrutura de pastas de um computador. Cada pasta pode conter outras pastas e arquivos.

```python
pastas = {
    "Documentos": {
        "Faculdade": {
            "Trabalhos": []
        },
        "Fotos": []
    }
}

print(pastas)
```
