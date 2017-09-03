# ¿Qué son las Listas?

Una lista es una tupla, a diferencia de que esta puede ser modificada. Estas se definen de la siguiente manera

```python
mi_lista = ['hola’, 15, 2.8, 'mundo', 25]
```

_En una lista se puede guardar números enteros, decimales, cadenas y demás tipos de datos_

A los elementos de esta se puede acceder por medio de su posición de igual manera y el contenido puede ser modificado de la siguiente manera

```python
mi_lista[posicion] = cambio
```

También es posible agregar o eliminar valores de la lista de la siguiente manera

```python
mi_lista.append(dato) # Agregar al final de la lista
mi_lista.insert(posición,dato) # Agregar en una posición de la lista
mi_lista.pop() # Eliminar el último elemento de una lista
mi_lista.pop(posicion) # Eliminar el elemento en una posición de la lista
mi_lista.remove(dato) # Eliminar el elemento “dato"
```

## Ejercicio : 

Crear la lista mis_numeros con los valores 1 12 0 10 3 , acceder desde la posición 2 a la 4 , eliminar el valor 12 de la lista y agregar en esta misma posición el valor 100
