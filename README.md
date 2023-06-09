# Gas-Leak-Detector

## TODO

## IN-PROGRESS

## FOR TESTING

## COMPLETED
- [x] Update gas level display
- [x] Finalize the whole system
- [x] Create a Partial System
- [x] Test the load cell/weight sensor
- [x] Test the buzzer
- [x] Test the smoke sensor
- [x] Test the LCD

## NOTES
- Amplifier and Load Cell connection
  - E+ -> red
  - E- -> black
  - A- -> white
  - A+ -> green

## SUGGESTIONS

## How to upload code to the Arduino
1. Download Arduino IDE with this [link](https://wiki-content.arduino.cc/en/software) and select your appropriate OS.
  ![arduino os selection](assets/ArduinoDownloadGuide.png)
2. Install the software.
3. Install required libraries by going to `Sketch` -> `Include Library` -> `Manage Libraries` -> then in the search bar, search the necessary library to install.
4. Necessary Libraries: 
  - `LiquidCrystal I2C` by *Frank de Brabander*
  - `HX711_ADC` by *Olav Kalhovd*
5. You can now add the code you want to upload to your arduino. Make sure to connect your arduino to your computer and select correct port and correct board.
6. Click the dropdown above and type in `Arduino Uno` in the search box then select the corresponding board.
  ![port](assets/arduino%20ports.png)
  ![board](assets/arduino%20board%20and%20port.png)
7. After doing these, you can now upload your code into your arduino and see it run!
  ![upload button](assets/upload%20button.png)