# L3mon-All_deb
original de D3vl R.A.T L3mon botnet 

# se puede usar desde termux también.
# es mejor usar un chroot en termux para mejor compatibilidad 
Y facilidad.
Ejemplo :
Nethunter Rootless 

https://www.kali.org/docs/nethunter/nethunter-rootless/

(Iniciar el entorno una vez instalado con ( nh) o ( nethunter )
Ahí dentro usar todo lo que necesites.

# es mejor instalar metasploit antes de usar L3mon.
Así como también: apktool , apksigner ,etc..

###########################################

apt update
apt upgrade -y
apt install wget -y
apt install python -y && apt install python2 -y
wget https://raw.githubusercontent.com/Hax4us/Apkmod/master/setup.sh
bash setup.sh

#############################################

termux-setup-storage
apt install nodejs -y && npm install -g npm@6.14.10 -y

(Descargar .deb l3mon y estara en descargas del celular
termux-setup-storage ayuda a traspasarlo...)


mv /data/data/com.termux/files/home/storage/downloads/ (elArchivoDescargado.deb)
 $HOME


AHORA :

dpkg -i (archivol3mon.deb)

################################################
(El password se debe setear con un hash md5 en el archivo 
maindb.json , entre las comillas "" de password...)

Guardar cambios .

Iniciar l3mon 

Esta en localhost y el puerto es 22533 ...
Y el 
Usuario : admin
Password : (aquí clave en letras , el hashMd5 solo va en el maindb.json "encriptado")


##############################################

Buena suerte.
