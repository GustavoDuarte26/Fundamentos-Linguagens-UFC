# Implementação de Subprogramas

Função recursiva:
```python
def fatorial(n):
    if n == 1:
        return 1
    return n * fatorial(n-1)
```
Pilha: fatorial(3) → fatorial(2) → fatorial(1)