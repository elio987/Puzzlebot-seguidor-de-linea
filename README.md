# Puzzlebot-seguidor-de-linea
Ambiente modificado del proyecto Puzzlebot de Manchester Robotics
- Puzzelbot en un pista de seguidor de linea.
- Copia los paquetes que aparecen en el src de tu WorkSpace.
- Al correr:
```
roslaunch puzzlebot_gazebo puzzlebot_gazebo.launch
```
- Corre en otra terminal:
```
rqt_image_view
```
- Al abrirse el rqt seleccione el topico:
```
/camera/image_raw
```
Y debe de verse al robot viendo una linea recta negra
- No olvides hacer catkin_make de tu worspace y el source devel/setup.bash al pegar los paquetes nuevos.
