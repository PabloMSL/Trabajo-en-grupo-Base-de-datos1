<h5>Del Modelo al Script – Construcción de Bases de Datos Reales en SQL</h5>
Ficha:3202084
Programa:ADSO

Tabla de contenido:
1.Introduccion
2.Análisis y construcción de las bases de datos
3.Modelo E-R
4.Script SQL
5.DML
6.Conclusion

INTRODUCCION:
en la siguiente actividad por grupos se realizaran 2 Diagramas de entidad-relación , Implementacion completa mediante SQL y se cargar ejemplos con insert para la verificacion de las bases de datos y su funcionamiento

<h3>Análisis y construcción de las bases de datos</h3>

1.Elaboración del diagrama entidad-relación (E-R) para cada base de datos, reflejando las entidades, relaciones, cardinalidades y reglas de negocio.

Primera base de datos: Colegio(título)
Tablas creadas: 
(Las que salen en colegio.png)
Descripción: Se eligió un colegio como primera base de datos porque es bastante simple, aunque con la normalización hasta la 3FN, se creo una tabla Intermedia para hacer más fácil la carga de datos, las tablas creadas son en base a los alumnos y estudiantes, con sus cursos notas y matrículas, nada tan complicado, pero lo suficientemente entendible para practicar.
![Colegio](Colegio.PNG)

Segunda base de datos: 
Estación de policía (título)
Tablas creadas:
(Estación de policía.png)
Descripción: Para algo más complicado elegimos una estación de policía, la normalizamos hasta la 3FN, y se crearon varias tablas intermedias, por cosas como varios cargos para un solo criminal, y varios criminales para un solo cargo, para así evitar la sobrecarga de datos, cumpliendo con las FN, siendo un buen ejemplo de que mientras más complejo el sistema, más tablas necesita, y más coherencia y menos redundancia.
![Estacion de policia](Estación_de_Policia.png)


<h3>Script SQL</h3>

2.Implementación completa mediante scripts SQL con sentencias DDL (CREATE, ALTER, DROP) para la creación de tablas, claves primarias y foráneas, restricciones, índices y vistas.
Empesamos creando por la terminal las bases de datos para ver revisar el archivo (Sql Bases.sql)
Revisamos la creacion de las tablas
[Estacion de policia](estacion_policia.sql)
[Escuela](escuela.sql)

<h3>DML</h3>

3.Desarrollo de scripts DML (INSERT) que permitan validar la integridad y coherencia de la estructura.
[Estacion de policia](DML_estacion.sql)
[Escuela](DML_escuela.sql)
Operaciones de validacion y coherencia de la estructura
(DML_operaciones.sql)

