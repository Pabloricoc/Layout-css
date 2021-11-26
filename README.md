<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>CSS Layout Pablo Rico Cabello</title>
	<style>
		.Ejemplo {
			color:red
		}
		#ejemplo-div {background-color :beige}
		.div-ejemplo {
            background: rgb(250, 138, 138);
            width: 70%;
            height: 70px;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 15px 0px 10px 6px;
            border: 5px groove rgb(96, 125, 202);
        }
		#ejemplo-model-box {
            background: rgb(92, 126, 177);
            width: 30%;
            height: 210px;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 15px 0px 10px 6px;
            border: 5px groove rgb(224, 238, 32);
        }
	</style>
</head>
<body>
	<h1><strong>Layout Pablo Rico Cabello</strong></h1>
<h2><strong>Span-Pablo Rico Cabello</strong></h2>
Utilizamos la etiqueta span para seleccionar una sola palabra que queramos cambiar de color o de fondo.<br>
Ejemplo de span: Esto es un<span class="Ejemplo"> ejemplo</span> que selecciono la palabra ejemplo para ponerla en color rojo
<h2><strong>Div-Pablo Rico Cabello</strong></h2>
Utilizamos la etiqueta div para crear secciones o agrupar contenidos. Sus etiquetas son: < div > y < /div > (ambas obligatorias). Está definido como: Elemento en bloque.<br>
<div id="ejemplo-div">Ejemplo del uso de div: Este texto lo he seleccionado con div y lo he puesto con un fondo de color beige para añadir al texto.<br>
Esto sigue siendo el ejemplo de div</div>
<h2><strong>Overflow-Pablo Rico Cabello</strong></h2>
La propiedad overflow permite regular la visiblidad de los contenidos que sobresalen de una caja html. Permite regular si los contenidos que sobresalen se seguirán viendo, si se ocultarán o si aparecerá una barra de scroll en el documento.
<div class="div-ejemplo">
La nutria es un mamífero con cuerpo de mustélido: alargado y esbelto, macizo y de patas cortas. La cabeza es aplastada y con el hocico ancho y las orejas pequeñas y cubiertas de pelos y que, al igual que las narinas, puede cerrar herméticamente cuando se sumerge en el agua. El pelaje es denso y pardo, y en la garganta, mejilla y vientre, más claro. La longitud de la cabeza y el cuerpo desde el extremo del hocico hasta la base de la cola es de 600-850 mm y la cola mide 350-600 mm siendo los machos mayores que las hembras. La longevidad oscila entre los 8 y los 12 años y en cautividad se conoce un caso de una nutria que llegó a vivir 19 años.

Las nutrias suelen ser de actividad nocturna y los machos solitarios la mayor parte del año, aunque la unidad social más desarrollada de las nutrias es el grupo familiar. Viven en aguas dulces, en costas abrigadas y estuarios y necesita lugares tranquilos donde situar sus madrigueras y el alimento sea abundante.</div>
<br>
<h2><strong>Model box-Pablo Rico Cabello</strong></h2>
El modelo de caja CSS se refiere a cómo se modelan los elementos HTML en los motores de los navegadores y cómo las dimensiones de esos elementos HTML se derivan de las propiedades CSS. Se distinguen padding, border y margin:<br>
Padding: Es la distancia de relleno entre el contenido del elemento y el borde. Podemos modificar esa distancia poniendo padding dentro de la etiqueta style y dentro de un bloque/elemento concreto.<br>
Borde: Es el borde, el límite del elemento. Podemos modificar su grosor, color y forma (entre otros) poniendo border dentro de la etiqueta style y de un bloque/elemento concreto.<br>
Margen: Es la distancia entre dos elementos. Se puede cambiar la distancia poniendo margin dentro de una etiqueta style y de un bloque/elemento concreto.<br>
<br>
<br>
<img id="ejemplo-model-box" src="https://desarrolladoresweb.org/wp-content/uploads/Ancho-total-del-modelo-de-caja-en-CSS-1.jpg">
el padding de la imagen anterior lo he puesto de 0px; el borde lo he hecho con un grosor de 5px, de color amarillo y con una forma "groove"; y el margen es de 15px.
Página hecha por Pablo Rico Cabello- 26/11/2021
</body>
</html>
