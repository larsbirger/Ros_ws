# Ros_ws

## setup

installerte ubuntu 18.04.  
kjorte standard install av ros melotic full versjon  


### Gazebo

- [ekstern link](http://classic.gazebosim.org/tutorials?tut=quick_start)


fikk problemer med gazebo utdatert gazebo versjon  
fant et mulig svar her:  
- [ekstern link](https://answers.gazebosim.org//question/22263/error-in-rest-request-for-accessing-apiignitionorg/)
- [enda en ekstern link](https://classic.gazebosim.org/tutorials?tut=install_ubuntu&cat=install#Alternativeinstallation:step-by-step)
kjorte komandoen
'''Bash
sudo apt-get install gazebo11-common gazebo11-plugin-base gazebo11 libgazebo11
'''
for aa oppdatere gazebo til versjon 11.


fikk saa feil paa hvordan VMWare kjorte grafikken.
- [ekstern link](https://answers.gazebosim.org//question/13214/virtual-machine-not-launching-gazebo/)
loste dette med aa kjore komandien
'''Bash
export SVGA_VGPU10=0
'''
og kommandoen
'''Bash
echo "export SVGA_VGPU10=0" >> ~/.profile
'''

for aa tvinge grafikk-aksellerasjonen til aa fungere



