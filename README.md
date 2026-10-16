## Inline-flex en .contenido o .inline-block en .tarjeta
* Me quedo con flex en .contenido, razones:
    * No necesito modificar padding ni margin porque el contenido se adapta solo al ancho.
    * Todo los hijos de .contenido se ven afectados
    * Si necesito que el tamaño del contenido no cambie siempre puedo usar un min-width
    * Lo vamos a usar próximamente, asi lo voy practicando
    * Flexbox me permitiría luego mucho juego para en el responsive para ordenar esos div.
## Respuestas Parte C
1. ¿qué diferencia hay entre margin y padding?
    Margin separa la caja de forma externa después del border, no ocupa espacio en el contenido aunque si dentro de donde este contenida la caja.
    Padding ocupa espació dentro del contenido y lo hace crecer.
2. ¿por qué saltaba la tercera tarjeta de línea?
    porque entre el contenido el margin, el border y el padding hacia que la caja ocupara más espacio, quitando 5 de padding se solucionó.
3. ¿qué propiedades ignoraba el <span> y por qué?
    Ignora el width, height y el margin-top y margin-bottom porque es un elemento de linea.
4. ¿qué hace display: none con el espacio que ocupaba la caja?
    Desaparece la caja y también el espacio que ocupaba