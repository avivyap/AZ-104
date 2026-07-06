------
Cada usuario es una cuenta de Azure que puede acceder a los recursos 

### ¿Que pasa cuando un usuario se autentica?

Se crea un token de acceso (como una llave temporal, la cual dice a que recursos puede entrar y que acciones puede hacer)

### Tipos de usuarios

- Identidades en la nube -> Se crean en Microsoft Entra

Por ejemplo: Un usuario creado manualmente en el portal de azure 

- Identidades sincronizadas por directorio -> Usuarios que provienen de un AD local, se sincronizan con Microsoft Entra Connect

Por ejemplo: Usuarios de Windows Server AD

- Usuarios invitados -> Cuentas fuera de Azure, tienen acceso de usuario invitado y se pueden eliminar en cualquier momento junto con los permisos asociados 

### Añadir usuarios de manera masiva

Puedes descargar el .csv y crear usuarios de manera masiva 

![[Pasted image 20260703112805.png]]
### Importar usuarios de otro tenant

Siempre que quieras invitar a otros usuario de otro dominio, tendrás que hacerlo a través de "Invitar a un usuario externo"
