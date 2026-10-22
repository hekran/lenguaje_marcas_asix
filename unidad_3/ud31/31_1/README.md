* static: añade left: 50px a .c1. ¿Se mueve? ¿Por qué?
    * No se mueve con left porque "static" es el posicionamiento por defecto no le afectan los posicionamientos, left, right, etc.

* absolute: pon c3 en position: absolute con top: 0 y right: 0. ¿A qué esquina va? 
    * Esquina superior derecha del viewport
* Ahora añade position: relative a .contenedor. ¿Qué cambia? ¿Y qué hacen los demás cuadros con el hueco de c3?
    * c3 se va a la esquina superior derecha de su padre .contenedor en lugar de la del viewport. Los demás cuadros no hacen nada se quedan igual, el que ocupa el hueco de c3 es la p con el texto.
