
# Colisión del lápiz con la letra

## Caso práctico: detectar colisión con la letra

El objetivo es alcanzar con el lápiz la letra que se mueve.

Para controlar la colisión seguimos añadiendo bloques en la programación del objeto lápiz, en el programa que se inicia "al presionar tecla flecha arriba".

Si detectamos que estamos tocando la letra A, enviaremos el mensaje "impacto-A"  a la letra A para decirle que desaparezca.

Habrá que pensar dónde colocar estos bloques.

<script type="text/javascript">var feedbackquesFeedback0b153text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-quesFeedback0b153" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

Estos son los bloques que controlarán que si el lápiz toca el objeto A, entonces se envía el mensaje "impacto-A":

![](img/Seleccion_055.png)
Estos bloques los colocaremos justo después de haber movido el lápiz en 10 posiciones hacia arriba:

![](img/Seleccion_056.png)
Ahora tenemos que recoger el mensaje "impacto-A" en el objeto A. Por lo tanto, haremos clic en el objeto A para modificar los bloques de su programación.

Añadiremos un bloque de programación en el objeto A: Cuando se reciba el mensaje "impacto-A", haremos que el objeto A desaparezca.

<script type="text/javascript">var feedbackquesFeedback1b153text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-quesFeedback1b153" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

![](img/Seleccion_058.png)
Ahora, cuando el objeto A es impactada por el lápiz, desaparece y ya no vuelve a aparecer. Tendremos que hacer que al inicio del juego, el objeto A aparezca visible. Lo podremos añadir en el programa ya existente que mueve la letra A.

<script type="text/javascript">var feedbackquesFeedback2b153text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-quesFeedback2b153" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

![](img/Seleccion_059.png)
## Caso práctico: Añadir puntuación

Añadiremos un marcador de puntos al juego. Haremos que los puntos se incrementen al detectar la colisión del lápiz con la letra.

Crear una variable llamada PUNTOS.

<script type="text/javascript">var feedbackquesFeedback0b154text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-quesFeedback0b154" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

![](img/Seleccion_060.png)
En la programación del objeto A:

- Al inicio del programa, ponemos los puntos a 0.
- En el momento de detectar colisión, sumamos 1 en la variable puntos.

<script type="text/javascript">var feedbackquesFeedback1b154text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-quesFeedback1b154" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

![](img/Seleccion_061.png)
