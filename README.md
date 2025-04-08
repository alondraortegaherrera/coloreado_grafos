# coloreado_grafos

# Coloreado de Grafos con Algoritmos Genéticos y Recocido Simulado

Este proyecto resuelve el problema de coloreado de grafos utilizando recocido simulado. El objetivo es encontrar una asignación de colores para los vértices de un grafo de manera que no haya dos vértices adyacentes con el mismo color, utilizando técnicas de optimización.

## Descripción

El coloreado de grafos es un problema clásico en teoría de grafos y optimización combinatoria. En este proyecto, utilizamos dos algoritmos de optimización:
- **Recocido Simulado**: Un algoritmo probabilístico para aproximarse a la solución óptima.
- **Algoritmo Genético**: Un enfoque basado en la evolución natural para encontrar una solución óptima.

El código genera grafos aleatorios y luego aplica estos algoritmos para encontrar una solución al problema de coloreado. Además, se comparan los resultados obtenidos por ambos algoritmos.

## Requisitos

Este proyecto utiliza Python y las siguientes bibliotecas:
- `networkx`: Para la creación y manipulación de grafos.
- `matplotlib`: Para visualizar los resultados de los grafos coloreados.
- `numpy`: Para realizar cálculos numéricos.
- `random`: Para la generación de secuencias aleatorias en el recocido simulado.

Si deseas ejecutar el código localmente, puedes instalar las dependencias con:

# Coloreado de Grafos con Recocido Simulado

Este proyecto resuelve el problema de coloreado de grafos utilizando el algoritmo de **recocido simulado**. El objetivo es encontrar una asignación de colores para los vértices de un grafo de manera que no haya dos vértices adyacentes con el mismo color, mediante una técnica de optimización probabilística.

## Descripción

El **coloreado de grafos** es un problema clásico en teoría de grafos y optimización combinatoria, donde se busca asignar colores a los vértices de un grafo de manera que no haya dos vértices adyacentes con el mismo color, utilizando el menor número posible de colores.

En este proyecto, se utiliza el algoritmo de **recocido simulado** para encontrar una solución aproximada a este problema. El recocido simulado es un algoritmo de optimización probabilística inspirado en el proceso físico de recocido, donde se busca minimizar el costo de una función a través de pequeñas variaciones controladas.

## Enfoque

- **Recocido Simulado**: Este algoritmo comienza con una solución aleatoria y la va mejorando iterativamente mediante pequeños cambios, aceptando soluciones peores con una probabilidad que disminuye a medida que avanza el tiempo de ejecución.
  
  El objetivo del algoritmo es minimizar el número de "colisiones", es decir, los casos en los que dos vértices adyacentes tienen el mismo color.

## Funcionalidad

1. **Generación de grafos aleatorios**: Se crean grafos con un número determinado de vértices y aristas, con grados de vértices también aleatorios.
   
2. **Aplicación del recocido simulado**: Se aplica el recocido simulado para encontrar una asignación de colores válida para el grafo generado. El proceso incluye:
   - Generación de soluciones iniciales aleatorias.
   - Evaluación de la calidad de cada solución (número de colisiones).
   - Aceptación de soluciones peores con una probabilidad determinada, que disminuye a lo largo de las iteraciones.

3. **Visualización**: Se utiliza `matplotlib` para representar visualmente el grafo coloreado, mostrando los vértices con sus respectivos colores.

## Requisitos

Este proyecto utiliza Python y las siguientes bibliotecas:
- `networkx`: Para la creación y manipulación de grafos.
- `matplotlib`: Para visualizar los resultados de los grafos coloreados.
- `numpy`: Para realizar cálculos numéricos.
- `random`: Para la generación de secuencias aleatorias en el recocido simulado.
