# This section is about raspberry and its control over arduinos:

  * It has a file called control.py, there is the code that receives commands from the web server, makes the necessary 
    corrections and sends them to the arduino using UART.
    
  * It runs over python3. To run the script, just type: python3 control.py.
  
  * Also there is need to give permission to the USB port used over arduino -> raspberry. To do it, check in wich port
    is connected the arduino with: ls /dev | grep tty. Then type: sudo chmod 777 /dev/ttyXXX, replacing XXX with the po
    rt name.
  