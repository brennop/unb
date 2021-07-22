# Grafos

Um grafo G é uma tripla ordenada *(V(G), E(G), w)* onde

1. V(G) é um conjunto de vértices
2. E(G) é um conjunto de [arestas]
3. w: E -> V² é uma função que associa cada aresta um par ordenado de vértices

## Terminologias

- Um grafo sem arestas é um **grafo vazio**
- Um grafo sem vértices é um **grafo nulo**
- Um grafo com somente um vértice é **trivial**
- Um grafo é finito se ambos V e E são **finitos**
- Arestas são **adjacentes** se elas compartilham um mesmo vértice terminal
- Arestas são **paralelas** se possuem os mesmos vértices terminais
- Uma aresta da forma *(v, v)* é um **laço** ➰
- Um grafo é simples se não possui **laços** sem **arestas paralelas**
- O **grau** de um vértice *d(v)* é o número de arestas com v sendo terminal