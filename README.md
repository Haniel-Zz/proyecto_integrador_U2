Animación por Frames en Blender (2D)
Proyecto: Animación simple de un león en 8 frames
Introducción

La animación por frames en 2D consiste en definir manualmente una serie de imágenes consecutivas que representan diferentes estados de un objeto, generando la ilusión de movimiento al reproducirse en secuencia.

En este proyecto se desarrolla una animación simple de un león en Blender, utilizando únicamente 8 frames, lo que corresponde a una animación básica tipo ciclo corto.

Objetivo

Crear una animación 2D básica del movimiento de un león utilizando 8 frames, aplicando keyframes manuales dentro del entorno de Blender.

1. Entorno de trabajo

El proyecto se desarrolla en el espacio de trabajo 2D Animation de Blender, donde se utiliza una cámara fija y un modelo estilizado del león.

Descripción técnica
Vista: Cámara en perspectiva
Tipo: Animación 2D
Objeto principal: León
Fondo: Color sólido
Timeline activa
2. Configuración de la animación
Procedimiento
Ir a la Timeline (parte inferior)
Configurar:
Frame inicial: 1
Frame final: 8
Ajustar FPS:
12 fps (recomendado para animación simple)
o 24 fps si se desea mayor fluidez
3. Activación de keyframes
Procedimiento
Activar el botón de Auto Keyframe (círculo rojo)
Esto permite registrar automáticamente los cambios realizados en cada frame
4. Desarrollo de la animación (8 frames)

Dado que solo se utilizan 8 frames, cada uno representa un cambio significativo en el movimiento.

Estructura de animación
Frame	Acción
1	Posición inicial
2	Movimiento leve de patas
3	Avance del cuerpo
4	Cambio de patas delanteras
5	Extensión del movimiento
6	Apoyo contrario
7	Preparación de cierre
8	Regreso a posición inicial
5. Procedimiento paso a paso
Frame 1
Seleccionar el león
Posición inicial (reposo)
Presionar:
I → Location / Rotation
Frame 2
Mover ligeramente:
Una pata
Cabeza
Insertar keyframe
Frame 3
Desplazar el cuerpo hacia adelante
Ajustar patas traseras
Insertar keyframe
Frame 4
Cambiar apoyo de patas delanteras
Ajustar equilibrio del cuerpo
Insertar keyframe
Frame 5–7
Continuar alternando movimiento de patas
Mantener coherencia del ciclo
Insertar keyframes en cada frame
Frame 8
Regresar a posición similar al Frame 1
Esto permite que la animación sea cíclica
6. Edición de animación
Uso del Dope Sheet
Cambiar vista a:
Dope Sheet → Action Editor
Verificar:
Que existan keyframes en los 8 frames
Ajustar tiempos si es necesario
7. Configuración de render
Procedimiento
Ir a Output Properties
Configurar:
Formato: MPEG-4
Codec: H.264
Seleccionar carpeta de salida
8. Renderizado
Procedimiento
Ir a:
Render → Render Animation
Blender generará la animación completa (8 frames)
Conclusión

La animación por frames en 2D con una cantidad reducida de frames permite comprender los principios básicos del movimiento, como la secuencia, el ritmo y la repetición. Aunque se trata de una animación simple, el correcto uso de keyframes y la organización del timeline permiten obtener resultados funcionales y reutilizables.

Estructura recomendada para GitHub
animacion-leon-2d
│
├── README.md
├── imagenes/
│   └── leon_base.png
├── leon.blend
└── render.mp4
Recomendaciones técnicas
Mantener consistencia entre frame 1 y 8 (loop)
Exagerar movimientos en pocos frames para mejor visibilidad
Trabajar primero en poses clave (key poses)
Usar interpolación lineal si se desea estilo más “frame a frame”
