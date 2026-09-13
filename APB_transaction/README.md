# APB UVM Verification Lab

## Introduction
A UVM testbench for the APB protocol, covering sequence items, sequences, drivers, monitors, and agents, with a simple APB slave DUT so it runs end-to-end.

## How to Run
```bash
vlog +incdir+$UVM_HOME/src $UVM_HOME/src/uvm_pkg.sv apb_uvm_lab.sv
vsim -c top -do "run -all; quit"
```
View the generated `apb_waveform.vcd` in your simulator's waveform viewer.

## Conclusion
Demonstrates the core building blocks of a UVM environment — from stimulus generation to driving and monitoring a DUT — as a base for extending into scoreboards, coverage, and multi-agent verification.
