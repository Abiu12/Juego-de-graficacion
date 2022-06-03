
# Juego de carreras en 3D

En el siguiente proyecto se desarrolló un Juego en 3D utilizando OpengL

## Como correr el programa
    1.Descargar Visual Studio  (v. 2015 o 2019). Asegurandose que se descarguen todos lo complementos para poder programar en C++.
    2.Una vez descargado debemos abrir el proyecto en Visual Studio, escogiendo el archivo llamado Texturas.vcxproj.
    3.Abrir las opciones del proyecto principal.
    3.Configuraremos la libreria glut por lo cual debemos de seleccionar configuracion.
    4.Escoger "para todos los ajustes".
    5.Ir a C++, despues a incluciones adicionales y poner la carpeta include. Aplicar cambios.
    6.Ir a Vinculador y en el primero poner en adicionales a lib para después guardar cambios.
    7. Cambiamos a "debug", seleccionamos entrada y en dependencias adicionales escribimos "freeglut.lib".
## Instruciones del juego
El juego consiste en que el usuario debe de llegar a la meta
que se encuentra al otro lado del camino 
 evitando los obstaculos y antes que se le acabe el tiempo.
El usuario se podrá mover hacia adelante (tecla w), girar hacia la derecha (tecla d) y girar hacia la izquierda(tecla a).
## Reglas
El usuario cuenta con 100 segundos para llegar a la meta y debe de evitar los obstaculos, ya que al 
momento de chocar con alguno perderá y el juego se reiniciará.
