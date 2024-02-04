# arduino33sense
Board Arduino 33 SENSE BLE
https://docs.arduino.cc/hardware/nano-33-ble-sense/#features

## Arduino C/C++
Arudino-cli, vs-code
ARM CMSIS-DAP compatible, Arduino Mbed OS Nano Boards
https://arduino.github.io/arduino-cli/
https://learn.sparkfun.com/tutorials/efficient-arduino-programming-with-arduino-cli-and-visual-studio-code/all

## MicroPython
Arduino MicroPython Installer here
ampy via pip installieren und nutzen
https://www.digikey.ch/en/maker/projects/micropython-basics-load-files-run-code/fb1fcedaf11e4547943abfdd8ad825ce
export AMPY_PORT=/dev/tty.usbmodem0000000000001
ampy ls
ampy run test.py

### Access console REPL via
screen /dev/tty.usbmodem0000000000001 115200
CTrL-a k to kill

### Mpremote (pip module via serial installieren)
https://docs.micropython.org/en/latest/reference/mpremote.html
