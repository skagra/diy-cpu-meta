# DIY CPU Meta

The repository collects together links and common materials related to the DIY CPU project.

The DIY CPU project began as a learning exercise in digital electronics, with goals to:

* Design a CPU from the ground up that is op-code compatible with the 6502.
* Implement and validate the design in a digital circuit simulator.
* Implement the design physically, primarily using the `74HC` series of ICs.

# Core Projects

* [DIY CPU](https://github.com/skagra/diy-cpu) - This original DIY CPU project.  The repository contains:
  * Design and emulations using generic components of an almost fully 6502-equivalent CPU.
  * Realizations and emulations of those designs using `74HC` series of ICs.
  * μcode implementing almost all of the 6502 instruction set which runs on the emulated CPU.

* [DIY CPU Simplified](https://github.com/skagra/diy-cpu-simplified) - A simplified version of the DIY CPU which is being implemented in physical hardware.  The repository contains:
  * Design and emulations using generic components of a simplified CPU.
  * Realizations and emulations of those designs using `74HC` series of ICs.
  * Microcode implementing a subset of the 6502 instruction set which runs on both the emulated and the physical simplified CPU.
  * Hardware desiigns.

* [DIY CPU μcode Assembler](https://github.com/skagra/diy-cpu-uc-assembler) - A μcode assembler capable of which processes symbolic μcode to create binary μcode ROMs and decoding ROMs.

* [DIY CPU Controller](https://github.com/skagra/diy-cpu-controller) - A micro controller based control unit and debugger for the Diy CPU.   This will eventually be replaced, according to the design, the the physical hardware with a `74HC` based circuit.

* [DIY Clock](https://github.com/skagra/diy-clock) - A flexible clock implementation for DIY-CPU.

* [DIY Display](https://github.com/skagra/diy-display) - A simple memory mapped I/O display for the diy-cpu project. 

* [DIY Display Tester](https://github.com/skagra/diy-display-tester) - A test rig for the DIY Display.

# Related Projects

* [EEPROM programmer](https://github.com/skagra/eeprom-programmer) - EEPROM programmer for parallel EEPROMs 

* [Hex Display](https://github.com/skagra/hex-reader) - A test tool to display up to 32 bits sampled from a digital circuit. 

* [atmega328-programmer](https://github.com/skagra/atmega328-programmer) - A programmer and prototyping tool for Atmega 328 microcontrollers. 

* [i2c Detect](https://github.com/skagra/i2c-detect) - An Arduino sketch to scan for attached i2c devices and to display their respective addresses.

# Tools

Here's short list of the tools used across these related projects.

* [Digital](https://github.com/hneemann/Digital) - Digital is an easy-to-use digital logic designer and circuit simulator.
* [Fritzing](https://fritzing.org/) - A simple circuit design applications for schematics, breadboards and PCBs.
* [Visual Studio Code](https://code.visualstudio.com/) - A flexible IDE, together with the following plugins:
  * Visual Studio Code extension for Arduino
  * C/C++ (Microsoft)
  * C# (Microsoft)
  * CMake (Microsoft)
  * Dasm macro assembler for VSCode
* [Dasm assembler](https://dasm-assembler.github.io/) - a 6502 cross-assembler.
* [Dotnet SDK](https://dotnet.microsoft.com/en-us/download) - C# is used for various tools including the microcode assembler.
* [CMake](https://cmake.org/) - A `make` implementation.

# Datasheets and Documentation

Various related datasheets are documentation is collected [here](docs) for ease of reference.

