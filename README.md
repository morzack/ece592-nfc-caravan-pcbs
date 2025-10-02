# ece592-nfc-caravan-pcbs

submodules vendor in reference boards for tt06 and caravel.

most up-to-date caravel evaluation PCB at `caravel_board/hardware/development/caravel-dev-v5-M.2` -- this contains details on FTDI module and flash memory for bringup of on-chip VexRiscv management CPU

## work breakdown

following a top-down design

1. make symbol for pinout (actual)
2. identify routing constaints for breakout
3. make block diagram of off-chip requirements for bringup
4. implement schematics for off-chip stuff
5. layout, etc
