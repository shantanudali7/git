# Arduino Demo Instructions

## Getting Started
1. Install Arduino IDE from [arduino.cc](https://www.arduino.cc)
2. Connect your Arduino board via USB cable
3. Open Arduino IDE and select Board and COM Port

## Basic Setup
- Go to **Tools** → **Board** and select your Arduino model
- Go to **Tools** → **Port** and select the connected COM port
- Click **Upload** button to program the board

## Example Code
```cpp
void setup() {
  Serial.begin(9600);
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```

## Useful Resources
- [Arduino Official Documentation](https://docs.arduino.cc)
- [Arduino Community Forums](https://forum.arduino.cc) 
