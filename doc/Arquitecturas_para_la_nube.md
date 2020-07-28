## Buscar una aplicación de ejemplo, preferiblemente propia, y deducir que patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

Durante la asignatura de Programación Web realizamos la página web de una red social, esta, se basaba en una arquitectura en capas. Consistía en una base de datos SQL donde se almacenaban los distintos datos de los usuarios y el código por otra parte se encontraba realizado en HTML, CSS y PHP.

Para evolucionar esta aplicación a una arquitectura basada en microservicios habría que identificar primero cada uno de los eventos y más tarde asignarle a cada uno un microservicio, como por ejemplo la gestión del "login" o la gestión de la base de datos.

## En la aplicación que se ha usado como ejemplo en el ejercicio anterior, ¿Podría usar diferentes lenguajes? ¿Qué almacenes de datos serian los más convenientes?

Si se rediseñase el proyecto de forma que estuviese basada en microservicios podríamos usar el lenguaje que más se adapte a cada uno de los microservicios que obtuviésemos. Un ejemplo podría ser que en lugar de realizar todo el front-end de la página web en HTML se podría utilizar algún framework de desarrollo como por ejemplo [Django] Como almacén de datos, una base de datos relacional es muy útil por las relaciones entre las distintas entidades en la base de datos, como por ejemplo los usuarios y sus comentarios. Aun así sería interesante realizar un estudio para comprobar si una base de datos noSQL nos sería útil para este propósito.
