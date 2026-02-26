# Python-POO-para-Jupyter-Notebook
La Programación Orientada a Objetos es un paradigma que nos permite organizar el código pensando en "objetos" de la vida real. En lugar de tener funciones sueltas y variables dispersas, agrupamos los datos y las acciones que les pertenecen en una sola unidad.
​Imagina que estás desarrollando un sistema para una veterinaria. En lugar de manejar listas de nombres y edades por separado, creas una entidad llamada "Mascota" que contiene toda esa información.

​2. Los Conceptos Fundamentales
​Para entender la POO, debemos diferenciar entre el diseño y la ejecución:
​A. La Clase (El Plano)
​Es la definición teórica. Es un molde que dice qué características tendrá un objeto, pero no es el objeto en sí. Por ejemplo, la clase Coche dice que todos los coches tienen color, marca y un motor.
​B. El Objeto (La Instancia)
​Es la materialización de la clase. Es el coche rojo de marca Toyota que está estacionado en tu garaje. En Jupyter, cada vez que ejecutas una celda creando un objeto, estás ocupando un lugar específico en la memoria de tu computadora.

​3. Anatomía de un Objeto en Python

​Un objeto se compone principalmente de dos elementos:

​Atributos (Datos): Son las variables que describen al objeto. Se definen dentro de un método especial llamado __init__ (el constructor).

​Métodos (Comportamiento): Son funciones que viven dentro del objeto y definen qué puede hacer. Siempre llevan el parámetro self, que es la forma en que el objeto se reconoce a sí mismo.

​4. Los Pilares de la POO
​Para que un sistema sea robusto, la POO se basa en cuatro reglas:

* ​Herencia: Permite crear una clase nueva a partir de una existente. Una clase Gato puede heredar de Animal, ahorrando código.

* ​Encapsulamiento: Protege los datos internos para que no se modifiquen por error desde fuera (usando guiones bajos como _password).

* ​Abstracción: Oculta la complejidad. Tú sabes usar el método conducir(), pero no necesitas saber cómo funciona la inyección de combustible por dentro.

* ​Polimorfismo: Diferentes objetos pueden usar un método con el mismo nombre pero comportarse distinto (un Circulo y un Cuadrado tienen el método dibujar(), pero el resultado es diferente).
