# Artemisa Diagnosis Tool

Welcome to the Artemisa Diagnosis Tool. In this directory, you will find the source code for a MSX ROM that implements a diagnosis tool for Artemisa Computer System.

## Dependencies

- `pasmo`, the Z80 assembler. In Debian-based systems, it is available with `apt-get install pasmo`. But you can also find it [in the project website](http://pasmo.speccy.org/). 

## Build

Just invoke `make`. It will generate an `adt.rom` file. This is a ROM image of the tool, ready to be burned in your preferred memory chip. 
