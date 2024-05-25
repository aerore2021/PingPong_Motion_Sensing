# PingPong_Motion_Sensing
A motion sensing game of ping-pong comptetition, based on Basys and STC89C52RC.  
It's a group project, I was in charge of Verilog code.  
As for C++ in STC89C52RC, I have no rights to access.  
**But the backbone of the whole game is implemented by Verilog:**  
- First, we determined the signals of in/outputs, and derived the state machine of the game.
- Then, we wrote the Verilog code to implement the state machine.
- In the meantime, we debugged 52 microcontrollers and ADXL345 accelerometers to transmit somatosensory signals.
- Last, we debugged the system altogether.

> Every folder includes an implementation of a complex module (except the `fundemental` folder) and a explanation in each markdown.
> All modules are integrated in top.v finally.
