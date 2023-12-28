2023-12-17  ---  09:55
Type : Reference
Tags : #PWM

---
# What is PWM ?
---
Pulse width modulation or PWM is a technique for supplying electrical power to a load that has a relatively slow response. The supply consists of a train of voltage pulses such that the individual pulses controls the effective voltage level to the load.


![[Speed-Measurement-using-back-EMF-Technique.png]]

The effective voltage is given by:


$$V_{eff} = V_s \cdot \frac{\tau_o}{\tau_c}$$

## Skeleton of an Arduino Sketch using the analogWrite in controlling PWM output

```cpp
#include <Arduino.h>

// For the Arduino uno, the pwm pins are 3, 5, 6, 9, 10 and 11
constexpr int PWM_out_pin = 9; 

void setup() {
  pinMode(PWM_out_pin, OUTPUT); 
}

void loop() {
  byte PWM_out_level;

  PWM_out_level = ... // code logic to set output level

  analogWrite(PWM_out_pin, PWM_out_level);
}
```
The analogWrite function is used to set the duty cycle of a pwm pulse train that operates at approximately 500Hz. Thus with a frequency fc = 500Hz, the period is 1/fc => approx 2ms.

The parameter that sets the duty cycle is an 8-bit unsigned integer, ie., a value in the range of: 0 <= PWM_out_level <= 255.


Since for the arduino uno, vs is always 5V, for routine calculations, we can use the simple formula:

$$PWM_{\text{out}}\text{ level} = \frac{255}{5} \cdot V_{eff}$$

Therefore, to supply an effective voltage of 3V, use:
$$PWM_{\text{out}}\text{ level} = \frac{255}{5} \cdot 3 = 153$$


Another cool thing we can do is, lets say we want to use a potentiometer to vary the duty cycle at a particular pwm pin, we can do this by reading the analog value from an analogpin connected to the potentiometer, and multiplying that by a scaling factor to clamp the max value from the analog pin. Here is a skeleton:
```cpp
#include <Arduino.h>

constexpr float scaling_factor = 255.0f / 1024.0f;

void setup() {
	pinMode(A0, INPUT);
	pinMode(9, OUTPUT); }

void loop()) {
	analogWrite(9, analogRead(A0) * scaling_factor);
}
```

---
### References
---
