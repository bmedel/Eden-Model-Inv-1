Proyecto de investigación sobre el modelo Eden C en una grilla (discreto).

El modelo Eden es un modelo de crecimiento aleatorio no trivial que simula un sistema auto-organizado que, dado un set de reglas, simula la dinámica de crecimiento de una partícula inicial. Existen 3 variantes del modelo (A-B-C). Estas variantes difieren en el set de reglas con el que estos sistemas crecen. Es importante notar que en este modelo se descarta la superposición entre partículas, por lo tanto, las partículas solo se pueden mover a espacios libres.

La variante C del modelo tiene dos reglas: 

  1. Selecciona aleatoriamente entre partículas activas (las que tienen disponible al menos un espacio libre para moverse).
  2. Selecciona aleatoriamente entre las posiciones libres (donde no haya otra partícula) que tiene la partícula escogida.

El archivo 'eden_c_anim.py' contiene la simulación. Basta elegir el tipo de grilla entre 'cuadrada' y 'triangular' y especificar el tamaño del cluster (N particulas) para que se guarde un archivo '.mp4' con la animación (8 segundos).
