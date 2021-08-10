# Operações Regulares

Operações sobre [linguagens].

## União

> A ∪ B = { x | x ∈ A ∨ x ∈ B }

- A classe das [linguagens regulares] é fechada sobre a operação de união.

## Concatenação

> A ○ B = { xy | x ∈ A ∧ x ∈ B }

- A classe das [linguagens regulares] é fechada sobre a operação de concatenação.

## Estrela

>  A\* = { x₁x₂...xₖ | k ≥ 0 ∧ xᵢ∈ A }

- Concatena as cadeias de A das infinitas maneiras possíveis, incluindo ε.

[linguagens]: definicoes.md#linguagem
[linguagens regulares]: regular.md 
