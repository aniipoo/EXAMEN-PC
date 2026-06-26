[link](https://editor.p5js.org/Anais06/sketches/C4yXdFtSB) p5js

# EXAMEN-PC

*BAUHAUS INTERACTIVO*

![<img width="466" height="700" alt="Copia de Bauhaus XI_20x30-1743091906222" src="https://github.com/user-attachments/assets/8a2f466d-f466-45bc-99af-9fe00de17c0e" />
]

El proyecto es un afiche de reinterpretación de la BAUHAUS, su autor es desconocido. El afiche no esta completo, solo tiene sus figuras geometricas principales y el texto, a través del sistema computacional hice el afiche interactivo.

Utilice la misma base de mi solemne dos, la diferencia aqui es la existencia de dos pantallas más.

Estado 1: es el afiche normal, color de fondo claro, sin interacción.

Estado 2: lo mismo, pero con el fondo negro y el color del trazo es blanco.

Estado 3: esta la mayor interactividad; el fondo es rosado, hay un sonido sin sentido, nada que ver con la BAUHAUS. Esto es intencional, ya que los colores que estan en el 3er afiche, no son parte del estilo bauhaus. Tambien con la letra 'a', se agrandan los circulos y con la 'w' se hacen más pequeños. 

Otra interacción aplicada en los 3 estados, es que en el eje y, hacia arriba, el trazo es más delgado y hacia abajo es más grueso. Hacia la izquierda el trazo desaparece y hacia la derecha, aparece.

**Inputs**
   - mouseX
   - mouseY
   - mousePressed
   - keyPressed

  **Outputs**
   - tamaño de los circulos
   - color de los circulos
   - cambio color de fondo
   - movimiento aleatorio de los circulos
   - cambio de tamaño y color del trazo
   - sonido en el estado 3
   - lineas

**PROCESO**


Aqui empezaba el codigo, tenia un error, y no descubri el por qué, por lo que tome la decisión de empezar de nuevo, pero más adelante tuve otro problema.
    ![<img width="1920" height="1080" alt="Captura de pantalla (72)" src="https://github.com/user-attachments/assets/e1101cfa-fec2-4894-923d-bb70eda568f4" />
]

Cuando puse el sonido, el codigo no me cargaba, e incluso, pensé que se me habia borrado todo, pero volvi a sketch.js porque habia notado que estaba en otra ventana, donde puse el audio, sin embargo, seguia sin cargar. Copie todo el código y lo pegue en otra pestaña de p5js. No sabía cual era el problema y le pregunte a la IA por que pasaba eso y resulto ser que el audio estaba mal escrito, una vez resolvi eso, cargo bien y el audio funcionaba.

![<img width="1920" height="1080" alt="Captura de pantalla (73)" src="https://github.com/user-attachments/assets/82128d73-c475-43b5-976a-2dd7bab319f0" />
]

Despues, me di cuenta que en el input mouseX y mouseY tenia mal al reves width y height, asi que los cambie y a demas habia olvidado poner el segundo bucle, solo lo tenia escrito, pero estaba vacio y decidi agregar lineas simples.

Los problemas que tuve se pudieron evitar, pero me sirvieron mucho como aprendizaje.

![<img width="1024" height="1536" alt="diagrama de flujo" src="https://github.com/user-attachments/assets/9f0269bd-e7ae-4e31-b8a6-7af5da51ca5f" />
]
