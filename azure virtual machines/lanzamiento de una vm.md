------
Basicamente configuras todo lo que quieras que tenga la maquina virtual 

![[Pasted image 20260707165334.png]]

Luego en tamaño puedes configurar la RAM de la maquina 

![[Pasted image 20260707165554.png]]

Una vez que creamos una maquina virtual, se nos va a crear dos grupo de recursos sobre esa maquina, uno de ellos es el grupo de recursos de la maquina virtual como tal 

![[Pasted image 20260708100654.png]]

Y el otro `NetworkWatcherRG` sirve para que Azure pueda supervisar y diagnosticar la red de tus máquinas virtuales y otros recursos
### Eliminar una VM

Si queremos eliminar una maquina virtual y todo lo que la engloba, lo mejor es irnos a grupos de recursos y eliminar el grupo de recurso como tal (el grupo de recursos incluye la ip, la maquina virtual, la key para conectarte...)

