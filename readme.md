Trabajo práctico de Digital House en el que veremos el diseño y la definicion de tablas a traves de algunos ejercicios de diagramas

metodo de uso

    - clonar el repositorio

    - abrir el archivo html con el navegador


descripcion : se pensaran base de datos para diferentes escenarios


escenario 1: digital house

    desafio 1: 
    usuarios y cursos

        - crear tabla de usuarios que contengan : nombre,apellido,email,contraseña y categoria

        - crear tablas de cursos que tendra: titulo,descripcion,imagen,fecha de inicio, fecha de finalizacion y cupo maximo

        - los cursos tendran unidades con : titulo,descripcion y fecha de inicio

        - los usuarios podran estar asociados a los cursos

    desafio 2:
    contenido del curso

        -crear tabla clases, que contendra titulo, una descripcion, fecha de inicio y una marca de visibilidad

        -las clases contendran bloques. los bloques tendran un titulo y una marca de visibilidad, pueden ser de diferentes tipos: texto, video, presentacion, pdf o archivo

        -los bloques tambien tendran que poder guardar contenido sea texto o una url en caso de que el tipo sea video, presentancion, PDF o archivo

escenario 2: Bazar Digital

    desafio 1:
    base
        - el bazar vendera vajilla,juguetes y articulos de jardin, tendrá empleados comunes, un coordinador, empleados de mostrador y repositores

        -todos los articulos tendran nombre,precio,descripcion y stock, aclaran tambien si son de uso profesional

        -Todos los empleados tendrán nombre, apellido, dni, sueldo y un rol.

    desafio 2:
    stock y ventas
        -los empleados de mostrador son los unicos que pueden cobrar y tendran una caja donde guardar el dinero, los repositores podran ir a la bodega de almacenamiento
        
        -tambien necesitamos saber cuandos productos estan exhibidos y en el deposito

        - los empleados pueden vender un articulo generando una comision adicional del 10% del valor del articulo

        - para las ventas esperamos almacenar fecha,articulos,medio de pago y total de la compra