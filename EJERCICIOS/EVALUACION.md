## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?  (valor 1.5)
   
    R= Acceder, modificar, actualizar, controlar y eliminar

3. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)
   
   R = Definición de los datos. 
       Manipulación de los datos.
       Preservar la seguridad e integridad de los datos. 
       Recuperación y restauración de los datos.
       Garantizar la disponibilidad de la base.
   
5. En una BD al usuario del sistema se le brindarán recursos para realizar diversas operaciones sobre estos archivos, tales como: (valor 1.5)
   
   R= Crear, editar y mantener los archivos de la base.
   
6. ¿Qué es un Sistema de Información? (valor 1.5)
   
   R= Elementos que se usan en el tratamiento y administración de datos, organizados y para poder utilizarse y resolver necesidades.




## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.

![image](https://github.com/JatzArroyo/Base_de_Datos/assets/111532416/21b38d48-e416-4b88-8bab-7a76fa802ef0)

