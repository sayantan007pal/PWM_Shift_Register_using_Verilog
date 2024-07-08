# PWM_Shift_Register_using_Verilog

PWM_Gen and ShiftReg Verilog Modules

Description

This Verilog project includes two main modules, PWM_Gen and ShiftReg, along with a testbench PWM_Test.

PWM_Gen:
Generates Pulse Width Modulation (PWM) signals based on preset duty cycles. It uses an internal counter and shifts the duty cycle values through a shift register.
ShiftReg:
A shift register that shifts input bits through an 8-bit register and latches the output.

Files

PWM_Gen.v: Generates 8 PWM signals with varying duty cycles.
ShiftReg.v: Implements an 8-bit shift register.
PWM_Test.v: Testbench for PWM_Gen.

Usage

1. Compile the Verilog files in Vivado.
2. Simulate using the provided testbench.
3. Verify the PWM output waveforms.

Simulation

Run PWM_Test.v to verify PWM signal generation and shifting functionality. The clock toggles every 1ns, and the simulation runs for 5000 clock cycles.
