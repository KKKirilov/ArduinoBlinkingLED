# ArduinoBlinkingLED
### Wiring
![header image](https://github.com/KKKirilov/ArduinoBlinkingLED/blob/master/ImageWiring.jpg)

### Code
```C++
void setup() {
  pinMode(7,OUTPUT);
}

void loop() {
  digitalWrite(7, HIGH);
  delay(500);
  digitalWrite(7, LOW);
  delay(500);  
}
```
