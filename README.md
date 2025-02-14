# Laboratorio 4 - Desarrollo del paquetes
Este laboratorio busca brindar las bases en el desarrollo de paquetes en ROS2 Humble que logren correr nodos dentro del grafo de ejecución. Estos nodos se comunicarán por medio de **topics**, para publicando y suscribiendo datos de interés para el sistema. 

### Objetivos específicos
- Entender el proceso de creación y desarrollo de paquetes en ROS2
- Comunicar nodos en el grafo de ejecución por medio de `topics`, publicando y suscribiendo información.
- Ejectura múltiples nodos en el grafo levantando un archivo `launch`
- Emplear ROS Toolbox de Matlab dentro del flujo de ROS2, para acceder y modificar la información del grafo.
- Conectar un sistema físico que responda a las señales de ROS2

> Durante la práctica, se usará turtlesim como paquete base para visualizar y controlar un sistema (la tortuga) a partir del flujo de información propuesto.

 

### Requisitos
Para el desarrollo de este laboratorio, se exige lo siguiente: 
- Tener instalado **ROS2 humble**
- Si está en **Windows**, tener instalado _VS Community 2022_
- 


## Configuración de desarrollo 
### Construcción de workspace 

### Desarrollo de paquetes 

## Turtlesim 
Es un paquete base de ros usado como primer acercamiento a la herramienta. Consta de una tortuga mobil en un espacio plano con los siguientes tópicos: 

- `/turtle1/cmd_vel`:
- `/turtle1/color_sensor`:
- `/turtle1/pose`:

### ROS Toolbox Matlab

