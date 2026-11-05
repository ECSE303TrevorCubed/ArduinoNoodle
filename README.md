# ECSE303 Lab Assignment 5
Group 11 Arduino Lab Notes
- Justin Fossum
- Trevor Nichols
- Trevor Swan

As per the Canvas assignment, this Lab only requires a notes submission.

## Notes
- `sudo usermod -a -G dialout group11` was used to add our group user to `dialout`
- We opened `arduino` from the terminal using `arduino`
- The first example we tried was the `Blink` example using the on-board LED
    - We selected it from `File` -> `Examples` -> `Basic`
    - Upon opening the example, we pressed the 'Upload' button and the LED flashed on and off every 1 second
- The second example we tried was the `Fade`
    - This example uses the PWM controller on the Uno
    - We connected the LED's power to pin 9 and the other end through ground
    - We selected it from `File` -> `Examples` -> `Basic`
    - We set up the LED with a 220 Ohm resistor and a red LED
    - The fading in and out was increased by a step of 5 every 30 milliseconds and decreased by 5 once the internal accumulator hit a maximum of 255
- The third example we tried was the `ReadAnalogVoltage` example
    - This example uses `analogRead` to read the analog signal from pin A0 on the Arduino
    - We selected it from `File` -> `Examples` -> `Basic`
    - We used a potentiometer with `out` connected to `A0` on the arduino, `grd` to `grd`, and `vcc` to `5V`
- We demoed the three examples to the TA on Thursday, November 5th