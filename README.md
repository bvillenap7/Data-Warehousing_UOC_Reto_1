# Data-Warehousing_UOC_Reto_1
22.511- Bases de Datos para Data Warehousing – Actividad P1
Estudios de Informática, Multimedia y Telecomunicación
Semestre 2024-1 pag 8

La escuela infantil La Casa de Baloo nos pide que le ayudemos en la construcción de una base de datos que facilite la gestión de su actividad.
Los niños y niñas (a partir de ahora, criaturas) se agrupan según su edad en las aulas. Las aulas suelen recibir nombres de animales (delfines, leones,...). No existen dos aulas con el mismo nombre. También se quiere guardar el rango de edad de las criaturas de cada aula (edad mínima y edad máxima).
Cada criatura tiene un nombre propio (Javier, Eva, Paula, ...), que es lo que queremos almacenar en la base de datos. De cada criatura nos interesa saber su fecha de nacimiento y la fecha de incorporación a la escuela. Aunque podemos considerar que no habrá dos criaturas en una misma aula con el mismo nombre (en caso de ocurrir, se les suele identificar por el nombre y el apellido, por ejemplo Javier Pérez, y esto es lo que se almacenará en la base de datos), sí puede haber dos criaturas con el mismo nombre en aulas distintas. Nos interesa tener constancia de las criaturas asignadas a cada aula.
La escuela dispone de un conjunto de trabajadores, formados por personal de administración, cocineros y cuidadores. Nada impide que un mismo trabajador pueda realizar más de una de estas tareas. De los cuidadores, los hay con titulación y sin titulación. De cada trabajador queremos saber su nombre, dirección y carné de identidad, así como la fecha en la que entró a trabajar en la escuela; de los titulados nos interesa saber el año de expedición del título y los años de experiencia; de los cocineros nos interesa saber el año de expedición del carné de manipulación de alimentos; y del personal de administración el título que tienen (si tienen alguno).

Para cada aula hay un responsable (que debe ser un cuidador titulado), y un ayudante (que puede ser un cuidador titulado o no). Cada aula tiene una sola asignación de responsabilidad (un solo responsable y un solo ayudante); y un mismo cuidador, una vez asignado a un aula, no puede ser asignado a ninguna otra aula (ni como responsable ni como ayudante).
Cada criatura tiene una ficha (identificada por un código), que gestionan desde administración. Se quiere tener constancia de todos los cambios que ha sufrido la ficha, es decir, qué trabajador de administración ha creado la ficha y qué trabajadores de administración la han modificado (para añadir, eliminar o cambiar datos). Una misma ficha puede sufrir varios cambios en una misma fecha, cambios que pueden haber sido realizados por distintos administrativos.
Se pide: hacer un diseño conceptual de la base de datos haciendo uso del modelo entidad-interrelación. Indicar claramente qué requisitos no han quedado reflejados en el esquema que proponéis. Si habéis realizado alguna suposición semántica adicional, indicadla también.
