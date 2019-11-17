## Buscar una aplicación de ejemplo, preferiblemente propia, y deducir que prato es el que usa. ¿Que habría que hacer para evolucionar a un patrón tipo microservicios?

Durante la asignatura de Programación Web realizamos la pagina web de una red social, esta, se basaba en una arquitectura en capas. Consistia en una base de datos SQL donde se almacenaban los distintos datos de los usuarios y el codigo por otra parte se encontraba realizado en HTML, CSS y PHP.

Para evolucionar esta aplicacion a una arquitectura basada en microservicios habria que identificar primero cada uno de los eventos y mas tarde asignarle a cada uno un microservicio, como por ejemplo la gestion del "login" o la gestion de la base de datos.

## En la aplicación que se ha usado como ejemplo en el ejercicio anterior, ¿Podría usar diferentes lenguajes? ¿Que almacenes de datos serian los más convenientes?

Si se rediseñase el proyecto de forma que estuviese basada en microservicios podriamos usar el lenguaje que más se adapte a cada uno de los microservicios que obtuviesemos. Como almacen de datos, una base de datos relacional es muy util por las relaciones entre las distintas entidades en la base de datos, como por ejemplo los usuarios sus comentarios. Aun así seria interesante realizar un estudio para comprobar si una base de datos noSQL nos seria util para este proposito.
