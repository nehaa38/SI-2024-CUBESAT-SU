# SI-2024-CUBESAT-SU
📡 Repository for Summer Internship 2024 "Intro To Cube-sat and Satellite Communication"

Cubesats are small and standardized spacecraft used primarily for research purposes, typically launched into space as secondary payloads on larger missions or as part of dedicated small satellite launch programs. Here's a comprehensive overview of cubesats:
### Characteristics of Cubesats:
#### Size and Form Factor:
Cubesats are small satellites with a standardized form factor based on cubic units called "units" or "U".
The most common size is 10 cm x 10 cm x 10 cm (1U), but larger configurations such as 2U (10 cm x 10 cm x 20 cm) and 3U (10 cm x 10 cm x 30 cm) are also prevalent.
They typically weigh between 1 to 10 kilograms, though larger variants exist.
#Lab Exercies
[ESP32](https://www.robotdazero.it/blog/esp32-i-segreti-del-suo-successo/)

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
