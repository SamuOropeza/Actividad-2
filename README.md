# Actividad 2: Snake Game - Dinámicas Aleatorias

Optimización del juego clásico "Snake" mediante la introducción de variables aleatorias tanto en el comportamiento de los objetos como en la interfaz visual.

## Registro de Cambios (Version Control)

### Push 1: Comportamiento Autónomo de la Comida
* **Movimiento Estocástico:** Actualización de la función `move()` para incluir un desplazamiento aleatorio de la comida en cada frame, validado mediante la función `inside()` para mantener la integridad de los límites del tablero.

### Push 2: Renderizado Dinámico de Colores
* **Paleta Aleatoria:** Implementación de una lista de 5 colores predefinidos. Se programó la lógica de selección inicial para que tanto el cuerpo de la serpiente como la comida reciban colores distintos de forma aleatoria en cada ejecución.
