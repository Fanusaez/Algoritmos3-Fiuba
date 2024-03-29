# Trabajo Prctico 1 

## Objetivo
Este es un trabajo práctico individual que tiene como objetivo aplicar los conceptos del paradigma de la orientación a objetos vistos hasta ahora en el curso mediante la resolución de un problema con Pharo.



## Consigna
Se deberá desarrollar un modelo de clases utilizando la metodología TDD. Las especificaciones son un archivo de pruebas SUnit (.st) adjunto a este enunciado y están dadas en forma de pruebas de casos de uso. Se espera que el alumno genere una solución que permita ejecutar exitosamente las pruebas especificadas manteniendo una alta cobertura y evitando la supervivencia de mutantes. Revisar el material Calidad de nuestras pruebas.


## Alcance
Se deberá desarrollar el modelo completo de la aplicación, sin incluir la interfaz gráfica. Para esto se especifica una API que está descrita por un conjunto de casos de uso. Este conjunto de pruebas está descrito por la clase dada como enunciado.

Para el manejo de errores y situaciones de excepción, se deberán desarrollar y utilizar las excepciones que se crean convenientes, más allá de que en la prueba de integración provistas no necesariamente se manejan excepciones.

Deberán entregarse:

todas las clases con sus métodos que resuelven el problema, organizados en una o más categorías según criterio del alumno;
conjunto de pruebas que garanticen la no supervivencia de mutantes;
un archivo "txt" que contenga la pieza de código que permite ejecutar los test de mutación (descrito aquí: pruebas de mutación);
documentación completa del diseño de clases incluyendo diagramas UML de clases y secuencia (cantidades variables acordes al diseño presentado).
Se considerarán entregas válidas a aquellas que contengan las partes anteriores. Las que no lo tengan alguna de ellas no serán tenidas en cuenta y se priorizará la corrección de aquellas que estén completas.


## Informe
El informe deberá tener una carátula que incluya los nombres y apellidos del alumno, su número de padron y dirección de correo electrónico. Además, deberá tener las siguientes secciones:

 ### Supuestos
 - Deberá contener explicaciones de cada uno de los supuestos que el alumno haya tenido que adoptar a partir de situaciones que no estén contempladas en la especificación.
 - Detalles de implementación
 - Explicar que pilares del paradigma empleó para modelar sus clases; describiendo ventajas, desventajas (de los pilares) y las clases donde lo aplicó.
 - Explicar porque utilizó herencia o delegación; describiendo ventajas, desventajas y las clases donde las aplicó.
 
### Excepciones
 - Explicación de cada una de las excepciones creadas y con qué fin fueron creadas.
 
### Diagramas de clases
 - Uno o varios diagramas de clases mostrando las relaciones estáticas entre las clases.  Puede agregarse todo el texto necesario para aclarar y explicar su diseño. Recuerden que la idea de todo el documento es que quede documentado y entendible cómo está implementada la solución. Todos los diagramas tienen que estar embebidos como imágenes en el informe de manera tal que entren en el ancho de una hoja A4 sin tener que rotarla. No se aceptarán diagramas en archivos sueltos.
 
### Diagramas de secuencia
 - Mostrar las secuencias interesantes que hayan implementado. Pueden agregar texto para explicar si algo no queda claro.
a concisa).


## Forma de entrega
La solución deberá ser desarrollada en su totalidad dentro dos paquetes:

 - TP1, en donde se ubicarán todas las clases que resuelven el problema;
 - TP1-Tests, que deberá contener todas las clases de pruebas creadas por el alumno.
Para la entrega deberá hacerse un File Out de estos dos paquetes (solamente estos dos, las pruebas especificadas por la cátedra no deben entregarse).

El entregable será un archivo comprimido en formato .zip que deberá llamarse <curso>-TP1-<numero de padrón>.zip, en donde <curso> es 1 para el curso de la tarde y 2 para el de la noche. Deberá contener únicamente los siguientes archivos:

 - TP1.st
 - TP1-Tests.st
 - TP1-Mutalk.txt
 - <número de padron>-tp1s.pdf

Criterios de corrección

Modelo
¿Está completo? ¿Contempla la totalidad del problema?
¿Respeta encapsulamiento?
¿Hace un buen uso de excepciones?
¿Utiliza polimorfismo en las situaciones esperadas?
Diagramas
¿Está completo el diagrama de clases?
¿Está bien utilizada la notación en el diagrama de clases?
¿Está completo el diagrama de secuencia?
¿Es consistente con el diagrama de secuencia con el diagrama de clases?
¿Está bien utilizada la notación del diagrama de secuencia?
Código
¿Respeta estándares de codificación?
¿Está correctamente documentado?
Pruebas
¿Hay suficiente cantidad de pruebas? ¿Es buena la cobertura?
¿Los nombres de las pruebas son adecuados?
¿Las pruebas son realmente unitarias?
Generalidades
¿Son correctos los supuestos y extensiones?
¿Es prolija la presentación del informe?
