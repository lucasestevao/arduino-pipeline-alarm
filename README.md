# Arduino Pipeline Alarm
An Arduino experiment to let the team know when a pipeline/build fails. If the build fails the buzzer will play the Imperial March song lighting the red led as you remind of Darth Vader.

## Hardware information
The board I used to test is a NodeMCU 1.0 (ESP-12E Module).
- Upload Speed: 115200
- CPU Frequency: 80 MHz
- Flash Size: 4M (no SPIFFS)

## Developing

#### Preconditions
- [Arduino IDE](https://www.arduino.cc/en/Main/Software) installed
- [MAC Drivers](https://github.com/adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver) installed

##### Getting started
- Install the board on Arduino IDE following [this tutorial](https://randomnerdtutorials.com/how-to-install-esp8266-board-arduino-ide/)
- Install the dependencies `ArduinoJson` and `WiFi`
- Compile and Upload the code

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -a 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request


## License

<a href="http://opensource.org/licenses/MIT" target="_blank">The MIT License</a>