# Projetos Python - Daniel Borborema

Conjunto de exercícios em Python para prática de lógica de programação.

## Arquivos

### `debug.py`
Sistema de cálculo de pedido com imposto e desconto.

**Funcionalidades:**
- Entrada de dados do cliente e 3 itens
- Cálculo de subtotal, imposto (10%) e desconto via cupom
- Exibição formatada do recibo

**Como executar:**
```bash
python debug.py
```

---

### `num_primos.py`
Módulo para verificação de números primos.

**Função principal:**
- `is_prime(n: int) -> bool` — Retorna `True` se o número é primo

**Funções auxiliares (privadas):**
- `_is_below_minimum(n)` — Verifica se n < 2
- `_is_even(n)` — Verifica se n é par
- `_has_odd_divisor(n)` — Verifica divisores ímpares

**Como usar:**
```python
from num_primos import is_prime

print(is_prime(7))   # True
print(is_prime(10))  # False
```

---

### `refatoracao.py`
Função para cálculo de estatísticas de uma lista de números.

**Função:**
- `calculate_list_statistics(numbers: list[float]) -> tuple[float, float, float, float]`
- Retorna: total, média, máximo e mínimo

**Como usar:**
```python
from refatoracao import calculate_list_statistics

numeros = [23, 7, 45, 2, 67, 12, 89, 34, 56, 11]
total, media, maximo, minimo = calculate_list_statistics(numeros)
```

---

## Requisitos

- Python 3.8+

## Licença

MIT
