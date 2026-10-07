# CSS UD 2.1
## Ejercicio 1
* La forma más cómoda o más práctica sería el archivo externo, razones:

  * Hacerlo inline sería un trabajo excesivo y dificil de corregir o actualizar, ya que si el HTML tiene muchas lineas (y aun con unas pocas) el proceso sería muy tedioso y difícil de organizar.
  * Hacerlo en el Head dentro de una etiqueta style puede estar bien para ejemplos o pruebas rápidas, pero si el CSS es extenso ocuparia demasiado espacio dentro del archivo HTML y si tienes varias páginas no podrías reutilizar ese CSS, te tocaría escribirlo de nuevo.
  * Mientras que el externo solo debes agregar una etiqueta link en el head y llamar al archivo CSS en cada página donde quieras utilizarlo, así tienes separados HTML y CSS y puedes reutilizar estilos para otras páginas, claramente sería el mejor para la pregunta de las 10 páginas (y para el 99% de los casos)
