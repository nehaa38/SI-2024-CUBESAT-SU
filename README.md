# SI-2024-CUBESAT-SU
📡 Repository for Summer Internship 2024 "Intro To Cube-sat and Satellite Communication"

#Lab Exercies

##Lab-1 Introduction To ESP32

- [Datasheet ESP32](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/Datasheet-ESP32.pdf)

##Lab-2 Blinking Of LED

```C
#define LED1 2
#define LED2 27
#define LED3 33
#define LED4 19
void setup() {
  // initialize digital pin LED as an output.
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
  pinMode(LED4, OUTPUT);
}
void loop() {
  digitalWrite(LED1, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(100);                      // wait for a second
  digitalWrite(LED1, LOW);   // turn the LED off by making the voltage LOW
  delay(100);                      // wait for a second
  digitalWrite(LED2, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(200);                      // wait for a second
  digitalWrite(LED2, LOW);   // turn the LED off by making the voltage LOW
  delay(200);                        // wait for a second
  digitalWrite(LED3, HIGH);   // turn the LED off by making the voltage LOW
  delay(300);                      // wait for a second
  digitalWrite(LED3, LOW);  // turn the LED on (HIGH is the voltage level)
  delay(300);                      // wait for a second
  digitalWrite(LED4, HIGH);   // turn the LED off by making the voltage LOW
  delay(400);                      // wait for a second
  digitalWrite(LED4, LOW);  // turn the LED on (HIGH is the voltage level)
  delay(400);                      // wait for a second
  
}
```

##Lab-3 Dimming LED

Parameters FRom LED Datasheet

| Parameter | Values |
|---------|----------|
|Max Forward Current|30mA|
|Forward Voltage|1.85V|
|Colour|Red|
|Total Capacitance|45pF|
|Operating Range|-40 to 85 C|
