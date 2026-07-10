------
Un grupo de VMs idénticas con carga equilibrada

Beneficio principales: 

- Automatiza creación, incremento o reducción de VMs
- Mantiene la consistencia de configuración 
- Soporta alta disponibilidad y balanceo de carga 
- No requiere intervención manual

### Conjuntos de escalado

- Aumenta instancias cuando la demanda crece 
- Reduce instancias cuando la carga disminuye

El escalado puede ser:

- Automático: basado en métricas (CPU, memoria, tráfico, etc.)
- Manual: definido por el administrador
- Combinado: mezcla de ambos métodos

### Características principales 

Permite administrar cientos de VMs sin tareas manuales de red o configuración 

Soporta escalado automático y balanceo de carga integrado 

Compatible con:

- Azure Load Balancer (Capa 4) -> tráfico básico TCP/UDP
- Azure Application Gateway (Capa 7) -> balanceo avanzado con TLS/SSL

### Recomendaciones - Examen de certificación

Los conjuntos de escalado (Scale Sets) están llevando las máquinas virtuales al siguiente nivel 

 Los Scale Sets pueden ejecutar VMs idénticas o diferentes, según el modo de orquestación elegido (Uniforme o Flexible)

- Uniforme: las VMs se crean a partir de una imagen base o plantilla 
- Flexible: se pueden mezclar distintos tamaños o configuraciones de VM

Aumenta el uso de recursos = el conjunto puede escalar automáticamente 

Sólo pagas por las maquinas virtuales, el almacenamiento y los recursos de red que usas. No hay coste adicional por usar conjuntos de escalado (Scale Sets)

