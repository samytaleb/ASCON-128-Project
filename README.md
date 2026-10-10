# ASCON-128 — Hardware implementation

Academic digital-design project exploring an **ASCON-128** cryptographic hardware design in **SystemVerilog**.

## Contents

- [Project report](Report.pdf) — design documentation
- [`sample/SRC/RTL/`](sample/SRC/RTL) — RTL modules, including `ascon_top.sv`, permutations, registers, counters, and control logic
- [`sample/SRC/BENCH/ascon_top_tb.sv`](sample/SRC/BENCH/ascon_top_tb.sv) — simulation testbench
- [`sample/LIB/`](sample/LIB) — tool-generated library artifacts

## Where to start

Read the report for project context, then inspect the top-level module (`ascon_top`) and its testbench to understand the interface and expected simulation behavior. An HDL simulator supporting SystemVerilog is required to run a simulation; the exact toolchain and commands have not been documented in this repository.

## Notes

This is an educational hardware-design artifact, **not a validated, production-ready cryptographic implementation**. Security-sensitive use requires independent verification, test vectors, timing analysis, and review.
