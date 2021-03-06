## Determinismo *(AFD)*

- Sabemos qual é o próximo estado
- Próximo estado é único
- Cada cadeia gera uma sequência

## Não-determinismo *(AFN)*

- Podem existir ≥ 0 estados possíveis
- Todas as possibilidades são processadas em paralelo

> Um autômato *não-determinístico* M aceita uma cadeia *w* se existe um caminho
> que leva a um estado de aceitação

### Equivalência

> Para todo *AFD* existe um *AFN*
> [equivalente](automatos/regular.md#equivalente).

ver também: [fecho](fecho-epsilon)

#### Corolário

> Uma linguagem é [regular](regular) *se, e somente se* um AFN a reconhece.
