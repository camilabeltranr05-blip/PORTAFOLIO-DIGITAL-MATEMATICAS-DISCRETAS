<div align="center">
  
# UNIDAD 3

</div>


## Resumen de la Unidad 3: 
<br>

# TEORÍA DE GRAFOS Y ÁRBOLES: OPTIMIZACIÓN Y ESTRUCTURAS DE DATOS

Este apartado aborda el estudio de las estructuras de datos no lineales, fundamentales para el modelado de redes, la organización jerárquica de la información y la optimización de recursos en la ingeniería de computación.

---

## 1. Teoría de Grafos y Optimización
Un **grafo** es una estructura matemática representada como $G = (V, E)$, donde $V$ es el conjunto de **vértices** (o nodos) y $E$ es el conjunto de **aristas** (o enlaces). Permite modelar desde redes sociales hasta infraestructuras complejas de transporte.

### Clasificación y Circuitos
* **Direccionalidad:**
  * **No dirigidos:** Relaciones simétricas (flujo bidireccional).
  * **Dirigidos (Dígrafos):** Relaciones asimétricas con un sentido específico.
* **Circuitos Especiales:**
  * **Circuito de Euler:** Recorre cada **arista** del grafo exactamente una vez.
  * **Circuito de Hamilton:** Visita cada **vértice** del grafo exactamente una vez.

### Representación Computacional
Para que una computadora procese un grafo de forma eficiente, se emplean principalmente dos estructuras:

| Representación | Ventaja Principal | Caso de Uso Ideal |
| :--- | :--- | :--- |
| **Matriz de Adyacencia** | Búsquedas ultra rápidas de conexiones ($O(1)$). | Grafos densos (muchas conexiones). |
| **Matriz/Lista de Incidencia** | Alta eficiencia en el uso de memoria. | Grafos dispersos (pocas conexiones). |

### Algoritmos de Ruta
* **Algoritmo de Dijkstra:** Es el estándar de oro para encontrar la trayectoria más corta entre un nodo origen y los demás nodos en grafos con aristas ponderadas, minimizando costos, distancias o tiempos de viaje.

---

## 2. Teoría de Árboles y Estructuras de Datos
Un **árbol** es un caso especial de grafo que se define por ser **conexo** y **acíclico** (sin bucles). En esta estructura, existe un único camino posible entre cualquier par de vértices.

### Propiedades y Tipos de Árboles
* **Fórmula de Aristas:** Para cualquier árbol con $n$ vértices, siempre existirá un total exacto de $n - 1$ aristas.
* **Árbol de Búsqueda Binaria (BST):** Organiza los datos de manera que los elementos menores que la raíz van a la izquierda y los mayores a la derecha.
* **Árbol AVL:** Es un BST auto-balanceado que ajusta su altura de forma dinámica tras inserciones o eliminaciones para garantizar tiempos de búsqueda óptimos de $O(\log n)$.

### Recorridos Algorítmicos
Para procesar o recorrer la información dentro de un árbol binario, se emplean tres métodos sistemáticos:

* **Preorden** (Raíz $\rightarrow$ Izquierda $\rightarrow$ Derecha): Útil para clonar o duplicar la estructura del árbol.
* **Inorden** (Izquierda $\rightarrow$ Raíz $\rightarrow$ Derecha): Devuelve los elementos en orden ascendente al aplicarse sobre un BST.
* **Postorden** (Izquierda $\rightarrow$ Derecha $\rightarrow$ Raíz): Esencial para evaluar expresiones matemáticas (notación polaca inversa) y para liberar la memoria del árbol de manera segura.

---

## 3. Integración Práctica y Aplicaciones en Computación

Ambas teorías constituyen los pilares del software moderno y de la resolución de problemas reales:

### Búsquedas Algorítmicas
* **BFS (Búsqueda en Anchura):** Explora nivel por nivel. Es ideal para encontrar el camino más corto en grafos no ponderados y en el enrutamiento de paquetes de red.
* **DFS (Búsqueda en Profundidad):** Explora mediante ramas completas antes de retroceder. Es clave para la resolución de dependencias en compiladores y detección de ciclos.

### Tecnologías del Mundo Real
* **Heaps (Montículos):** Estructuras base para implementar colas de prioridad eficientes.
* **Tries:** Árboles de prefijos utilizados para el autocompletado rápido de texto.
* **Árboles B+:** Estructura estándar para los índices en los motores de bases de datos relacionales.
* **Árboles de Decisión:** Modelos fundamentales en Inteligencia Artificial para el aprendizaje supervisado.

### Impacto Social y Sostenibilidad
* **Reducción de la Brecha Digital:** Aplicación práctica de algoritmos de **Árboles de Expansión Mínima (MST)**, como Prim o Kruskal, para optimizar el tendido de fibra óptica en zonas rurales (como en la provincia de Loja, Ecuador), minimizando los costos de infraestructura física y el impacto ecológico.

<br><br>

## A continuación, se presentan los enlaces a las actividades de la unidad: 
<br>

## ACTIVIDADES PRÁCTICO EXPERIMENTALES (APE)<br> 
* **Enlace de Google Drive:** [Haz clic aquí para ver el documento](https://drive.google.com/drive/folders/1stx0Y-O-yLCNfY6ujpNyge6ts1VFFK2z)

## APRENDIZAJE EN CONTACTO CON EL DOCENTE (ACD)<br> 
* **Enlace de Google Drive:** [Haz clic aquí para ver el documento](https://drive.google.com/drive/folders/1MxVnQG94dcK_Iw9YorWVDJuIdkMoIk_n)

## ACTIVIDADES AUTÓNOMAS (AA) <br> 
* **Enlace de Google Drive:** [Haz clic aquí para ver el documento](https://drive.google.com/drive/folders/1oCR4Lcp1h6Y7rt_bMEL3KtLoAS-G223U)
  
## EVALUACIÓN SUMATIVA (ES) <br> 
* **Enlace de Google Drive:** [Haz clic aquí para ver el documento](https://drive.google.com/drive/folders/1x8i_7w8NZzt1TlaJbzFlSgSG1KgdjQi1)

<div align="center">
  
## 
<a href="https://github.com/camilabeltranr05-blip/PORTAFOLIO-DIGITAL-MATEMATICAS-DISCRETAS/blob/main/README.md" target="_blank"><img src="https://img.shields.io/badge/REGRESAR-000000?style=for-the-badge" alt="Regresar"></a>
</div>
