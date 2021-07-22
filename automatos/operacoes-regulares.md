# Operações Regulares

Operações sobre linguagens. ([[definicoes#Linguagem]])

## União

> A ∪ B = { x | x ∊ A ou x ∊ B }

- A classe das linguagens regulares ([[computacao#Linguagem Regular]]) é fechada sobre a operação de união.

## Concatenação

> A ○ B = { xy | x ∊ A e x ∊ B }

- A classe das linguagens regulares ([[computacao#Linguagem Regular]]) é fechada sobre a operação de concatenação.

## Estrela

>  $A^* = \{ x_1x_2...x_k | k \geq 0 \land x_i \in A \}$

- Concatena as cadeias de A das infinitas maneiras possíveis, incluido ε.