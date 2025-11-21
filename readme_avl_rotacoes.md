# Rotacoes AVL — LL e RR

Este repositório contém implementacoes completas em **C++** demonstrando as rotacoes fundamentais da arvore AVL:

- **Rotacao Simples à Direita (LL)**
- **Rotacao Simples à Esquerda (RR)**

Cada operacao possui:
- Diagrama ASCII explicativo
- Codigo completo em C++
- Explicacao da logica
- Função `main()` para demonstracao

---

## 📌 O que é uma Rotacao em AVL?
As arvores AVL sao arvores binarias de busca **autobalanceadas**. Sempre que uma insercao deixa uma subarvore mais alta que a outra em **2 niveis de diferenca**, é necessário aplicar uma rotacao para restaurar o equilibrio.

Existem **4 tipos de rotacoes**:
- LL — Simples à Direita
- RR — Simples à Esquerda
- LR — Dupla Esquerda-Direita
- RL — Dupla Direita-Esquerda

Neste projeto, voce encontra **LL** e **RR** separadas por arquivos.

---

# 🔄 1. Rotacao Simples à Direita (LL)

### 📘 Quando ocorre?
Quando o **nó está desbalanceado para a esquerda** e seu filho esquerdo também está inclinado à esquerda.

### 📐 Diagrama ASCII
```
            y                              x
           / \                           /   \
          x   T3       →                T1    y
         / \                                 / \
       T1   T2                              T2  T3
```

### 📎 Arquivo
**LL_ROTATION.cpp**

---

# 🔄 2. Rotacao Simples à Esquerda (RR)

### 📘 Quando ocorre?
Quando o **nó está desbalanceado para a direita** e seu filho direito também está inclinado à direita.

### 📐 Diagrama ASCII
```
    y                            x
   / \                          / \
  T1  x        →               y   T3
     / \                      / \
   T2  T3                   T1  T2
```

### 📎 Arquivo
**RR_ROTATION.cpp**

---

# ▶️ Como compilar
Para compilar pelo terminal:

```
g++ LL_ROTATION.cpp -o LL
./LL

g++ RR_ROTATION.cpp -o RR
./RR
```

---

# 🧪 Exemplo de Saída
### Para LL:
```
=== Rotacao Simples à Direita (LL) ===
Pre-ordem antes da rotacao: 30 20 10
Pre-ordem depois da rotacao: 20 10 30
```

### Para RR:
```
=== Rotacao Simples à Esquerda (RR) ===
Pre-ordem antes da rotacao: 10 20 30
Pre-ordem depois da rotacao: 20 10 30
```

---

# 📚 Sobre
Este material é ideal para estudantes de:
- Estruturas de Dados
- Algoritmos
- Arvores balanceadas
- Preparacao para concursos e entrevistas técnicas

Se quiser, posso gerar também:
- Rotacoes duplas LR e RL
- Um arquivo completo com Arvore AVL funcional
- Diagramas SVG para o README
- Versao do projeto em Java ou Python

Só pedir! 🚀

