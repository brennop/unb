# Definição Formal de Computação
Seja M = (Q, Σ, δ, q0, F) um autômato finito e suponha que w = w₁w₂ · · · wₙ
seja uma cadeia onde cada wi é um membro do alfabeto Σ. Então M aceita w se
uma sequência de estados r₀, r₁, . . . , rₙ em Q existe com três condições:
1. r0 = q0,
2. δ(ri, wi+1) = ri+1,
para i = 0, . . . , n − 1, e
3. rn ∈ F.

> Uma linguagem chamada de uma ***linguagem regular*** se algum autômato finito a reconhece