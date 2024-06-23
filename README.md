# Arch_Linux_TCL
-- Vamos a ver hasta donde llegamos con esta cuenston sere brutalmente honesto se trata de adentrarme desde el inicio ha esta distro como
entorno principal que empieze el juego!.

# boot in linux (ventoy)
Downloa ventoy in > https://ventoy.net/en/download.html
elegit el .tar.gz en mi caso
sudo fdisk -l
estar parado en la carpeta de ventoy descomprimida (cd Descargas/ventoy-1.0.99-linux)
sudo sh Ventoy2Disk.sh -I -s /dev/sdb
si ocure un error intentar desmontar con 
sudo umount /dev/sdb1
sudo sh Ventoy2Disk.sh -I -s /dev/sdb
y confirmarcon y
