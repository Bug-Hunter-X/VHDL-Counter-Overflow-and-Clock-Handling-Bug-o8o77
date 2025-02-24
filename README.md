# VHDL Counter Bug and Solution

This repository demonstrates a common bug in VHDL counters and provides a solution.

## The Bug
The `buggy_counter.vhd` file contains a VHDL counter.  This counter has a potential overflow problem, and it may not react correctly to the clock signal.  The counter also may not be properly reset.

## The Solution
The `fixed_counter.vhd` file provides a corrected version of the counter. This version addresses the overflow issue and improves clock and reset handling. It uses a more robust approach to ensure correct operation and to prevent issues stemming from improper handling of edge conditions.

## How to reproduce
1.  Simulate `buggy_counter.vhd`. Observe the unexpected behavior when the counter reaches its maximum value (15) or during reset and clock transitions. 
2. Simulate `fixed_counter.vhd` and verify that it functions as expected. 
