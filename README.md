# CaC_JAVA_Backend
## Servicio de Alquiler de Bicicletas

Se realizó con Spring. Se trata de estaciones de alquiler de bicicletas que se encuentran en diferentes puntos geográficos de la Ciudad de Córdoba.
Utilicé el IDE IntelliJ y Solo está desarrollado el Backend. No se hizo un FrontEnd aún, pero se puede demostrar la funcionalidad con la herramienta Postman.

Creé el proyecto con Spring Initializr, a través de https://start.spring.io/
Incluí las dependencias que se recomiendan para aplicaciones Web que son: "Spring Web", "Lombok" y "Spring Data JPA".
"Spring Web": dá la facilidad de crear APIs RESTful o aplicaciones web tradicionales.
 "Lombok": es una biblioteca que genera automáticamente métodos como getters, setters, constructores.
 y "Spring Data JPA": simplifica el poder interactuar con BD relacionales, implementando automáticamente las consultas CRUD (Create, Read, Update, Delete) 

Luego se crea una clase Java para representar la entidad, en este caso Tarifa.
@Entity: lo que hace es marcar a la clase como una entidad persistente, lo que significa que los objetos de esta clase se van a guardar y se recuperar en una BD.
@Data: genera los métodos getters y setters para todos los campos de la clase.
Esto es clave porque reducimos la cantidad de código y me es de mucha ayuda a mi criterio, me encanta ♥.
Por último, cabe aclarar que definí los parámetros de conexión hacia el origen de datos en el archivo application.properties bajo el puerto 8085.

