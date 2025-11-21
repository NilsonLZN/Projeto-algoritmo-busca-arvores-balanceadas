## Desafio de projeto

Desenvolver um algoritmo para busca em árvores balanceadas em linguagem C++.

# Rotacao Simples à Direita (LL)

### Quando ocorre?
Quando o nó está desbalanceado para a esquerda e seu filho esquerdo também está inclinado à esquerda.

### Diagrama ASCII

            y                              x
           / \                           /   \
          x   T3       →                T1    y
         / \                                 / \
       T1   T2                              T2  T3


# Rotacao Simples à Esquerda (RR)

### Quando ocorre?
Quando o nó está desbalanceado para a direita e seu filho direito também está inclinado à direita.

### Diagrama ASCII

    y                            x
   / \                          / \
  T1  x        →               y   T3
     / \                      / \
   T2  T3                   T1  T2
