Integrantes: Eduardo Díaz del Castillo, Abdiel Alveo, Astrid Hurley
Instalación de ROS (Representación del Conocimiento) LAB 1. Ambiente de trabajo

Lineamientos del proyecto:

Seguir el instructivo de la instalación de ROS. (ros-melodic-desktop-full)
Crear un entorno de trabajo para ejecutar un experimento de ROS.
Configurar el entorno del usuario para que pueda llamar los comandos de ROS como parte de los comandos del sistema operativo
Leer la documentación de ROS
Escribir un programa en C++, Python o Java que: Cada 5 segundos genere un número aleatorio, y lo envie a a traves de un topico de ROS hacia otro NODO, que lo reciba y lo grafique en cada interacción.
¿Qué se debe entregar?

Codigo del programa que genera los número aleatorios y el que lo recibe. Los archivos estan en la carpeta script dentro de my_first_package nombrados como talker.py y listener.py
Primero debemos tener una terminal corriendo roscore. En otra terminal compilamos rosrun my_first_package talker.py (Saliendo como resultado el programa de numeros aleatorios cada 5 segundos)
https://github.com/abdielalveo-cmd/Lab-1-de-IA-Intalaci-on-de-Ros/blob/master/rqt.png
