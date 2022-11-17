# ROS 2
versjon foxy.

## Gazebo
her er gazebo ikke installert fra starten av så det må installerest ekstra med kommandoen:

```Bash
sudo apt install gazebo11
``` 

det er ganske rett framm etter dette. versjonen fungerer og det er en nice forbedring fra ROS melodic som ville kjøre gazebo 9 uten skikkelige ssl sertifikater og en source link til en REST API server som ikke lenger er der gazebo spør etter...

- [gazebo relaterte notater](gazebo)

## drift av ROS 2
start med å kjøre:

```Bash
source /opt/ros/foxy/setup.bash
```

Ellers vil ikke kommandoen `ros2` fungere.  
Den kan selvfølgelig appendes til `~\.bashrc` for å være kjørt hver gang, men der god trening å være bevist på dette fra starten av.



