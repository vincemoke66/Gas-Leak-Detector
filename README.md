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