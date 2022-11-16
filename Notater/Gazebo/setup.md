# Gazebo setup

[Gazebo](http://classic.gazebosim.org/tutorials?tut=quick_start) skal egentlig fungere rett ifra ROS Melotic complete med å kjøre kommandoen:
```Bash
gazebo
```

Så enkelt er det ikke alltid...  
Fikk av en eller annen grunn [problemer](https://answers.gazebosim.org//question/22263/error-in-rest-request-for-accessing-apiignitionorg/) med at gazebo haddet utdaterte ssl sertifikater og linket til en utdatert REST API. virker som om dette er noe en fikser med å [oppdatere](https://classic.gazebosim.org/tutorials?tut=install_ubuntu&cat=install#Alternativeinstallation:step-by-step) gazebo versjonen til versjon 11.

Kjørte komandoen:

```Bash
sudo apt-get install gazebo11-common gazebo11-plugin-base gazebo11 libgazebo11
```


Fikk så feil på hvordan VMWare kjørte [grafikken](https://answers.gazebosim.org//question/13214/virtual-machine-not-launching-gazebo/).  
Løste dette med å kjøre komandoen:

```Bash

export SVGA_VGPU10=0
```
Og kommandoen:

```Bash
echo "export SVGA_VGPU10=0" >> ~/.profile
```

Det virker nå som om Gazebo fungerer.