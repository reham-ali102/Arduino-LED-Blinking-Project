# Arduino-LED-Blinking-Project
This project demonstrates a simple Arduino circuit that makes an LED blink on and off. The circuit uses an Arduino UNO, an LED, a resistor, and connecting wires.

## Components

- Arduino UNO
- LED
- Resistor (220Ω recommended)
- Breadboard
- Jumper wires


## Circuit Connections

1. Connect the longer leg (anode) of the LED to one end of the resistor.
2. Connect the other end of the resistor to pin 13 on the Arduino.
3. Connect the shorter leg (cathode) of the LED to the GND pin on the Arduino.

## Code

Upload the following code to your Arduino UNO using the Arduino IDE:

```c
int ledPin = 13; // Define the pin where the LED is connected

void setup() {
  pinMode(ledPin, OUTPUT); // Initialize the LED pin as an output
}

void loop() {
  digitalWrite(ledPin, HIGH); // Turn the LED on
  delay(1000); // Wait for one second
  digitalWrite(ledPin, LOW); // Turn the LED off
  delay(1000); // Wait for one second
}
```

## Getting Started

1. Install the [Arduino IDE](https://www.arduino.cc/en/software).
2. Connect your Arduino UNO to your computer using a USB cable.
3. Open the Arduino IDE and copy the code above into a new sketch.
4. Select your Arduino board and port from the Tools menu.
5. Click the Upload button to upload the code to the Arduino.

## Simulation with Tinkercad

If you don't have the physical components, you can simulate this project using [Tinkercad](https://www.tinkercad.com/).

1. Create a new Tinkercad account if you don't have one.
2. Create a new circuit in Tinkercad.
3. Add an Arduino UNO, an LED, a resistor, and wires to your circuit.
4. Connect the components as described in the Circuit Connections section.
5. Copy the code into the code editor in Tinkercad.
6. Start the simulation to see the LED blink.

## Simulation Images

### Circuit Setup in Tinkercad
![Tinkercad Circuit Setup](https://github.com/reham-ali102/Arduino-LED-Blinking-Project/blob/main/switch-LED.PNG)

### Code Editor in Tinkercad
![Tinkercad Code Editor](https://github.com/reham-ali102/Arduino-LED-Blinking-Project/blob/main/LED.PNG)


