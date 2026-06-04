Huellitas es un sistema de gestión integral diseñado para optimizar los procesos
operativos, médicos y legales de un refugio de rescate y adopción animal. El
objetivo de este proyecto fue poder ayudar a la mejorar de los registros y en los
cuales antes de esta implementación digital habían sido un caos, ya que había
muchos problemas con los documentos a papel, por lo que se creo una base de
datos y una pagina web para que el refugio pudiera tener un alcance máximo ya
sea para encontrar adoptantes, o personas que estén interesadas en apoyar
mediante donaciones, ya sea económicos, alimentos o productos de limpieza.
Para poder crear este proyecto, nos ayudamos de diferentes practicas en las
cuales en cada una de ellas pudimos ir aprendiendo nuevas cosas asi como
herramientas para crear la logística y optimización de este mismo.
En la practica 1.
Fue básicamente el cómo nació todo el proyecto, y en lo que fue antes de que lo
metiéramos a código, ya que aquí se trabajó desde las problemáticas que había y
para dar una solución creamos un Modelo Entidad-Relación.
Practica 2.
Ante la implementación del MER descubrimos que estábamos un poco limitados
asi que gracias a esta practica pudimos crear un MER EXTENDIDO en el cual,
gracias a esto, pudimos tener una idea mas clara de lo que queríamos crear para
ofrecer al cliente,
Practica 3.
En esta practica descubrimos el Modelo Relacion, en el cual debíamos de
transformar en esto el MER EXTENDIDO, ya que aquí, se aplicaban reglas
matemáticas, jerarquías y definir como se propagaban las llaves, lo cual esto fue
de mucha ayuda, al momento de pasar a código nuestra idea de la solución que
teníamos.
Practica 3.1.
descubrimos el entorno de la nube y el alojamiento web. Aquí el reto fue crear una
arquitectura híbrida donde pudimos conectar nuestro frontend estático en GitHub
Pages con un backend dinámico en Render y bases de datos serverless en
Supabase. Esto nos ayudó muchísimo a entender cómo interactúan los sistemas
en producción y cómo proteger nuestras credenciales mediante variables de
entorno en el mundo real.
Practica 4.
Aquí fue el nacimiento físico de nuestra base de datos en código. Usando
PostgreSQL, empezamos a entender y aplicar sentencias DDL para estructurar
las tablas con restricciones reales de dominio, como los NOT NULL para campos
obligatorios, UNIQUE para evitar que se repitieran correos o INEs, y candados
CHECK para validar datos. Además, con las sentencias DCL, descubrimos cómo
implementar un esquema de seguridad basado en roles y permisos para que los
usuarios del refugio solo puedan hacer lo que su puesto les permita.
Practica 5.
Aquí nos enfocamos en la transaccionalidad y en ver cómo reaccionaba nuestro
sistema ante el estrés del mundo real usando DML. Desarrollamos scripts en
código para poblar la base de datos en tres niveles: desde algo leve para pruebas,
hasta cargas masivas de millones de registros en producción.
Practica 6.
Trabajamos con conjuntos de datos reales y desordenados de Kaggle para
llevarlos desde un estado confuso hasta la Tercera Forma Normal (3FN). Esta
práctica influyó en nuestro proyecto ayudándonos a identificar dependencias
parciales y transitivas, asegurando que nuestro propio diseño de nuestro proyecto
fuera completamente óptimo, eficiente y libre de redundancias o anomalías al
insertar, actualizar o borrar información.
Practica 7.
En esta práctica entramos de lleno a la fundamentación matemática de las bases
de datos con el Álgebra Relacional. Nos enfocamos en los operadores básicos
como la selección y la proyección, además de la teoría de conjuntos como la
unión, intersección y diferencia.
Practica 8.
Aquí subimos el nivel del álgebra relacional hacia operadores avanzados.
Descubrimos cómo funcionan matemáticamente las reuniones (JOIN), las
funciones de agregación (como COUNT, SUM o AVG) y las agrupaciones. Esto
influyó directamente en la capacidad de nuestro proyecto para generar reportes y
estadísticas eficientes.
Practica 9
Fue la culminación teórica de la materia, donde descubrimos el Cálculo
Relacional. A diferencia del álgebra relacional, aquí aprendimos a formular
consultas de manera declarativa usando lógica de primer orden con
cuantificadores existenciales y universales. Gracias a esto, pudimos demostrar la
completitud relacional de nuestro sistema, asegurando que la estructura de
nuestras tablas es tan robusta que es capaz de resolver cualquier consulta lógica
imaginable por el cliente de forma segura y finita.

https://github.com/gabrielhuav/DB-Coursework-2026-2