# ArduinoBlinkingLED
### Wiring

![header image](https://github.com/KKKirilov/ArduinoBlinkingLED/blob/master/IMG_20200710_234805.jpg)

### Code
```
void setup() {
  pinMode(5,OUTPUT);
}

void loop() {
  digitalWrite(5, HIGH);
  delay(500);
  digitalWrite(5, LOW);
  delay(500);  
}
```
