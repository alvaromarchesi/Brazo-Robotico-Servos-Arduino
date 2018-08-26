# Brazo-Robotico-Servos-Arduino

Este proyecto construye y controla un brazo robotico de 6 grados de libertad manejado con un arduino nano.

Los servos se manejan con potenciómetros que indican el grado de avance de cada servos. Los angulos se encuentran limitados.

Para la construcción se anadió un contrapeso para que los motores pudieran con el brazo, principalmente el del codo.

IDEAS pendientes:
- Distribuir las potencias de los motores de manera diferente, más potentes hoombro y codo y menos los de muñeca y pinza, que a su vez deben de pesar menos.
- Mejorar el código de lectura de los potenciómetros de manera que los movimientos sean menos bruscos.
- Incluir más opciones del tipo:
  + Boton pra acudir a una posición (reposo, por ejemplo)
  + Potenciómetro para indicar la velocidad de movimiento de los servos, indicar el delay.
  + Display de velocidad de movimiento
  + Display de voltaje de la batería del mando.
  + Display de último motor utilizado y su ángulo
  + Display con todos los angulos actuales del brazo
