<div align='justify';>

<div align="center">

# PROYECTO BASE DE DATOS 1 DAW

</div>

![Portada](https://github.com/Angel170605/Proyecto-BBDD/blob/main/img/basesdedatos.jpg)

<div align="center">

## ÍNDICE

</div>

* [Descripción](#descripción)

* [Diagrama ER](#diagramaentidadrelación)

* [Modelo Relacional](#modelorelacional)

* [Normalización](#normalización)

<div align="center" >

## DESCRIPCIÓN

</div>

Este es un proyecto grupal para la asignatura Base de Datos de 1º CFGS DAW (Desarrollo de Aplicaciones Web). El objetivo de dicho proyecto es la creación de una Base de Datos para una Universidad, en la que habrán entidades como alumnos, profesores, cursos, materias, etc. 
1. Crear el modelo *Entidad-Relación* de la Universidad, tras haber analizado todas sus entidades, propiedades y posibles relaciones entre las mismas.
2. Transformar el Diagrama Entidad-Relación creado previamente al Modelo Relaccional, teniendo en cuenta la cardinalidad de las relaciones del diagrama.
3. Realizar la normalización del Modelo Relacional resultante a la primera, segunda, tercera y cuarta forma normal.

![Universidad](https://github.com/Angel170605/Proyecto-BBDD/blob/main/img/universidad.jpg)

<div align="center">
   
## DIAGRAMA ENTIDAD RELACIÓN

</div>

El primero de los pasos quie debíamos seguir para poder crear la Base de Datos que nos propone el ejercicio era crear el Diagrama Entidad-Relación. Gracias a este diagrama, podemos ver de forma bastante clara la base de datos, con sus entidades y relaciones, además de que ya la estaremos preparando para completar los siguientes pasos de forma más sencilla. Este diagrama lo pudimos completar siguiendo tres pasos:

* Lo primero que hicimos fue identificar todas las entidades que estaban presentes en el enunciado. Encontramos un total de 16 entidades, ya fueran comunes, jerárquicas o incluso autoreflexivas.
* Ya una vez completado este paso, pasaríamos a analizar y establecer las distintas relaciones que se dan entre las entidades que hemos definido previamente, surgiendo de esta forma distintos tipos de cardinalidades.
* Una vez identificadas las entidades y definidas las relaciones que conectan las mismas, lo último que nos quedaba era ir conectando todas las entidades y relaciones, dando lugar al Diagrama Entidad-Relación que se nos pedía.

![Diagrama Entidad-Relación](Modelo-ER/Modelo-ER.drawio.png)

<div align="center">

## MODELO RELACIONAL

</div>

Ya una vez creado el DIagrama Entidad-Relación, era hora de convertirlo al Modelo Relacional. En este, las entidades pasan a ser tablas, además de que en determinados casos las relacionés también podrán generar de las mismas, dependiendo de su cardinalidad. Al igual que el resto, el Modelo Relacional lo hicimos en una serie de pasos:

* El primer paso que llevamos a cabo fue el de la conversión de las entidades a tablas. Estas tablas tienen el nombre y propiedades de la entidad, siendo la propiedad más importante la *PK* o *Primary Key* de la tabla. En el caso de las entidades que en el Diagrama ENtidad-Relación no tenían propiedades, se le asignaba automáticamente una *PK* con el nombre "id_nombredelaentidad".
* Ya creadas la stablas correspondientes a las entidades, quedaba relacionarlas entre sí, de la misma manera que en el diagrama del paso previo. Esta vez no era tan sencillo, pues se podían dar distintos casos dependiendo de las cardinalidades:
    * La relación genera tabla: En estos casos, había que crear una tabla con el nombre de la relación, la cual incluiría las PK de cada una de las entidades involucradas en la misma.
    * La relación no genera tabla: Por otro lado, cuando la relación no genera tabla, una de las entidades adoptará la PK de la otra como *FK* o *Foreign Key*, además de algunas de sus propiedades.

  Ya una vez completados lo9s pasos redactados en el apartado previo, ye teníamos nuestra Base de Datos convertida al Modelo Relacional.

![Modelo Relacional](https://github.com/Angel170605/Proyecto-BBDD/blob/main/Modelo%20Relacional/Modelo%20Relacional.drawio.png)

<div align="center">

##  NORMALIZACIÓN

</div>

Por último, nos queda normalizar la Base de Datos. Esto se hace principalmente para eliminar la redundancia de información, además de simplificar la base de datos con la información más importante. Este proceso se divide en distintas fases, conocidas como las *Fases Normales*, estando la *1FN*, *2FN*, *3FN*, *4FN*, y *5FN* (aunque este proyecto no llevaremos la normalización hasta esta última). 

<div align="center">
   
## AUTORES

### [Ricardo Zamora](https://github.com/21ricardozamora)

### [Ángel Pérez](https://github.com/Angel170605)

</div>

</div>
