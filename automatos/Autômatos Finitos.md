# Autômatos Finitos
- Simples
- Memória Limitada

## Definição

Um autômato finito é uma 5-upla (Q, Σ, δ, q₀, F), onde

1. Q é um conjunto finito denominado os estados,
2. Σ é um conjunto finito denominado o alfabeto,
3. δ: Q × Σ → Q é a funcão de transição
4. q₀ ∈ Q é o estado inicial, e
5. F ⊆ Q é o conjunto de estados de aceitação.

## Linguagem de M
Se A é o conjunto de todas as cadeias que a máquina *M* aceita, dizemos que 

> *A* é a *linguagem da máquina* *M*,

ou então

> *M* reconhece *A*.

### Observações
- Usamos o termo *aceita* para cadeias e *reconhece* para linguagens. 
- **Uma máquina pode aceitar várias cadeias, mas ela sempre reconhece somente uma linguagem**. 
- Se uma máquina não aceita nenhuma linguagem, ela reconhece a linguagem vazia ∅.