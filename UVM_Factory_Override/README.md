# UVM Factory Driver Override

## Introduction
This project demonstrates how to override a UVM driver implementation using the UVM Factory.

The `base_driver` is replaced by `new_driver` using `set_type_override()` without changing the agent's driver creation code.

## UVM Concept
The main concept used in this lab is:

```systemverilog
base_driver::type_id::set_type_override(new_driver::get_type());
