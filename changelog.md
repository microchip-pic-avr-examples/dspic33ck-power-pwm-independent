# dspic33ck-power-pwm-independent, release v1.0.0

### Release Highlights
This is the initial release demonstrating the basic configuration of a high-resolution PWM generator of the dsPIC33C family of devices. This example is part of a series of code examples highlighting specific operating modes and features.

### Features Added\Updated
In this initial version the on-board LED of the dsPIC33CK Digital Power Plug-In Module is toggled with a interval period of 300 ms, when the controller is running at maximum speed of 100 MIPS. After startup, PWM generator #3 is generating two 200 kHz independent PWM waveform with 25% duty cycle at the PWM3H/PWM3L outputs. By pressing the on-board push button USER on the Digital Power Development Board, the duty cycle of PWM3L is toggled between the 25% kHz and 50% while the PWM3H duty remains constant at 50% duty.



