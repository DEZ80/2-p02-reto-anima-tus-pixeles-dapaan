# RETO 2.P02: Anima Tus Píxeles
Copia más abajo tus programas, cada uno en su parte del reto.

* Cada fotograma de animación debe durar 0.1s (10 fotogramas por segundo)
* Limitación: Sólo usar instrucciones siguientes: `3E`, `32`, `21`, `22`, `18`, `76`, `C3`

# PROGRAMAS

## Actividad 1: Mover el píxel rojo
Pixel que se mueve cíclicamente por los 4 primeros píxeles de pantalla
```
3E 88 32 00 C0 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 3E 44 32 00 C0 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 3E 22 32 00 C0 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 76 3E 11 32 00 C0 C3 00 40

Versión usando bucles
21 88 00 22 00 C0 3E 20 76 3D 20 FC 21 44 00 22 00 C0 3E 20 76 3D 20 FC 21 22 00 22 00 C0 3E 20 76 3D 20 FC 21 11 00 22 00 C0 3E 20 76 3D 20 FC C3 00 40
```
PC: 4000

## Actividad 2: Barra de progreso de 4 colores
La barra de progreso se rellena alternativamente con cada uno de los colores
```
21 43 77 22 00 C8 18 FE
```
PC: 4000

## Actividad 3: Sprite animado (Ej: Cara sonriente)
4x4 píxeles mínimo para cada fotograma.
```
21 43 77 22 00 C8 18 FE
```
PC: 4000

# IMAGENES
Si quieres, puedes subir pantallazos y enlazarlos aquí.
![Actividad 1](/tuimagen1.png)
![Actividad 2](/tuimagen2.png)
![Actividad 3](/tuimagen3.png)
