# Cell infos

A slash before a signal name means it's active low.

## AND, OR, NAND, NOR

They all look the same. ANDs and ORs are actually NANDs and NORs with an added inverter, so they're bigger. AND and ORs appear like mirrored copies of each other depending on the power lines order.

## DFFs

There are many flavors of DFF (D Flip-flop) cells used throughout the design. Most of them have a pair of complementary clock inputs.

Some have /RESET inputs, some have /RESET and /SET, some only have a /Q and no Q output.

## LATCH

AKA transparent latch. They're similar to DFFs but they let data pass through when inactive.

## COUNT

Counter element. Basically a 1-bit register and a full adder.

## AOI

AND-OR-Invert cell. Inputs are grouped by pairs into AND gates, the outputs of which go in a NOR gate.
Sometimes used as a multiplexer when combined with a one-hot decoder.

## Adders

Half adder: A+B -> S, carry in COUT.

Full adder: A+B+CIN -> S, carry in COUT.

The half adders are used for the first bit in adder chains, as there is no carry in.
