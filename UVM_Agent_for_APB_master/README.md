# UVM APB Master Agent

## Overview

This project implements a simple **UVM-based APB Master Agent** for verification.

## Components

* Transaction
* Sequence
* Sequencer
* Driver
* Monitor
* Agent
* Environment
* Test
* APB Interface
* APB Slave DUT

## Flow

```text
Sequence
   ↓
Sequencer
   ↓
Driver
   ↓
APB Interface
   ↓
DUT
   ↑
Monitor
```

## Simulation

The test generates a simple APB write and read transaction. The monitor observes the APB bus and collects the transactions.

A waveform file `apb_wave.vcd` is also generated for viewing the APB signals.

## Tools

* SystemVerilog
* UVM
* Xcelium / EDA Playground

## Purpose

The purpose of this project is to understand the basic structure and working of a UVM agent for an APB bus master.

