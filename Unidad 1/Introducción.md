Características de los sistemas operativos

Transparencia {Los usuarios pueden tener acceso a todos los recursos del sistema}
	**Acceso transparente:** Los usuarios pueden acceder a los recursos sin necesidad de conocer la ubicación del mismo.
	**Ubicación transparente:** Los usuarios no necesitan conocer la ubicación física de los recursos.
	**Migración transparente:** Los procesos pueden moverse entre diferentes nodos sin que los usuarios se den cuenta
	
Recursos compartidos
Todos los recursos en un SOD pueden ser compartidos entre los diferentes nodos.
Maximiza la eficiencia del sistema al distribuir las cargas de trabajos y utilizar los recursos disponibles.

Escalabilidad
SOD puede escalar fácilmente añadiendo mas nodos al sistema. esto permite manejar mayores cargas de trabajo sin sacrificar el rendimiento.

Tolerancia a fallos
Los SOD están diseñados para ser tolerantes a fallos. Si un nodo falla, el sistema puede redistribuir las tareas a los demás. 

Concurrencia 
Múltiples procesos pueden ejecutarse simultáneamente en diferentes nodos, lo que mejora el rendimiento general del sistema.

Comunicación y coordinación 
Los nodos de un SD necesitan comunicarse y coordinarse entre si. Esto se logra a través de protocolos de comunicación como RPC (Remote Procedure Call) o mensajes.
La coordinación asegura que las tareas distribuidas se completen de manera eficiente y que los recursos no se usen en exceso o de manera ineficiente.