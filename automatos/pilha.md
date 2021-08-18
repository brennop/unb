# Autômatos com Pilha (_AP_)

## Definição

Um autômato com pilha é uma 6-upla (Q, Σ, Γ, δ, q₀, F), onde

1. Q: conjunto de estados,
2. Σ: alfabeto de entrada,
3. Γ: Alfabeto de pilha,
4. δ: Q × Σ × Γ → P(Q × Γ) é a função de transição,
5. q₀ ∈ Q é o estado inicial, e
6. F ⊆ Q é o conjunto de estados de aceitação.

## Equivalência

> Uma linguagem é [livre-do-contexto] ⇔ um autômato com pilha a reconhece

3 estados: i (inicial), l, (leitura) e f (aceitação)

1. i, ε, ε → S$, l
2. |e, s| em regras: l, ε, e → s, l
3. |t| em terminais: l, t, t → ε, l
4. l, ε, $ → ε, f

## Observações

- _$_: marcador de fim de pilha

[livre-do-contexto]: glc#Linguagem-da-GLC
