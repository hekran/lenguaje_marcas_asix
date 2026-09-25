<alumno>Héctor Santonja</alumno>
# ACTIVIDAD 1
Al crear el archivo con extensión txt se ve el código tal cual se escribe en el navegador:
```
<h1>Texto grande</h1>
<h3>Texto Pequeño</h3>
```
Al cambiar la extensión a .html ya se ve formateado h1 como titulo principal.
<h1>texto grande</h1>
Y h3 como titulo secundario
<h3>Texto Pequeño</h3>

# ACTIVIDAD 2
```
<asir>
  <modulo><titulo>Lenguaje de Marcas</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>HTML</unidad>
      <unidad>CSS</unidad>
    </contenido>
  </modulo>
  <modulo><titulo>Fundamentos de Hardware</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>Unidad 1</unidad>
      <unidad>Unidad 2</unidad>
    </contenido>
  </modulo>
  <modulo><titulo>Implantación de Sistemas Operativos</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>Unidad 1</unidad>
      <unidad>Unidad 2</unidad>
    </contenido>
  </modulo>
  <modulo><titulo>Planificación y Administración de Redes</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>Unidad 1</unidad>
      <unidad>Unidad 2</unidad>
    </contenido>
  </modulo>
</asir>
```
# ACTIVIDAD 3
```
<mundo>
	<continente><nombre>Europa</nombre>
		<paises>
			<pais>España</pais>
			<pais>Portugal</pais>
			<pais>Francia</pais>
			<pais>Alemania</pais>
			<pais>Italia</pais>
		</paises>
	</continente>
	<continente><nombre>América</nombre>
		<paises>
			<pais>Venezuela</pais>
			<pais>Argentina</pais>
			<pais>Ecuador</pais>
			<pais>México</pais>
			<pais>Canadá</pais>
		</paises>
	</continente>
	<continente><nombre>Asia</nombre>
		<paises>
			<pais>China</pais>
			<pais>Japón</pais>
			<pais>Corea del Sur</pais>
			<pais>Taiwán</pais>
			<pais>Indonesia</pais>
		</paises>
	</continente>
	<continente><nombre>África</nombre>
		<paises>
			<pais>Marruecos</pais>
			<pais>Egipto</pais>
			<pais>Sudáfrica</pais>
			<pais>Congo</pais>
			<pais>Madagascar</pais>
		</paises>
	</continente>
</mundo>
```
> ### *Vocabulario:*
> mundo, continente, nombre, países, país
> ### *Reglas:*
> *mundo* contiene varios *continente*, un *continente* tiene un *nombre* y *paises*, *paises* tiene varios *pais*. Todos los *pais* entan en *paises*, *pais* es texto simple, detras de un *pais* solo puede ir otro *pais* o el fin de *paises*. Detras de *paises* solo puede ir otro *continente* o fin de *mundo*
# ACTIVIDAD 4
```
<biblioteca>
	<libros>
		<libro>
			<titulo>FALCO</titulo>
			<isbn>9788420419688</isbn>
			<autor>ARTURO PEREZ REVERTE</autor>
			<paginas>296</paginas>
			<editorial>ALFAGUARA</editorial>
			<idioma>CASTELLÀ</idioma>
			<formato>En papel</formato>
		</libro>
		<libro>
			<titulo>TODO ALATRISTE</titulo>
			<isbn>9788420425528</isbn>
			<autor>ARTURO PEREZ REVERTE</autor>
			<editorial>ALFAGUARA</editorial>
			<idioma>CASTELLÀ</idioma>
			<formato>EBOOK</formato>
		</libro>
		<libro>
			<titulo>HOMBRES BUENOS</titulo>
			<isbn>9788466329804</isbn>
			<autor>ARTURO PEREZ REVERTE</autor>
			<editorial>PUNTO DE LECTURA</editorial>
			<anio>2024</anio>
			<formato>En papel</formato>
			<sinopsis>La heróica aventura de quienes se atrevieron a cambiar el mundo con libros. En tiempos de oscuridad siempre hubo hombres buenos que lucharon para llevar las luces y el progreso. Y otros que procuraron impedirlo.</sinopsis>
		</libro>
	</libros>
</biblioteca>
```
> ### *Vocabulario:*
> biblioteca, libros, libro, titulo, isbn, autor, paginas, editorial, idioma, formato, anio, sinopsis.
> ### *Reglas:*
> *biblioteca* contiene *libros*, un *libros* contiene varios *libro*, un *libro* puede tener *titulo, isbn, autor, paginas, editorial, idioma, formato, anio (año), sinopsis*, todas estas estiquetas son texto simple, detrás de un *libro* solo puede ir otro *libro* o fin de *libros*, después de *libros* solo puede ir fin de *biblioteca*.
