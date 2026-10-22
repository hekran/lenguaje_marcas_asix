* Añade una etiqueta "-20%" en la esquina superior derecha, sobresaliendo un poco (top: -10px; right: -10px) con position: absolute. ¿Qué elemento necesita position: relative para que la etiqueta se coloque respecto a la tarjeta?
    * El elemento padre, en mi caso .tarjeta que es donde está contenido .etiqueta
* Pon overflow: hidden a la tarjeta. ¿Qué le pasa a la parte de la etiqueta que sobresale? Anota por qué y cómo lo arreglarías.
    * La parte que sobresalia, queda oculta, la etiqueta aparece cortada ya que hidden en overflow lo que hace es ocultar lo que "sobresale" del contenedor al que se le aplica.
    * Para arreglarlo, la verdad no queda mal, me gusta más así, pero sería quitando el overflow o si tiene que quedar declarado, poniendolo como "visible".
* Prueba overflow: visible, hidden, scroll y auto. Anota en el README qué hace cada uno y deja auto.
    * visible: la apariencia es la misma, se ve igual (muestra el overflow)
    * hidden: oculta todo lo que no cabe en la caja padre, no puedes desplazarte con la rueda del mouse para verlo.
    * scroll: aparece una barra lateral y horizontal de desplazamiento donde puedes desplazarte por el texto que se sale de la caja pinchandola o con la rueda del mouse.
    * auto: en este caso pasa parecido a "scroll" mostrando solo la barra de desplazamiento vertical, si no hubiera overflow no mostraria barras de desplazamiento.
* Duplica una tarjeta y prueba visibility: hidden en una y display: none en la otra. Anota la diferencia respecto al hueco que dejan.
    * visibility hidden: La tarjeta no se ve, pero conserva su espacio en el viewport
    * display none: La tarjeta desaparece del viewport, incluido el espacio que ocupa.