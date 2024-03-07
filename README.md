# Write a program to blink 3 LEDs with different color using arduino uno

---

## Requirement
  
 1.Arduino uno

 2.Bread Board

 3.Data cable
 
 4.Jumper Wire

**Arduino IDE** :  [Download IDE](https://www.arduino.cc/en/software)


## Program

```cpp

void setup() {
  for(int i=2;i<=4;i=i+1){
  pinMode(i, OUTPUT);
  }
}
void loop() {

  for (int i = 2; i <= 4; i = i + 1) {
    digitalWrite(i, HIGH);
    delay(50);
    digitalWrite(i, LOW);
    delay(50);
  }
}

```
