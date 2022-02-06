# Canon E410 Printer Server
Connecting Canon E410 Printer into home network using CUPS Printer Server

`sudo apt install cups`<br>

`sudo usermod -a -G lpadmin pi`<br>

`sudo cupsctl --remote-any`<br>

`sudo systemctl restart cups`<br>

`sudo apt install printer-driver-gutenprint` <br>


# Adding E410 Printer to Windows Machine via network

* Download and install Canon E410 drivers on your windows machine https://my.canon/en/support/0100764102 ( This might be tricky as the installation in the end might ask you to connect your Printer to the PC using USB. Just ignore it and close the  window using Task Manager.
* Follow steps from here https://github.com/apple/cups/issues/5987#issuecomment-950273204
