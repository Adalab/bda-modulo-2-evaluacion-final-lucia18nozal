# bda-modulo-2-evaluacion-final-lucia18nozal

Este ejercicio se basa en la base de datos ***"Sakila"***. La base de datos contiene las tablas: *actor*, *address*, *category*, *city*, *country*, *customer*, *film*, *film_actor*, *film_category*, *fil_text*, *inventory*, *language*, *payment*, *rental*, *staff* y *store*.

## Tablas más relevantes

- __film__: Contiene información sobre las películas.
- __actor__: Contiene información sobre los actores.
- __customer__: Contiene información sobre los clientes.
- __rental__: Contiene los registros los alquileres realizados por los clientes.
- __category__: Contiene las categorías de las películas.
- __film_actor__: Relaciona las películas con los actores que aparecen en ellas.

## Consultas Realizadas
A continuación se listan las consultas SQL realizadas sobre la base de datos Sakila:

1. Selecciona todos los nombres de las películas sin que aparezcan duplicados.
2. Muestra los nombres de todas las películas que tengan una clasificación de "PG-13".
3. Encuentra el título y la descripción de todas las películas que contengan la palabra "amazing" en su descripción.
4. Encuentra el título de todas las películas que tengan una duración mayor a 120 minutos.
5. Recupera los nombres de todos los actores.
6. Encuentra el nombre y apellido de los actores que tengan "Gibson" en su apellido.
7. Encuentra los nombres de los actores que tengan un actor_id entre 10 y 20.
8. Encuentra el título de las películas en la tabla film que no sean ni "R" ni "PG-13" en cuanto a su clasificación.
9. Encuentra la cantidad total de películas en cada clasificación de la tabla film y muestra la clasificación junto con el recuento.
10. Encuentra la cantidad total de películas alquiladas por cada cliente y muestra el ID del cliente, su nombre y apellido junto con el número de películas alquiladas.
11. Encuentra la cantidad total de películas alquiladas por categoría y muestra el nombre de la categoría junto con el recuento de alquileres.
12. Encuentra el promedio de duración de las películas para cada clasificación de la tabla film y muestra la clasificación junto con el promedio de duración.
13. Encuentra el nombre y apellido de los actores que aparecen en la película con título "Indian Love".
14. Muestra el título de todas las películas que contengan la palabra "dog" o "cat" en su descripción.
15. Encuentra el nombre y apellido de los actores que no han actuado en ninguna película de la categoría "Horror".
16. Encuentra el título de todas las películas que fueron lanzadas entre el año 2005 y 2010.
17. Encuentra el título de todas las películas que son de la misma categoría que "Family".
18. Muestra el nombre y apellido de los actores que aparecen en más de 10 películas.
19. Encuentra el título de todas las películas que son "R" y tienen una duración mayor a 2 horas en la tabla film.
20. Encuentra las categorías de películas que tienen un promedio de duración superior a 120 minutos y muestra el nombre de la categoría junto con el promedio de duración.
21. Encuentra los actores que han actuado en al menos 5 películas y muestra el nombre del actor junto con la cantidad de películas en las que han actuado.
22. Encuentra el título de todas las películas que fueron alquiladas por más de 5 días. Utiliza una subconsulta para encontrar los rental_ids con una duración superior a 5 días y luego selecciona las películas correspondientes.
23. Encuentra el nombre y apellido de los actores que no han actuado en ninguna película de la categoría "Horror". Utiliza una subconsulta para encontrar los actores que han actuado en películas de la categoría "Horror" y luego exclúyelos de la lista de actores.
24. Encuentra el título de las películas que son comedias y tienen una duración mayor a 180 minutos en la tabla film.

## Cómo ejecutar el ejercicio
- __Instalar MySQL__: Asegúrate de tener MySQL instalado en tu sistema.
- __Cargar la base de datos Sakila__: Puedes cargar la base de datos *"Sakila"* utilizando los archivos *sakila-schema.sql* y *detalle-bbdd-sakila.md* que puedes obtener en *https://books.adalab.es/materiales-data-analytics-full-time/modulo-2-extraer-informacion-de-la-web-y-bases-de-datos/repasos/repaso-2*.
- __Ejecutar las consultas__: Una vez que la base de datos esté creada y completa, puedes ejecutar las consultas SQL proporcionadas en el archivo *"Ejercicio_Evalucaion_Modulo_2_Lucia_Nozal.sql"*.

## Autor del ejercicio
- Lucía Nozal Benito.

## Tecnologías y herramientas usadas
- **Visual Studio Code**: Editor de código utilizado para desarrollar el README y como conector con Git.
- **GitHub**: Plataforma utilizada para alojar el ejercicio completo.
- **MySQL Workbench**: Herramienta utilizada para gestionar y ejecutar las consultas en la base de datos.