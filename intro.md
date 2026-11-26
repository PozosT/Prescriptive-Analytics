# Prescriptive Analytics

Notas de clase del curso *Prescriptive Analytics* (antes Metaheurísticas), del Departamento de Ingeniería Industrial de la Universidad de los Andes. El curso trata las heurísticas y metaheurísticas como herramientas para decidir en problemas de optimización que los métodos exactos no resuelven en un tiempo razonable, sea por su tamaño, por su estructura combinatoria o porque la función objetivo sale de una simulación o de un modelo de aprendizaje de máquina.

Cada capítulo es un cuaderno de Python que presenta un método con varios ejemplos. Los ejemplos van de problemas de prueba conocidos (la función de Rosenbrock, las $n$ reinas, la mochila, el agente viajero) a problemas de ingeniería industrial (programación de producción, ruteo de vehículos, inventarios, portafolios) y a problemas de analítica (ajuste de hiperparámetros y selección de variables de un modelo predictivo).

## Organización

El capítulo 1 trata dos decisiones que preceden a cualquier metaheurística, cómo se representa una solución y cómo se mide la distancia entre dos soluciones. Los capítulos 2 y 3 presentan métodos de trayectoria, que mejoran una sola solución a lo largo de la búsqueda: el recocido simulado y la búsqueda en vecindarios grandes. Los capítulos 4 a 7 presentan métodos poblacionales: la colonia de hormigas, el enjambre de partículas, la búsqueda dispersa y los algoritmos meméticos. Los capítulos 8 a 10 salen del caso de un objetivo y una corrida, con la optimización multiobjetivo, el ajuste de los parámetros de una metaheurística y la comparación estadística entre metaheurísticas.

## Cómo usar los cuadernos

Los cuadernos están guardados con sus resultados, de modo que se pueden leer sin ejecutar nada. Para ejecutarlos, cada página tiene un botón que la abre en Google Colab. Para trabajar en un computador propio, las bibliotecas necesarias están en `requirements-curso.txt` del repositorio:

```bash
pip install -r requirements-curso.txt
```

Los ejemplos fijan la semilla de los generadores aleatorios, así que una nueva ejecución reproduce las figuras y las cifras del libro.

## Texto guía

S. Luke, *Essentials of Metaheuristics*, segunda edición, 2013.
