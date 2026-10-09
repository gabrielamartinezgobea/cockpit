# cockpit

primero configuramos el netplan con la subred que se pide:
con el siguiente comando 
cd /etc/netplan 
sudo cp ![IMAGENES](images/2.png)
editamos el netplan para configurar el segmento de red clase C: 192.168.100.0/24  ![IMAGENES](images/3.png)


A continuación se describe brevemente las tareas que tendrá que realizar.

1. Actualizar los respositorios 
hacemos un sudo nano cockpit-install.sh
para crear el script para instalar cockpit   ![IMAGENES](images/4.png)
mediante este sscript basico:
![IMAGENES](images/5-script.png)

Luego damos el permiso de ejecucion al script cockpit-install.sh con
sudo chmod cockpit-install.sh ![IMAGENES](images/6.png)

Finalmente damos el ./cockpit-install.sh
para ejecutar
   
