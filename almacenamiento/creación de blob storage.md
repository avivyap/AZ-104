------
![[Pasted image 20260706073438.png]]

![[Pasted image 20260706073855.png]]

![[Pasted image 20260706074103.png]]

Habilitar el espacio de nombres jerárquico <- Esto lo que permite es transformar la cuenta de almacenamiento para que funcione como un sistema de archivos, con carpetas y subcarpetas 

##### Niveles de acceso

Frecuente <- Este es el nivel hot

Esporádico <- Este es el nivel cool

Acceso esporádico <- Este es el nivel cold

![[Pasted image 20260706074424.png]]

En el apartado de redes tenemos lo siguiente

En acceso público, si lo dejamos como esta, podemos acceder a la cuenta de almacenamiento desde cualquier IP

En seguro por perímetro, lo que hace es bloquear todo excepto lo que especifiquemos

En el ámbito de acceso a la red publica vamos a configurar si el acceso publico se limita a esa cuenta de almacenamiento o tambien a sus recursos hijos (si no necesitas acceso publico, lo mejor es quitarlo)

Punto de conexión privado, aquí es donde se permite que tu cuenta de almacenamiento sea accesible solo desde dentro de tu red virtual de azure (hace que se comporte como si fuese un recurso interno, sin salir a internet)

Por ultimo tenemos el apartado de "Enrutamiento de red", aquí es donde vamos a poder definir como se enruta el trafico hacia el servicio de almacenamiento, la primera evita que salga a internet publico y la segunda, es donde el trafico puede ir por internet publico antes de llegar al servicio (esta opción solo tiene sentido en entornos antiguos)

![[Pasted image 20260706075329.png]]

Habilitar la restauración a un momento dado para contenedores, esta opción lo que permite es restaurar uno o varios contenedores a un estado anterior en el tiempo 

Habilitar la eliminación temporal para blobs, esto lo que permite es recuperar blobs que han sido eliminados o sobrescritos

Habilitar la eliminación temporal para contenedores, lo mismo que antes pero para contenedores enteros

Habilitar la eliminación temporal de recursos compartidos de archivos clásicos, lo mismo pero aplicado a archivos compartidos

Habilitar el control de versiones para blobs, si queremos que un archivo tenga diferentes versiones

Habilitar la fuente de cambios del blob, esto permite registrar eventos, perfecto para análisis de logs 

Habilitar la compatibilidad con la inmutabilidad de nivel de versión, esto permite configurar políticas para que las versiones de los blobs no puedan ser modificadas o eliminadas durante un tiempo definido

![[Pasted image 20260706075932.png]]


Claves administradas por Microsoft (MMK)

Claves administradas por el client (CMK), en caso de que trabajemos en una empresa donde tenemos unas claves de cifrado, podemos usarlo y tendremos el control total del cifrado, pero esta opción NO se puede cambiar después de crear la cuenta 

Habilitar cifrado de infraestructura, es decir a parte del cifrado en reposo, es una capa adicional


