#TODO

# Gramáticas

## Gramáticas Regulares *(tipo 3)*

- Linear à direita

A → uB
A → u

- Linear à esquerda

A → Bu
A → u

Onde A,B ∈ V, u ∈ Σ∗

## Gramáticas Livres-do-Contexto *(tipo 2)*

> A → u, 

u ∈ (Σ ∪ V)∗

## Gramáticas Sensíveis-ao-Contexto *(tipo 1)*

> αAβ → αγβ,

Onde A ∈ V, α, β, γ ∈ (Σ ∪ V)∗

- Podemos substituir A por γ se A está entre α e β (o *contexto*)

## Gramáticas irrestritas *(tipo 0)*

> α → β

Onde, α, β ∈ (Σ ∪ V)∗, α ≠ ε

- Classe de linguagens Turing-reconhcíveis

## Hierarquia de Chomksy

Irrestritas > Sensíveis > Livres > Regulares
