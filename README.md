# Búsqueda en Grafos: BFS y DFS

Este proyecto muestra la implementación y visualización de dos algoritmos clásicos de búsqueda en grafos:

- Breadth First Search (BFS)
- Depth First Search (DFS)

El programa permite visualizar cómo los algoritmos recorren un grafo paso a paso mediante una animación.

---

## Objetivo

El objetivo de este proyecto es comprender cómo funcionan los algoritmos de búsqueda en grafos y observar visualmente la diferencia entre:

- Búsqueda en anchura (BFS)
- Búsqueda en profundidad (DFS)

---

## Tecnologías utilizadas

El proyecto fue desarrollado utilizando:

- Python
- NetworkX (para crear el grafo)
- Matplotlib (para visualizar el grafo)
- Google Colab

---

## Funcionamiento del programa

1. Se genera un grafo representado visualmente como un árbol.
2. El usuario puede elegir un nodo objetivo para buscar.
3. El algoritmo recorre el grafo desde el nodo inicial.
4. Se muestra una animación que indica qué nodos se van visitando.
5. Cuando se encuentra el nodo objetivo, el recorrido se detiene.

---

## Algoritmos implementados

### BFS (Breadth First Search)

- Explora el grafo **por niveles**.
- Utiliza una **cola (queue)** para almacenar los nodos pendientes.
- Es útil para encontrar el **camino más corto en grafos no ponderados**.


---

### DFS (Depth First Search)

- Explora el grafo **lo más profundo posible antes de retroceder**.
- Utiliza una **pila (stack)** para almacenar los nodos pendientes.


---

## Visualización

Durante la ejecución:

- Los nodos visitados cambian de color.
- Las aristas recorridas se resaltan.
- Se muestra el progreso de la búsqueda paso a paso.

Esto permite entender visualmente cómo funciona cada algoritmo.

---

## Ejecutar el proyecto

Puedes ejecutar el notebook directamente en Google Colab:

LINK_COLAB_AQUI

---

## Autor

Cristian David García Valderrama

https://colab.research.google.com/drive/12-VqzOc6UNDKkqGnifo7V0ddimrFdvQQ?usp=sharing
