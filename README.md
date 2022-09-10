# Generic Debian Pi ( 03-09-2022 V 1.0 Beta )

![alt text](https://i.imgur.com/tWxxdRX.png)

## Français : 

Mon projet est un ensemble de scriptes qui facilitent la construction d'images génériques Debian pour les hardwares Raspberry pi. Pour le moment, le projet est en phase bêta et sera amené a être mis à jour. 

Le fonctionnement est simple. Vous devez indiquer pour quel Raspberry pi vous souhaitez construire une image et indiquer la version de l'image si le Raspberry pi a un processeur 64 bits. 

Par défaut, le nom d'utilisateur est "pi", le mot de passe est "raspberry" et le nom d'hôte est "a404dded". Vous pouvez changer ça en modifiant les 3 premières variables du fichier "config_variables". 

Si vous désirez changer la version de Debian, vous devez modifier la variable "RELEASE" dans le fichier "config_variables". Étant donné que mon projet utilise l'outil Debootstrap pour générer les racines des images, il est également possible de construire une image Ubuntu. Dans la prochaine version de ce projet cette possibilité sera plus accessible.

## English : 

My project is a set of scripts that makes easier to build a pure generic Debian image for the most Raspberry pi sbc hardware. For the moment, the project is in beta stage. I plan to update it. 

The using is easy. You have to write for which Raspberry pi you would like to build an image. If the CPU is an aarch64 ARM, you also have to write the version of the OS. 

By default, the username is "pi", the password is "raspberry" and the hostname is "a404dded". You can change that by the editing the 3 firsts variables from the file "config variables".

If you wish to change the Debian version, you have to edit the variable "RELEASE" from the file "config_variables". Seen that my project is using Debootstrap for the rootfs base generating, is also possible to build an Ubuntu image. In the next version of my project, this possibility will be more easier to access. 
