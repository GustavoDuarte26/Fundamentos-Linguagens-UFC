# Concorrência

```python
import threading

def tarefa():
    print("Executando")

thread = threading.Thread(target=tarefa)
thread.start()
```

**Threads** são leves, **processos** são isolados.