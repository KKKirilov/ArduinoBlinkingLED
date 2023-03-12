# ArduinoBlinkingLED
### Wiring
![header image](https://github.com/KKKirilov/ArduinoBlinkingLED/blob/master/IMG_20200710_234805.jpg)

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
