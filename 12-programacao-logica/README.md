# Programação Lógica

```prolog
pai(joao, maria).
pai(joao, jose).
irmao(X, Y) :- pai(Z, X), pai(Z, Y), X \= Y.
```