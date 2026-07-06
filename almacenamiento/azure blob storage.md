------
Almacenamiento de objectos seguro y escalable de forma masiva

¿Para que se puede utilizar?

- Cargas de trabajo nativas de nube 
- Archivos
- Data Lake
- Computación de alto rendimiento
- IA / Machine Learning

-----
### Características 

- Escalable, duradero y disponible
	- Excelente durabilidad por diseño con replicación geográfica

- Protegido
	- Autenticación con Microsoft Entra ID, control de acceso basado en roles (RBAC), cifrado y protección contra amenazas avanzada

- Optimizado para lagos de datos
	- El espacio de nombres de archivos y el acceso multiprotocolo permiten ejecutar cargas de trabajo y obtener valor a partir de los datos 

- Administración de datos completa 

--------
### Tipos de blob

#### Block (Bloque)

Almacena texto y datos binarios. Está compuesto por bloques individuales que se gestionan de forma separada. Ideal para cargas de datos masivas
#### Append (Anexo)

Contiene bloques optimizados para agregar datos al final del archivo. Es perfecto para escenarios donde se escriben registro de forma continua como logs o eventos.

#### Page (Página)

Permite el acceso directo a cualquier parte del archivo, lo que hace ideal para discos duros virtuales y entornos que requieren operaciones de lectura y escritura aleatoria 

-------
### Niveles de acceso para Blob Storage

#### Hot (Frecuente)

Enfocado para esos archivos a los que accedemos frecuentemente, con tiempos de acceso más bajos y costos de acceso más altos

#### Cool (Esporádico)

Enfocado para datos accedidos ocasionalmente. Menor costo que Hot, pero acceso más lento. Requiere permanecer al menos 30 días

#### Cold (Frío)

Optimizado para almacenar datos a los que rara vez se accede o modifica, pero que aún así requieren una recuperación rápida

#### Archive (Archivo)

Para datos a los que rara vez se accede. Costos de almacenamiento mas bajos y tiempos de recuperación más largos

------
### Estructura de Azure Blob Storage

Cuenta de almacenamiento -> Raíz del servicio

Contenedor -> organiza los blobs = carpetas

Blob -> El archivo en si 

![[Pasted image 20260706073028.png]]