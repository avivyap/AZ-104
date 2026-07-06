------

Una asignación de rol define quien puede hacer que sobre que recurso 

**1. Entidad de seguridad (Quién)**

Es una identidad a la que se le asigna un rol:

- Usuario <- Persona individual
- Grupo <- Conjunto de usuarios 
- Entidad de servicio <- Aplicaciones o servicios

**2. Definición de rol (Qué)**

Determina que acciones puede realizar la entidad de seguridad 

Roles mas comunes:

- Propietario <- Acceso total
- Colaborador <- Crear y administrar recursos
- Lector <- Ver recursos existentes
- Administrador de acceso de usuario <- Gestiona permisos

**3. Ámbito (Dónde)**

Define en qué parte de Azure se aplican los permisos:

 - Grupo de administración <- Nivel más alto
 - Suscripción <- Contiene grupos de recursos y recursos 
- Grupo de recursos <- Conjunto de recursos relacionados
- Recurso individual <- VM, BD o app

![[Pasted image 20260704095350.png|298]]

**4. Asignación de roles en Azure**

Proceso de unir:

- Entidad de seguridad (Quién)
- Definición de rol (Qué)
- Ámbito (Dónde)

![[Pasted image 20260704095918.png|697]]