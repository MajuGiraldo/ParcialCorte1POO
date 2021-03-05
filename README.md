# ParcialCorte1POO

# CONCEPTOS

1. ¿Qué es encapsulamiento? ¿Qué ventajas ofrece?

RTA/ El encapsulamiento es un principio muy utlizado en Java y además una buena práctica de programación que consiste en limitar el acceso a las clases que hemos creado previamente para asi tener un mayor control sobre ellas, es decir, este principio hace que los atributos de las clases se puedan editar sólo a través de métodos. De manera general, se hace teniendo las propiedades como privadas y métodos que la controlan públicos. Estos métodos que nos permiten interactuar con los atributos de una clase se llaman métdos de acceso, también conocidos como getters y setters. Los setters se utilizan para definir los atributos de la clase, mientras que los getters se utilizan para poder acceder a estos atriutos, como si fueran una llave de acceso. 

El encapsulamiento tiene bastantes ventajas, pero las principales son: mantenibilidad, estabilidad y seguridad. El encapsulamiento nos asegura que estas caracteristicas se cumplan ya que al restringir el acceso a los atributos de una clase nos asegura que no cambiaran a  lo largo del tiempo por un agente externo generando una alteración a nuestro código, es decir, hace que nuestro código se mantenga con el tiempo y que ningún programador o persona externa pueda cambiar dichos atributos. La función principal del encapsulamiento es precisamente esa: limitar las interacciones de otra persona con nuestro código, y solo darle acceso a las cosas que con las que podra interactuar sin alterar el código interno que hace funcionar el programa o los atributos ya predefinidos por así decirlo.

2. ¿Qué es ocultación de información? ¿Por qué aplicarla? ¿Cómo se implementa en Java?

RTA/ La ocultación de la información, como su nombre lo indica, se encarga de esconder o hacer inaccesible datos o procesos a otras estructuras; pueden ser a otras clases, paquetes, etc. Esto con el objetivo de estas entidades comuniquen entre ellas solo la información importante o esencial. Es como si fueran entidades independientes que solo se transmiten entre sí la información que nosotros consideremos necesaria. Esta práctica se aplica principalmente para facilitar las pruebas, el manejo y las modificaciones que requiera el software. Se puede decir que la ocultación de información sirve como un criterio eficaz para dividir cualquier pieza del software en modulos de funcionalidad o interfaces, una independiente de la otra pero a la misma vez relacionadas. 

La ocultación de información se implementa en Java mediante tres niveles de acceso, los cuales son: Público (Public); Todos pueden acceder a los datos o métodos de una clase que se definen con este nivel, este es el nivel más bajo, esto es lo que tu quieres que la parte externa vea. Protegido (Protected); Podemos decir que estás no son de acceso público, solamente son accesibles dentro de su clase y por subclases y Privado (Private); En este nivel se puede declarar miembros accesibles sólo para la propia clase. Por último se imlemnetan los métodos getters y setters mencionados anteriormente.


# MAPA DE MEMORIA

![IMG_2192](https://user-images.githubusercontent.com/78317998/110185377-2dd4d000-7de0-11eb-85dd-2ae5a3fef74f.jpg)
