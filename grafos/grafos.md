# Grafos

> Um grafo G é uma tripla ordenada *(V(G), E(G), w)* onde
> 
> 1. V(G) é um conjunto de vértices
> 2. E(G) é um conjunto de [arestas]
> 3. w: E -> V² é uma função que associa cada aresta um par ordenado de vértices

## Terminologias

- Um grafo sem arestas é um **grafo vazio**
- Um grafo sem vértices é um **grafo nulo**
- Um grafo com somente um vértice é **trivial**
- Um grafo é finito se ambos V e E são **finitos**

- Arestas são **adjacentes** se elas compartilham um mesmo vértice terminal
- Arestas são **paralelas** se possuem os mesmos vértices terminais
- Uma aresta da forma *(v, v)* é um **laço** ➰
- Um grafo é **simples** se não possui *laços* sem *arestas paralelas*

- O **grau** de um vértice *d(v)* é o número de arestas com v sendo terminal
- Um grafo G é **regular** se todos os vértices de G tiverem o mesmo grau. Se o grau for r, então G será *regular de grau r*.

- Um grafo *simples* com todas as arestas possíveis é um grafo completo: $K_n$

## Subgrafo

> Um grafo $G_1=(V_1, E_1)$ é subgrafo de $G_2=(V_2, E_2)$
>
> - $V_1 \subseteq V_2$
> - toda aresta de $G_2$ é uma aresta de $G_1$

- Todo grafo é subgrafo dele mesmo
- Um vértice de G é um subgrafo de G
- Uma aresta de G com seus vértices é um subgrafo de G