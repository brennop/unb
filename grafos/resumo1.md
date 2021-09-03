# Resumo P1

## Matriz de Adjacência

|     | A   | B   | C   |
| --- | --- | --- | --- |
| A   | 0   | 1   | 0   |
| B   | 1   | 0   | 1   |
| C   | 0   | 1   | 0   |

## Matriz de incidência

|     | A   | B   | C   |
| --- | --- | --- | --- |
| α   | 1   | 1   | 0   |
| β   | 0   | 1   | 1   |

## Componente Forte

> Um componente forte é um conjunto maximal de vértices fortemente conectados.

## Kosajaru-Sharir

1. Inverter o grafo
2. Computar a *pós-ordem*: DFS, toda vez que ocorrer backtracking, adiciona ao
   **início** da lista
3. DFS no grafo original, seguindo a pós-ordem

> Dica: faz um árvore, e vai subindo a partir das folhas
