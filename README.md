# Desafío 4 - Inmobiliaria

En este desafío validaremos nuestros conocimientos en los contenidos de arreglos y objetos, modificándolos con DOM.

Lee todo el documento antes de comenzar el desarrollo __individual__, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

Aplicando los conceptos y herramientas aprendidas hasta ahora, en este desafío deberás programar la renderización dinámica de propiedades inmobiliarias y los filtros de búsquedas de un menú lateral.

A continuación te mostramos una referencia de lo que debes maquetar:

💡 Puedes utilizar el código del ___Apoyo Desafío - Inmobiliaria___, o crear tu propio estilo.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-04/blob/main/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Maqueta general del desafío<br>
Fuente: Desafío Latam
</p>

En donde tenemos un buscador de propiedades en un costado:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-04/blob/main/02.png?raw=true?raw=true" alt="Imagen 02"><br>
Imagen 2. Buscador<br>
Fuente: Desafío Latam
</p>

Y una galería de propiedades con el total de busqueda:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-04/blob/main/03.png?raw=true?raw=true" alt="Imagen 03"><br>
Imagen 3. Galería de propiedades<br>
Fuente: Desafío Latam
</p>

El usuario deberá poder tipear en el filtro la cantidad de cuartos y un rango de metros cuadrados que desee definir para la búsqueda de propiedades que cumplan estos criterios.

En caso de que falte algún campo por llenar se deberá avisar al usuario con una ventana emergente.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-04/blob/main/04.png?raw=true?raw=true" alt="Imagen 04"><br>
Imagen 4. Notificación de campos vacíos<br>
Fuente: Desafío Latam
</p>

Al momento de realizar una búsqueda con éxito, se debe actualizar el valor del nuevo total de propiedades.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-04/blob/main/05.png?raw=true?raw=true" alt="Imagen 05"><br>
Imagen 5. Búsqueda con éxito<br>
Fuente: Desafío Latam
</p>

## Requerimientos

1. Implementar todos los elementos necesarios para aplicar las funcionalidad del desafío __(1 punto)__

2. Crea un arreglo de propiedades que cumplan la siguiente estructura __(2 puntos)__

```js
{
  nombre: "Departamento",
  descripcion: "Desde las alturas todo se ve mejor",
  src: "...",
  cuartos: 3,
  metros: 200
},
```

3. Agrega el evento click al botón del buscador __( 0.5 puntos)__

4. Agrupar la lógica en funciones reutilizables que sean ejecutadas en cada búsqueda __(1 punto)__

5. Utiliza ciclos para recorrer el arreglo de propiedades __(2 puntos)__

6. Utiliza la interpolación y el _innerHTML_ para crear templates y agregar los templates de las propiedades durante el recorrido del arreglo __(2 Puntos)__

7. Utiliza condicionales para evaluar si falta algún campo por llenar en el buscador __(1 Punto)__

8. Actualiza el total de resultados en cada búsqueda generada con éxito __(0.5 Punto)__

😊¡Mucho éxito!
