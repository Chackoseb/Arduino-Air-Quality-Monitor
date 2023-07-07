
<div align="center">
  <p>
      <img width="20%" src="/readme-essentials/arduino-icon.svg">
  </p>
  <b><h3> Air Quality Monitoring System </h3></b>
  <p> Making air quality monitoring and alert system using <a href="https://www.arduino.cc"> Arduino </a></p>
</div>
<br>

<br>

<br><br>

## Hardware Requirements
1. [Arduino Uno R3](https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us)
2. [MQ-135 Air Quality Sensor](https://www.elprocus.com/mq135-air-quality-sensor/)
3. 16 x 2 LCD Display
4. LEDs
5. Buzzer
6. Breadboard and Jumper Wires
7. 10K Potentiometer
8. USB cable type A/B

<br>

## Software Requirements
 &nbsp;  &nbsp; <a href="https://www.arduino.cc/en/software"><img src="/readme-essentials/arduino-ide-logo.svg" width="40"></a>

<br><br>

## Block Diagram
 <img src="/readme-essentials/block-diagram.png" width="600"></a>
 <br>

## Implementation
<br>

  <img src="/readme-essentials/circuit-diagram.jpg" width="600">
  <br>
  The implementation process of the air quality monitoring system involves several key steps :
 <br><br>
 A) Hardware Setup: Connect the components, including the Arduino Uno processor, MQ-135 sensor, LCD display, LEDs, buzzer, and other necessary hardware, on a breadboard or a suitable circuit board. 
 <br><br>
 B) Wiring and Connections: Use jumper wires to establish the necessary electrical connections between the components. Refer circuit diagram.
 <br><br>
 C) Arduino Programming: Write the code in the Arduino programming language using the Arduino IDE. The code should include instructions for reading sensor data, displaying the data on the LCD screen, and implementing any desired features such as alerts.
 <br><br>
 D) Upload Code: Connect the Arduino Uno to the computer using a USB cable and upload the code to the Arduino board using the Arduino IDE.
 <br><br>
 E) Calibration: Calibrate the air quality sensors based on the manufacturer's specifications and any additional calibration procedures identified during the system design phase. This step ensures accurate measurements and reliable data.

 
<br><br>

## How It Works
<br>
  A) Gas Detection: The system utilizes the MQ-135 gas sensor to detect and measure the concentration of harmful gases in the indoor environment. The sensor is highly sensitive and capable of detecting gases such as carbon monoxide, nitrogen dioxide, ammonia, and benzene.

 <br><br>
 B) Data Processing: The sensor readings are collected and processed by the Arduino Uno board, which serves as the central processing unit of the system. The Arduino board converts the analog readings from the gas sensor into meaningful digital values for further analysis.

 <br><br>
 C) Threshold Comparison: The system compares the digital values obtained from the gas sensor against pre-defined thresholds for air quality. These thresholds determine the safe levels of gas concentration. If the measured gas concentrations exceed the safe thresholds, the system proceeds to activate the alert system.

 <br><br>
 D) Alert System Activation: When the gas concentrations exceed the safe thresholds, an intelligent alert system is triggered. The system activates a buzzer to generate audible alerts and illuminates LED indicators to provide a visual indication of the severity of the air quality issue.

 <br><br>
 E) User Monitoring and Action: Homeowners can monitor the air quality levels in real-time through the user-friendly LCD display provided by the system. The display shows the detected gas concentrations and any active alerts. Upon receiving the alerts, users can take appropriate actions, such as opening windows for ventilation, identifying potential sources of pollution, or seeking professional assistance.


<br><br>

## Working Video:
<video width="320" height="240" controls>
  <source src="/readme-essentials/general.mp4" type="video/mp4">
</video>
<br><br>

### Detecting Smoke:
<video width="320" height="240" controls>
  <source src="/readme-essentials/smoke.mp4" type="video/mp4">
</video>
<br><br>

### Detecting Gas:
<video width="320" height="240" controls>
  <source src="/readme-essentials/gas.mp4" type="video/mp4">
</video>


<br>

## Special Thanks:
 [MakerGuides](https://www.makerguides.com/)


<br>

## Checkout Our Documentation:
[Project Presentation](/readme-essentials/presentation.pptx) <br>
[Project Report](/readme-essentials/report.pdf)

<br><br>

