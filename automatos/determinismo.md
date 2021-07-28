## Determinismo *(AFD)*

- Sabemos qual é o próximo estado
- Próximo estado é único
- Cada cadeia gera uma sequência

## Não-determinismo *(AFN)*

- Podem existir ≥ 0 estados possíveis
- Todas as possibilidades são processadas em paralelo

> Um autômato *não-determinístico* M aceita uma cadeia *w* se existe um caminho que leva a um estado de aceitação

### Função de transição 

> $\delta: \Sigma_\epsilon \times Q \rightarrow P(Q)$ 

### Teorema

Para todo *AFD* existe um *AFN* [equivalente][1].

[1]: [[computacao#Equivalência]]