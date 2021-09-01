# Operações

Operações sobre [linguagens].

|              | Definição                          | Regular | LR  | LLC |
| ------------ | ---------------------------------- | :-----: | :-: | :-: |
| União        | A ∪ B = { x / x ∈ A ∨ x ∈ B }      |   ✅    | ✅  | ✅  |
| Concatenação | A ○ B = { xy / x ∈ A ∧ x ∈ B }     |   ✅    | ✅  | ✅  |
| Estrela      | A∗ = { x₁x₂...xₖ / k ≥ 0 ∧ xᵢ∈ A } |   ✅    | ❌  | ✅  |
| Intersecção  |
| Complemento  |
| Reverso      | REV(L) = { Я / R ∈ L }             |   ❌    | ❓  | ✅  |

- Se a linguagem A é regular, então seu complemento é livre-do-contexto
