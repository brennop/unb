# Conversão

## AFN → AFD

Se N = (Q, Σ, δ, q₀, F) é um *AFN*, então

> M = (Q', Σ, δ', q₀', F'), tal que

- Q' = P(Q)
- δ': Q × Σ → P(Q)
  δ'(R,a) = ∪ δ(r,a)
- q₀' = {q₀}
- F' = { R ∈ Q' | R ∩ F ≠ ∅ }

será um *AFD* equivalente

## AFD → AFN
