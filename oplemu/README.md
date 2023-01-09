# Standalone OPL emulation module

This directory contains a standalone version of the OPL emulation components, found in the following source files:

- `src/hardware/opl.cpp`
- `src/hardware/opl.h`

This directory contains standalone versions of those two files, edited to remove dependencies on the rest of DOSBox and also so that they can compile as C source files rather than C++.

A number of definitions have been moved from the header to the source file, to simplify the public interface.
