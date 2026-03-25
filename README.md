Animación 2D por Frames (8 Frames) en Blender
Introducción

En esta práctica se realiza una animación 2D por frames en Blender utilizando un personaje tipo león. La animación consta de 8 frames, donde cada uno representa un cambio manual en la posición del modelo para simular movimiento (caminar).
referencia:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1f2d942f-e358-4495-a49a-3d961bd5ea4f" />

Vista del proyecto

Configuración inicial
Abrir Blender.
Cargar el archivo .blend del león.
Ir al espacio de trabajo 2D Animation.
Configurar la línea de tiempo:
Start: 1
End: 8
Proceso de animación (8 Frames)
Frame 1 (posición inicial)
El león está en reposo.
Todas las patas alineadas.

Frame 2 (inicio de movimiento)
Se adelanta la pata delantera.
Ligero movimiento de cabeza.

Frame 3 (avance)
El cuerpo se desplaza ligeramente hacia adelante.
La pata trasera comienza a levantarse.

Frame 4 (paso medio)
La pata delantera está más extendida.
El cuerpo baja ligeramente.

Frame 5 (continuación del paso)
Se alterna el movimiento de patas.
El cuerpo avanza.

Frame 6 (segunda fase)
La otra pata delantera avanza.
Movimiento leve de cola.

Frame 7 (cierre del ciclo)
El cuerpo vuelve a estabilizarse.
Preparación para volver al frame 1.

Frame 8 (posición final)
Similar al frame 1 para crear loop.
Permite animación continua.

Cómo insertar keyframes en Blender

Para cada frame:

Posicionarse en el frame (1–8).
Seleccionar el objeto o hueso del león.
Presionar:
I → Location

O si usas rig:

I → LocRotScale
Reproducción
Presionar barra espaciadora
Verificar fluidez del movimiento
Renderizado
Ir a Output Properties
Configurar:
Formato: FFmpeg Video
Resolución: 1920x1080
Render → Render Animation
<img width="1098" height="709" alt="image" src="https://github.com/user-attachments/assets/98e5a9cf-83d0-4c7b-8b75-3d3671b7674f" />
Conclusión

La animación por frames permite controlar completamente cada movimiento del personaje. Con solo 8 frames se logra una animación simple tipo ciclo de caminata, ideal para prácticas iniciales en Blender.
