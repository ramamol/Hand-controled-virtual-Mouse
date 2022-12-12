
# Hand controled virtual Mouse

El proyecto consiste en controlar el cursor con gestos realizado con la mano derecha. El codigo se basa en el uso de un modelo de una red neuronal convucional
implementada por mediapipe. Consiste en un módulo que detecta directamente los gestos de lamano
utilizando mediapipe hand detection. Actualmente corre en Windows.

## Video

Para ver el video del funcionamiento acceder al suguiente link: 


## Features

#### Gesestos de control:

|#gesto |Gesto de la mano             | Función                                      |
|-| ----------------- | ------------------------------------------------------------------ |
|1|Puño con dedo Indice y dedo mayor levantado, sin separación entre medio| Detecta la mano y mueve el cursor |
|2| 1 + Puño con dedo pulgar Levantado   | Detiene el movimiento en el lugar | 
|3| 2 + Acción de Bajar y subir indice |Click izquierdo|
|4| 2 + Acción de bajar y subir indice y dedo mayor| Doble click izquierdo|
|5| 2 + Acción de separar y juntar dedo indice y dedo mayor | Click derecho|
|6| Levantar/bajar Puño cerrado con dedo pulgar levantado | Scroll arriba/abajo|
|7| Puño cerrado | Mantener pinchado  (drag)|
|8| 2 + Acción de abrir completamnete la mano y cerrarla | Captura de pantalla|
## Para correr el codigo

Primer paso:
Copiar el codigo completo y pegarlo en el editor de texto.
Codigo : 

Se debe instalar OpecCv

```bash
  pip install OpecCv   
```

Se debe instalar la librería mediapipe         

```bash
  pip install mediapipe   
```

Se debe instalar  pyautogui         

```bash
  pip install pyautogui   
```
## Autores

Ramiro Molin - ramiro.molin@ing.austral.edu.ar

Mariano Narbais  -  mariano.narbais@ing.austral.edu.ar

Ignacio soria - ignacio.soria@ing.austral.edu.ar

