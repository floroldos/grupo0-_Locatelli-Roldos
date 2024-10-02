## How it works
For this project, 8 DSR flip-flops were connected in a shift register configuration. A comparator circuit was built to check if the stored value in the register matches a fixed 8 bit binary number. The shift register shifts with each clock cycle. When a number is inputed by opening/closing the input and stepping, the circuit compares is the value inputed matches 10010010. If it matches, the LED will turn on.

## How to test
Feed an 8-bit binary value into the register through the D input of the first Flip-Flop. You can manipulate the D input and run several clock cycles to shift the bits across the register with the stepper. If the value inputed is 10010010, the LED must turn on, otherwise it mustn't.
