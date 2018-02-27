#DESCRIPCION
#Equipo 8
#Sistemas Embebidos
#Alvarez Gonzalez Salvador
#Garcia Miguel Luis Christian

#**Metodo SSH**
![SSH Deshabilitado](sshDisable.png "Comando : list-unit-files")
![SSH Status](sshStatus.png "Comando : sudo systemctl status ssh")
![SSH Start](sshStart.png "Comando : sudo systemctl start ssh")
![SSH Enable](sshEnable.png "Comando : sudo systemctl enable ssh")
![IP MAC](ipMAC.png "Comando : ifconfig")
![Hostname](hostname.png "Comando : hostname -I")
![NMap](nmap.png "Comando : nmap -p22 192.168.1.73/24")
![ARP](sshConnection.png "Comando : arp -v | grep da:71 && ssh pi@192.168.1.71")

#**Metodo VNC**
![VNC-x11 Deshabilitado](vncDisable.png "Comando : sudo systemctl list-unit-files")
![VNC Status](vncStatus.png "Comando : sudo systemctl status vncserver-x11-serviced")
![VNC Start](vncStart.png "Comando : sudo systemctl start vncserver-x11-serviced")
![VNC Enable](vncEnable.png "Comando : sudo systemctl enable vncserver-x11-serviced")
![VNC Enabled](vncEnableView.png "sudo systemctl status vncserver-x11-serviced")
![VNC Viewer](vncViewer.png "Login VNC Viewer")
![VNC Viewer Login](vncViewerLogin.png "Login VNC Viewer")
![VNC Connect](vncConnect.png "Conexion en Raspberry")
![VNC Connect Laptop](vncViewerLaptop.png "Conexion laptop")

#**Metodo UART**
![UART](configUART.png "Comando : sudo nano /boot/config.txt")
![UART USB](pin1.png "Identificando pin 1")
![UART USB](ConexionFisica.png "Conexion fisica")
![UART USB](ConexionFisica2.png "Conexion fisica")
![UART Terminal](UARTdev.png "Comando : ls -l /dev/ttyUSB0")
![UART Terninal](UARTid.png "Comando : id")
![UART Reboot](reboot.png "Reiniciando raspberry")
![UART Screen](UARTLogin.png "Comando : screen /dev/ttyUSB0 115200")
![UART Final](UARTFinal.png "Conexion exitosa")



