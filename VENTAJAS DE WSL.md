Ventajas de WSL

El Subsistema de Windows para Linux puede ser útil tanto para usuarios aficionados que empiezan a dar los primeros pasos en este sistema operativo como para usuarios avanzados y administradores de sistemas.
La finalidad principal de WSL es permitir a los administradores de sistemas, y a los programadores, usar todas las herramientas y todos los servicios de Linux directamente desde Windows sin tener que virtualizar nada más ni montar infraestructuras complicadas. 

WSL2 vs máquina virtual
Entonces, ¿qué ventajas (e inconvenientes) aporta WSL2 frente a instalar Linux en una máquina virtual como VirtualBox o VMware? La primera diferencia es que, mientras que un Linux en una máquina virtual está aislado, WSL2 está totalmente integrado con Windows, por lo que ambos sistemas pueden interactuar entre sí. Además, el Subsistema de Windows puede cargar Linux en tan solo un segundo, mientras que una máquina virtual es bastante más lenta a la hora de arrancar el sistema.

El consumo de recursos es también muy considerable. Mientras que WSL2 es muy ligero y gasta muy poca memoria RAM, una máquina virtual consume muchos más recursos en este aspecto.

Y, aunque es cierto que una máquina virtual ofrece más control y más opciones de personalización, Windows Subsystem for Linux solo se ejecuta cuando lo necesitamos, y solo carga los procesos y servicios necesarios para lo que necesitemos hacer.

Si no sabemos qué sistema usar, os recomendamos usar una máquina virtual cuando:

Necesitemos sacarle todo el provecho a Linux.
Tengamos previsión de escalabilidad en función de los niveles de producción.
Queramos usar un sistema operativo con interfaz y aplicaciones de entorno gráfico.
Vayamos a hacer un uso intensivo de la red en el que el rendimiento es esencial.
Y podemos optar por WSL cuando:

Queramos ejecutar comandos básicos de Linux.
Queramos gastar poca memoria y pocos recursos del PC.
Necesitemos eficiencia de almacenamiento.
No queramos/podamos/sepamos usar máquinas virtuales.
Queramos un acceso rápido al sistema de archivos, e interactuar con el sistema de archivos de Windows directamente.

Integración entre Windows y Linux.
Arranque rápido del entorno Linux.
Elevado rendimiento y baja necesidad de recursos.
Basado en máquina virtual (VM).
Núcleo completo de Linux.
Compatibilidad completa con llamadas al sistema.
Permite la utilización paralela de VMware y VirtualBox.
Permite la utilización más allá de los sistemas de archivo del sistema operativo.
