# Blue Whale Hardware
ECP5 FPGA board

## Software
The ECP5 FPGA board was developed to enable the development of a RISCV processor and allow for for an extension connector. See the [RISCV_PROCESSOR](https://github.com/gildobjanschi/RISCV_PROCESSOR) project for detailed explanation of the Verilog code developed for this board.

## How To setup KiCAD
Checkout the KiCAD project and open it. In the Configure Paths dialog add: Name: ECP5_RISCV and Path: <The full path to the GitHub directory>/GitHub/ECP5_BGA381_RISCV

In the Manage Symbol Libraries click the Project Specific Libraries tab and add: Name: ECP5_RISCV and Library Path: ${ECP5_RISCV}/symbols/Symbols.kicad_sym

In the Manage Footprint Libraries click the Project Specific Libraries tab and add: Name: ECP5_RISCV and Library Path: ${ECP5_RISCV}/footprints/Footprints.pretty

## Project Status
The HW has been fully verified as part of the [RISCV_PROCESSOR](https://github.com/gildobjanschi/RISCV_PROCESSOR) project. An extension board was developed to test the extension interface. That extension is not published on Github.

[Schematic PDF](https://github.com/gildobjanschi/ECP5_BGA381_RISCV/blob/main/kicad/ECP5_board.pdf)

![Blue Whale 3D view](https://github.com/gildobjanschi/ECP5_BGA381_RISCV/blob/main/ECP5.png)
