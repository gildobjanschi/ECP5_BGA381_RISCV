# blue_whale_hw
ECP5 FPGA board

## Software
The ECP5 FPGA board was developed to enable the development of a RISCV processor and allow for for an extension connector. See the [RISC-V_micro Project](https://github.com/gildobjanschi/RISC-V_micro) for detailed explanation of the Verilog code developed for this board.

## How To setup KiCAD to use the project specific symbols, footprints and 3D models.
Checkout the KiCAD project and open it. In the Configure Paths dialog add: Name: ECP5_RISCV and Path: <The full path to the GitHub directory>/GitHub/blue_whale_hw

In the Manage Symbol Libraries click the Project Specific Libraries tab and add: Name: ECP5_RISCV and Library Path: ${ECP5_RISCV}/symbols/Symbols.kicad_sym

In the Manage Footprint Libraries click the Project Specific Libraries tab and add: Name: ECP5_RISCV and Library Path: ${ECP5_RISCV}/footprints/Footprints.kicad_sym


![Blue Whale 3D view](https://github.com/gildobjanschi/blue_whale_hw/blob/main/ECP5.png)
