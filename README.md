# hw-foundations

Small Verilog exercises, each with a testbench.

- `01-and-gate`: AND gate with an exhaustive stimulus testbench

```
cd 01-and-gate
iverilog -o and_gate_sim and_gate.v and_gate_tb.v && vvp and_gate_sim
```
