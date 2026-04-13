Descripción del proyecto
El paquete desarrollado, puzzlebot_control, utiliza una máquina de estados finitos (FSM) para gestionar el movimiento del robot . El sistema permite realizar una trayectoria cuadrada de 2 metros por lado y navegar hacia una lista de coordenadas $(x, y)$ ingresadas dinámicamente por el usuario desde la terminal.
Características principales
Navegación interactiva: El usuario define el número de puntos y el tiempo deseado para cada trayecto.

Validación de factibilidad: El nodo estima automáticamente si el punto es alcanzable según los límites de velocidad lineal y angular del hardware .

Control auto-ajustable: El sistema calcula las velocidades y aceleraciones necesarias para cumplir con los tiempos impuestos por el usuario .

Robustez: Integración de parámetros de zona muerta y saturación de los motores para compensar no linealidades físicas.
