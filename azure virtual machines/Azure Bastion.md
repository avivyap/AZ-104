------

Plataforma como servicio (PaaS) totalmente administrada

Ofrece conexión RDP y SSH directamente desde el portal de Azure

Utiliza una conexión privada y cifrada 

Eliminando la necesidad de IP públicas

Administración remota segura -> Permite conectarse a recursos remotos sin exponerse a riesgos de seguridad 

### Requisitos

Roles requeridos (lectura)
-  El usuario debe tener rol de lector en:
	- La máquina virtual de destino
	-  La interfaz de red de la VM (con dirección IP privada)
	-  El recurso de Azure Bastion

Networking

- Azure Bastion se implementa en su propia subred dentro de una red virtual o una red emparejada
- La subred debe llamarse exactamente -> **AzureBastionSubnet**

![[Pasted image 20260710101235.png]]