# EdvFormal - Formal Verification Framework (v0.1)

EdvFormal is a formal verification tool which helps in proving properties and finding corner-case bugs. It uses modern Satisfiability (SAT) / Satisfiability Modulo Theories (SMT) solvers to prove properties.

## Overview

EdvFormal Tool provides a comprehensive formal verification environment for RTL designs using SystemVerilog Assertions (SVA). It enables property-based verification to mathematically prove that design behavior aligns with specification under all legal input combinations.

## Objectives

- Formally prove correctness of the design under the defined constraints
- Ensure that the RTL design is bug-free

## Requirements

| Component | Version |
| --- | --- |
| OS  | Linux |
| Python | 3.12 |

## Installation Guide

### Symbiyosys Installation

Install python3 packages if not already installed:

sudo apt install python3-pip

sudo apt install python3-click