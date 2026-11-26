# Prescriptive Analytics

Notas de clase del curso *Prescriptive Analytics* (antes Metaheurísticas), del Departamento de Ingeniería Industrial de la Universidad de los Andes. El curso trata las heurísticas y metaheurísticas como herramientas para decidir en problemas de optimización que los métodos exactos no resuelven en un tiempo razonable, sea por su tamaño, por su estructura combinatoria o porque la función objetivo sale de una simulación o de un modelo de aprendizaje de máquina.

Cada capítulo es un cuaderno de Python que presenta un método con varios ejemplos. Los ejemplos van de problemas de prueba conocidos (la función de Rosenbrock, las $n$ reinas, la mochila, el agente viajero) a problemas de ingeniería industrial (programación de producción, ruteo de vehículos, inventarios, portafolios) y a problemas de analítica (ajuste de hiperparámetros y selección de variables de un modelo predictivo).

## Organización

El capítulo 1 presenta los problemas de optimización combinatoria, los tres problemas que sirven de ejemplo a lo largo del libro (la mochila, las $n$ reinas y el agente viajero) y la razón por la que hacen falta métodos aproximados. Los capítulos 2 a 4 tratan las bases comunes a las metaheurísticas: la representación de las soluciones y las distancias entre ellas, las heurísticas constructivas y la búsqueda local con su límite, el óptimo local, y las primeras estrategias para salir de él. Los capítulos 5 a 8 presentan métodos de trayectoria, que mejoran una sola solución a lo largo de la búsqueda: la búsqueda tabú, la búsqueda de vecindad variable, el recocido simulado y la búsqueda en vecindarios grandes. Los capítulos 9 a 13 presentan métodos poblacionales: los algoritmos genéticos, la colonia de hormigas, el enjambre de partículas, la búsqueda dispersa y los algoritmos meméticos. Los capítulos 14 a 16 salen del caso de un objetivo y una corrida, con la optimización multiobjetivo, el ajuste de los parámetros de una metaheurística y la comparación estadística entre metaheurísticas.

## Cómo usar los cuadernos

Los cuadernos están guardados con sus resultados, de modo que se pueden leer sin ejecutar nada. Para ejecutarlos, cada página tiene un botón que la abre en Google Colab. Para trabajar en un computador propio, las bibliotecas necesarias están en `requirements-curso.txt` del repositorio:

```bash
pip install -r requirements-curso.txt
```

Los ejemplos fijan la semilla de los generadores aleatorios, así que una nueva ejecución reproduce las figuras y las cifras del libro.

## Texto guía

S. Luke, *Essentials of Metaheuristics*, segunda edición, 2013.
