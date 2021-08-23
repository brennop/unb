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

### Lema 1

Se L é um LLC então L é reconhecida por um AP

#### Algorítimo:

3 estados: i (inicial), l, (leitura) e f (aceitação)

1. i, ε, ε → S$, l
2. |e, s| em regras: l, ε, e → s, l
3. |t| em terminais: l, t, t → ε, l
4. l, ε, $ → ε, f

### Lema 2

Se L é reconhecido por um AP então L é uma LLC

#### Simplificações

1. Um único estado de aceitação
  - Transições epsilon para um único estado.
2. Pilha precisa estar vazia antes de aceitar.
  - Marcador de fim de pilha
  - Loop para esvaziar a pilha
3. Cada transição empilha ou desempilha.
  - (a,b → c) ⇒ (a,b → ε), (ε,ε → c)
  - (a,ε → ε) ⇒ (a,ε → x), (ε,x → ε)

#### Regras

1. Apq -> (Apr)(Arq)
2. Apq -> a(Ast)b
3. App -> ε

Simplificações

- Remover variáveis *impossíveis*
- Remover variáveis *recursivas*
- Remover regras-ε
- Remover regras unitárias redundantes, e.g. Apq → Apq | ⋯
- Remover variáveis que não aparecem do lado esquerdo
- Remover variável inicial redundante

## Observações

- _$_: marcador de fim de pilha

[livre-do-contexto]: glc#Linguagem-da-GLC
