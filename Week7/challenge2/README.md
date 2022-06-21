# Week 7 - Challenge 2

## API REST Things I already know

Crea una API REST que se conecte a un fichero JSON, para manipular recursos de tipo _cosas que ya sé_. El JSON tendrá una sola propiedad de tipo array, donde almacenarán objetos que representarán cosas que hemos aprendido en el bootcamp. Duplica el fichero JSON de datos para que una sea la de pruebas y otra la de producción.

La API REST debe tener los siguientes endpoints:

[GET] /things -> devuelve el array de cosas que ya sé

[GET] /things/:idThing -> devuelve una cosa que ya sé

[DELETE] /things/:idThing -> borra una cosa que ya sé

[POST] /things -> crea una cosa que ya sé (la recibe en el body)

[PUT] /things -> modifica una cosa que ya sé (la recibe en el body)

## Opción extra:

Para iniciar la API, el programa debe mostrarle al usuario las siguientes preguntas (utiliza el paquete `inquirer`):

- ¿En qué puerto quieres que se inicie la API? (respuesta por defecto: 4000)
- ¿Qué fichero quieres usar? (pregunta con varias opciones, una única respuesta)
  - Pruebas
  - Producción
- ¿Quieres permitir que los clientes puedan crear, borrar y modificar? (respuesta de sí o no)

## Utiliza el patrón de express:

- server
- app
- /router
- /controller

## Intenta empezar a testear los controllers
