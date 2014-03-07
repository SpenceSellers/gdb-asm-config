gdb-asm-config
==============

This is just a simple script to prepare gdb for assembly debugging.

Run it with ```gdb --command=asmdebug.gdb [program]```

By default it decodes each instruction into NASM assembly. To change that just comment out the ```intel``` flavor line in the script.
