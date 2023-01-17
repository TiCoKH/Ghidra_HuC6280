# Ghidra HuC6280 Processor module

Install
-------

Copy Ghidra directory into your Ghidra folder (exp.: ghidra_10.1.2_PUBLIC/Ghidra/).

Usage
-----

Load PCEngine Logical RAM dump (64Kb) Format as Raw Binary, choose HuC6280 Language.

Known Issues
------------

Few memory block conflict but disassembly works.
Zero Page reference seen as full address 0x20XX instead of usual $XX
Now CD System symbols is default on MPR7, PCEngine dump memory configuration should be configurable (HuC Card, CD, PSG)
