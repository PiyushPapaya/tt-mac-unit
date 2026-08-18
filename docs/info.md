## How it works

This project implements an 8-bit multiply-accumulate (MAC) unit. It takes
two 4-bit operands as input, multiplies them, and accumulates the result
in an internal register on each clock cycle.

## How to test

Apply two 4-bit values via ui_in (bits 0-3 for operand A, bits 4-7 for
operand B), clock the design, and observe the accumulated result on uo_out.

## External hardware

None
