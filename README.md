# riscv-formal-RVFI

`riscv-formal` is a work-in-progress framework project for formal verification of RISC-V processors from SymbioticEDA (https://github.com/SymbioticEDA/riscv-formal).

It consists of the following components:
- A processor-independent formal description of the RISC-V ISA
- A set of formal testbenches for each processor supported by the framework
- The specification for the [RISC-V Formal Interface (RVFI)](https://github.com/SymbioticEDA/riscv-formal/blob/master/docs/rvfi.md) that must be implemented by a processor core to interface with `riscv-formal`.
- Some auxiliary proofs and scripts, for example to prove correctness of the ISA spec agains riscv-isa-sim.

`riscv-formal` uses the FOSS SymbiYosys formal verification flow. All properties are expressed using immediate assertions/assumptions for maximal compatibility with other tools.

#
