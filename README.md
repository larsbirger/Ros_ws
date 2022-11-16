# Ros_ws

## setup

installerte ubuntu 18.04.  
kjorte standard install av ros melotic full versjon  


fikk problemer med gazebo utdatert gazebo versjon  
kjorte komandoen
'''Bash
sudo apt-get install gazebo11-common gazebo11-plugin-base gazebo11 libgazebo11
'''
for aa oppdatere gazebo til versjon 11.


fikk saa feil paa hvordan VMWare kjorte grafikken. loste dette med aa kjore komandien
'''Bash
export SVGA_VGPU10=0
'''
og kommandoen
'''Bash
echo "export SVGA_VGPU10=0" >> ~/.profile
'''

for aa tvinge grafikk-aksellerasjonen til aa fungere



