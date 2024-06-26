# Documentación de Funciones

## Función Euler

```python
def euler(f, x0, y0, h):
    """
    Calcula el siguiente paso de y usando el método de Euler.

    Args:
        f: La función derivada de y respecto a x.
        x0: Valor inicial de x.
        y0: Valor inicial de y.
        h: Tamaño del paso.

    Returns:
        El nuevo valor de y.
    """
    return y0 + h * f(x0, y0)
