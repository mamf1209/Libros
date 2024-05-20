# Explicación breve de las clases del proyecto:
## Clase Libro.java
El archivo Libro.java es una clase en Java que representa un objeto de tipo libro en nuestra aplicación de biblioteca digital. Esta clase contiene diferentes atributos que describen las características de un libro y métodos para interactuar con esos atributos.
Estas son las siguientes variables:

titulo: Esta variable de tipo String almacena el título del libro.

autor: Almacena el nombre del autor del libro como un String.

isbn: Representa el número de ISBN del libro, que es un identificador único para cada libro.

anioPublicacion: Un entero que indica el año de publicación del libro.

genero: Almacena el género del libro, también como un String.

editorial: El nombre de la editorial que publicó el libro.

![Code de la clase libro](https://raw.githubusercontent.com/mamf1209/libros/main/libro.jpg)

## Clase LibroController.java
La clase LibroController es responsable de manejar las solicitudes relacionadas con los libros en nuestra aplicación. Esto incluye la gestión de la lógica de negocio relacionada con los libros, como la creación, edición, eliminación y búsqueda de libros.
## Clase LibroService.java
La clase LibroService proporciona métodos y funciones que encapsulan la lógica de negocio relacionada con la gestión de libros. Aquí se pueden encontrar operaciones más complejas, como la validación de datos de libros, la gestión de transacciones y la interacción con la capa de persistencia de datos.
## Clase LibroRepository.java
La clase LibroRepository actúa como una interfaz entre nuestra aplicación y la capa de almacenamiento de datos. Aquí se definen los métodos para acceder y manipular los datos de los libros en la base de datos.

# Spring Boot

Acá se puede ver como se ejecutó con éxito el Spring Boot en el proyecto:

![Ejecución de Spring Boot](https://raw.githubusercontent.com/mamf1209/libros/main/EjecucionSpring.jpg)

# Pruebas a través de Postman:
## Endpoint GET/libros
### Descripción:
Este endpoint devuelve todos los libros almacenados en la base de datos.

![Obtener todos los libros](https://raw.githubusercontent.com/mamf1209/libros/main/GetAllBook.jpg)

## Endpoint GET/libros/{id_libro}
### Descripción:
Este endpoint devuelve un libro específico según su ID.

![Obtener libro por ID](https://raw.githubusercontent.com/mamf1209/libros/main/GetID.jpg)

## Endpoint POST/libros
### Descripción:
Este endpoint permite añadir un nuevo libro a la base de datos.

![Crear libro](https://raw.githubusercontent.com/mamf1209/libros/main/Create.jpg)

## LocalHost:
Acá se puede visualizar la página actualizada despues de realizar el útlimo Endpoint (donde se creó un nuevo libro):

![Imagen de localhost](https://raw.githubusercontent.com/mamf1209/libros/main/localhost1.jpg)


