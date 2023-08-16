# Ejercicio XML y Kotlin: Práctica de Vistas y Activities

Este repositorio contiene un ejercicio simple en el que se practica la integración de XML con Kotlin en el desarrollo de aplicaciones de Android. El ejercicio se enfoca en la creación de vistas y activities para lograr una funcionalidad básica.

## MainActivity

El archivo `MainActivity.kt` contiene el código para la actividad principal de la aplicación. Algunos puntos clave incluyen:

- Se define una actividad `MainActivity` que hereda de `AppCompatActivity`.
- En el método `onCreate`, se establece el contenido de la actividad a partir del archivo de diseño `activity_main.xml`.
- Se obtienen referencias a un botón (`btnStart`) y un campo de texto (`etName`) mediante su ID.
- Se configura un listener para el botón que, al hacer clic, verifica si el campo de texto no está vacío.
- Si el campo de texto tiene contenido, se crea un intent para lanzar la `ResultActivity2` y se le pasa el nombre ingresado como extra.

## ResultActivity2

El archivo `ResultActivity2.kt` representa la segunda actividad de la aplicación, que muestra un mensaje de saludo. Puntos importantes:

- La actividad `ResultActivity2` extiende `AppCompatActivity`.
- En `onCreate`, se vincula el diseño `activity_result2.xml` con la actividad.
- Se obtiene el nombre pasado como extra desde el intent.
- Se muestra un mensaje de saludo utilizando el nombre obtenido.

## Conclusiones

Este ejercicio proporciona una práctica básica en la creación de actividades, vinculación de vistas y el uso de extras en intents. Aunque simple, sienta las bases para comprender cómo desarrollar aplicaciones Android utilizando Kotlin y XML.

¡Diviértete explorando y mejorando tus habilidades en el desarrollo de aplicaciones móviles!
