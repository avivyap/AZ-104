------

![[Pasted image 20260703124132.png]]

### SCIM

Este protocolo permite intercambiar datos de identidad entre sistemas de manera automática 

Permite integrar aplicaciones y sistemas con Microsoft Entra ID
#### Componentes:

- Sistema HCM <- El origen de los datos, donde esta el capital humano
- Microsoft Entra ID <- El destino donde se crean los usuarios
- Sistema de destino <- Es cualquier aplicación que soporte SCIM 
- Microsoft Entra Provisioning Service <- Es la pieza que conecta el origen y el destino mediante APIs

Este protocolo se utiliza para poder automatizar intercambiar información, creación automática de usuarios, sincronizar atributos, eliminación segura

