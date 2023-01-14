<p align="center">
	<img src='https://github.com/johnathanalyst/Arduino-Temp/blob/main/imgs/cover-slide.png' alt='Cover Slide'/>
</p>

# Arduino-Temp
Final project for Engineering Physics 223.

![Build Status](https://img.shields.io/badge/build-Stable-green.svg)
![License](https://img.shields.io/badge/license-NONE-green.svg)
<br/><br/>

# Prompt
The Analog Devices TMP36 Temperature Sensor is the most common digital device used to measure the ambient temperature of a system. However, what the device actually outputs is a voltage. Fortunately, the output voltage is proportional to the temperature, so it’s a matter of calibrating the voltage to conform with the temperature.

Write the Arduino code that receives input from the TMP36 sensor and outputs the Celsius temperature to the serial monitor using the formula you determined above. Some tips:

 * One particular line that will be helpful is Serial.println(temp_C); which will cause a line space to appear between data entries.
 * The analogRead command receives input from the sensor and converts it into a variable (note the sensor output is connected to Arduino analog port 0):
float voltage = analogRead(A0);
 * Add a 1 second delay (delay(1000)) between readings and limit the number of readings, unless you want to be overwhelmed by data. Note the delay value is in milliseconds.
<br/>

Email me@johnathanalyst.com with questions.

Enjoy!

## Prerequisites
* web browser
* TinkerCAD account
<br/><br/>


## Installation
```bash
git clone https://github.com/johnathanalyst/Arduino-Temp.git
```
<br/>

## Usage
Make a TinkerCAD account and create a new circuit. Import the ".brd" file into your project and run the simulation. Use the sliders to adjust the temperature for each circuit and see the response in the Serial Monitor (lower-right), and from the LEDs.

Feel free to ask me questions on [GitHub](https://github.com/johnathanalyst)

<br/>
<p align="center">
<img src='https://github.com/johnathanalyst/Arduino-Temp/blob/main/imgs/analog-temp-circuit.png' alt='Analog Circuit'/>
</p><br/>

<p align="center">
<img src='https://github.com/johnathanalyst/Arduino-Temp/blob/main/imgs/digital-temp-circuit.png' alt='Digital Circuit'/>
</p>
<br/>


## Authors
* **Johnathan Chivington:** [GitHub](https://github.com/johnathanalyst)

## Contributing
Not currently accepting outside contributors, but feel free to use as you wish.

## License
There is no license associated with this content.
<br/><br/>
