#cap2

# Gramáticas Livres-do-Contexto

> Uma gramática livre-do-contexto é uma 4-upla (V, Σ, R, S), onde
> 
> 1. V é um conjunto finito denominado de as *variáveis*,
> 2. Σ é um conjunto finito, disjunto de V , denominado de os *terminais*,
> 3. R é um conjunto finito de *regras de transição*
> 4. S ∈ V é a *variável inicial*

## Linguagem da GLC

> L(G) = {w | w ∈ Σ∗ e S ∗⇒ w}

Ou seja, todas as cadeias que compostas por *terminais* que podemos obter a
partir de *derivações* da *variável inicial*.

- *Pode ser vazia*
- Uma linguagem é livre-do-contexto ⇔ um [autômato com pilha] a reconhece

## Linguagem livre-do-contexto (LLC)

Aquela gerada por uma GLC.

- ∅ é uma LLC
- Linguagens Regulares ⊂ LLC


