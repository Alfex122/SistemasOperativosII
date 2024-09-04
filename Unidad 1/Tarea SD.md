1. Tres ventajas y tres desventajas de los sistemas distribuidos con respecto a los centralizados:

Ventajas:
- Escalabilidad: Pueden crecer añadiendo más recursos fácilmente.
- Tolerancia a fallos: Si un componente falla, el sistema puede seguir funcionando.
- Rendimiento: Pueden procesar tareas en paralelo, mejorando el tiempo de respuesta.

Desventajas:
- Complejidad: Son más difíciles de diseñar, implementar y mantener.
- Seguridad: Tienen más puntos de vulnerabilidad potenciales.
- Consistencia: Es más difícil mantener la coherencia de los datos entre nodos.

2. Importancia de la transparencia en los sistemas distribuidos:

La transparencia es crucial en los sistemas distribuidos porque permite que el sistema se perciba y se use como si fuera un sistema único y coherente, ocultando la complejidad subyacente de la distribución. Esto facilita el uso y desarrollo de aplicaciones, ya que los usuarios y programadores no necesitan preocuparse por los detalles de la implementación distribuida.

3. Transparencia de red en los sistemas distribuidos:

La transparencia de red se refiere a ocultar los detalles de la comunicación y la conectividad entre los componentes del sistema distribuido. Los usuarios y las aplicaciones no deberían ser conscientes de cómo se transmiten los datos a través de la red, ni de la ubicación física de los recursos. Esto permite que el sistema se use como si todos los recursos estuvieran localmente disponibles.

4. Diferencia entre sistemas fuertemente acoplados y sistemas débilmente acoplados:

- Sistemas fuertemente acoplados: Los componentes están estrechamente interconectados y dependen mucho unos de otros. Cualquier cambio en un componente puede afectar significativamente a otros. Suelen ser más eficientes en términos de rendimiento, pero menos flexibles y más difíciles de modificar o escalar.

- Sistemas débilmente acoplados: Los componentes son más independientes entre sí y se comunican a través de interfaces bien definidas. Son más flexibles, fáciles de modificar y escalar, pero pueden ser menos eficientes en términos de rendimiento debido a la sobrecarga de comunicación.

5. Diferencia entre un sistema operativo de red y un sistema operativo distribuido:

- Sistema operativo de red: Proporciona servicios básicos de red y permite compartir recursos entre máquinas conectadas, pero cada nodo mantiene su propio sistema operativo local. Los usuarios son conscientes de la ubicación de los recursos y deben acceder explícitamente a las máquinas remotas.

- Sistema operativo distribuido: Funciona como un sistema único y coherente en múltiples máquinas. Gestiona todos los recursos del sistema de forma transparente, ocultando la distribución a los usuarios. Los usuarios ven el sistema como una única entidad y no necesitan conocer la ubicación de los recursos.

6. Diferencia entre una pila de procesadores y un sistema distribuido:

Una pila de procesadores, también conocida como sistema multiprocesador, consiste en múltiples procesadores que comparten una memoria común y están estrechamente acoplados dentro de un solo sistema. Por otro lado, un sistema distribuido está compuesto por múltiples computadoras autónomas conectadas a través de una red, cada una con su propia memoria y procesador. La pila de procesadores opera bajo un único sistema operativo, mientras que un sistema distribuido puede tener diferentes sistemas operativos en cada nodo.

7. "Imagen única" en sistemas distribuidos:

El concepto de "imagen única" (single system image) se refiere a la capacidad de un sistema distribuido de presentarse a los usuarios y aplicaciones como si fuera un único sistema coherente, ocultando la complejidad y la naturaleza distribuida del sistema subyacente. Esto permite que los usuarios interactúen con el sistema distribuido de la misma manera que lo harían con un sistema centralizado, sin necesidad de conocer los detalles de la distribución de recursos y procesos.

8. Cinco tipos de recursos en hardware y software que pueden compartirse de manera útil:

- Hardware: 
  1. Procesadores
  2. Almacenamiento (discos duros, unidades de estado sólido)
  3. Dispositivos de entrada/salida (impresoras, escáneres)

- Software:
  4. Archivos y sistemas de archivos
  5. Bases de datos

9. Importancia del balanceo de carga en los sistemas distribuidos:

El balanceo de carga es crucial en los sistemas distribuidos porque:
- Mejora el rendimiento general del sistema al distribuir el trabajo de manera equitativa entre los nodos disponibles.
- Evita la sobrecarga de nodos individuales, lo que podría llevar a cuellos de botella o fallos.
- Aumenta la disponibilidad y fiabilidad del sistema al evitar puntos únicos de fallo.
- Permite una mejor utilización de los recursos del sistema.
- Facilita la escalabilidad, permitiendo añadir o quitar nodos según sea necesario.

10. Escalabilidad en un sistema distribuido:

Un sistema distribuido se considera escalable cuando puede manejar un aumento en la carga de trabajo o en el número de usuarios sin una degradación significativa en el rendimiento. Esto puede lograrse de varias maneras:
- Escalabilidad de tamaño: Añadiendo más nodos o recursos al sistema.
- Escalabilidad geográfica: Expandiendo el sistema a través de áreas geográficas más amplias.
- Escalabilidad administrativa: Manejando fácilmente un aumento en el número de organizaciones o usuarios que utilizan el sistema.

Un sistema verdaderamente escalable debería poder crecer sin necesidad de cambios fundamentales en su arquitectura o diseño.

11. Mayor riesgo de seguridad en un sistema distribuido comparado con un sistema centralizado:

Los sistemas distribuidos presentan mayores riesgos de seguridad por varias razones:
- Más puntos de entrada: Cada nodo en el sistema es un punto potencial de ataque.
- Comunicación en red: Los datos que viajan entre nodos pueden ser interceptados o alterados.
- Complejidad: La naturaleza distribuida hace más difícil implementar y mantener políticas de seguridad consistentes.
- Autenticación y autorización: Es más complejo gestionar el acceso a los recursos distribuidos.
- Heterogeneidad: Diferentes nodos pueden tener diferentes niveles de seguridad o vulnerabilidades.
- Ataques distribuidos: Los sistemas distribuidos pueden ser más susceptibles a ataques coordinados desde múltiples puntos.