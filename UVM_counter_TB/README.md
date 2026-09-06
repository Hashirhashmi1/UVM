# UVM Counter Verification

## Description

A beginner-level UVM testbench created to verify a simple 4-bit counter.

## DUT

The counter:

* Resets to `0` when `rst = 1`
* Increments when `en = 1`
* Holds its value when `en = 0`

## UVM Components

* Transaction
* Sequence
* Sequencer
* Driver
* Monitor
* Scoreboard
* Agent
* Environment
* Test

## Tools

* SystemVerilog
* UVM 1.2
* Cadence Xcelium
* EDA Playground

## Verification Flow

`Sequence → Sequencer → Driver → DUT → Monitor → Scoreboard`

## Result

The scoreboard compares the expected counter value with the actual DUT output and reports PASS or FAIL.

