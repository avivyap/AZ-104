-------
### Azure AD DS

Es un servicio gestionado por microsoft que nos facilita la implementación de servicios de dominio de azure 

- Autenticación, autorización y aplicación de políticas para aplicaciones y usuarios

Es esencial para las organizaciones que desean migrar aplicaciones al cloud sin perder las funcionalidades del AD DS tradicional 

Permite unificar el manejo de identidades corporativas en entornos híbridos

Soporta protocolos de autenticación antiguos, NTLM y Kerberos

##### ¿Como funciona Azure AD DS?

Al ser un servicio gestionado no instalas ni configuras un S.O

Lo primero que hacemos es crear un nombre de dominio

La sincronización de datos es unidireccional, de Microsoft Entra ID a Azure AD DS

Entra ID tambien se puede sincronizar bidireccionalmente con AD Local

#### Casos de uso

- Migración de aplicaciones, para aplicaciones on-premises que dependen del AD DS y se están moviendo a Azure
- Desarrollo y pruebas

![[Pasted image 20260703125953.png|279]]

## Comparación entre Entra ID vs AD DS

![[Pasted image 20260703130633.png]]
