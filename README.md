Name:Matta Jhansi.
Company:CODTECH IT SOLUTIONS.
ID:CT6VLSI1243.
Domain:VLSI.
Duration:July to August 2024.
Mentor:Muzammil Ahmed.

**Overview of the project**
project:Finite State Machine(FSM)Design using vlsi

**objective**
This Verilog module defines a basic FSM with three states (IDLE, STATE_1, FINAL) and two outputs (out1, out2) that indicate whether the FSM is in STATE_1 or FINAL, respectively. The FSM transitions between states based on the input a and operates synchronously with the clock signal clk.

**KeyActivities**
 *Inputs:*
  - clk: Clock signal, used for synchronous operation.
  - a: Input signal that controls state transitions.
  
- *Outputs:*
  - out1: Output signal indicating whether the FSM is in STATE_1 (1 if true).
  - out2: Output signal indicating whether the FSM is in FINAL (1 if true).
 State Encoding
- **state (reg [2:0] state):** This 3-bit register stores the current state of the FSM.
- *State Parameters:*
  - IDLE (3'b001): Initial and default state.
  - STATE_1 (3'b010): State transitioned to from IDLE when a is asserted (1).
  - FINAL (3'b100): State transitioned to from STATE_1 when a is asserted (1).

    Techologies used
    * vlsi: The primary programming language use for designing FSM
    * EDA Playground:is used to executive the programe
    * simulator:is used to obtain the output waveform

