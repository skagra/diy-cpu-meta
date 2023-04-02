# DIY CPU Meta

The DIY CPU project began as a learning exercise in digital electronics, with goals to:

* Design a CPU from the ground up that is op-code compatible with the 6502.
* Implement and validate the design in a digital circuit simulator.
* Implement the design physically, primarily using the `74HC` series of ICs.

While maintaining its original theme, the project has evolved into the following:

# Core Projects

* [DIY CPU](https://github.com/skagra/diy-cpu) - This is the original DIY CPU project, it consists of:
  * Design of an (nearly) 6502-equivalent CPU using generic components.
  * An emulation of the design using [Digital](https://github.com/hneemann/Digital).
  * μcode implementing almost the entire 6502 instruction set.

* [DIY CPU Simplified](https://github.com/skagra/diy-cpu-simplified) - A simplified version of the DIY CPU which is being implemented in physical hardware.  The repository contains:
  * A design of the CPU using generic components.
  * An embedding of the design using the `74HC` series of ICs.
  * Emulations of both the generic and the `74HC` designs using [Digital](https://github.com/hneemann/Digital).
  * μcode implementing a subset of the 6502 instruction set.

* [DIY CPU μcode Assembler](https://github.com/skagra/diy-cpu-uc-assembler) - A μcode assembler which processes symbolic μcode to create binary μcode ROMs and decoding ROMs.

* [DIY CPU Controller](https://github.com/skagra/diy-cpu-controller) - A μcontroller based control unit and debugger.   This will eventually be replaced by a `74HC` circuit.

* [DIY Clock](https://github.com/skagra/diy-clock) - A flexible clock implementation.

* [DIY Display](https://github.com/skagra/diy-display) - A simple memory mapped output display. 

* [DIY Display Tester](https://github.com/skagra/diy-display-tester) - A test rig for the DIY Display.

# Related Projects

* [EEPROM programmer](https://github.com/skagra/eeprom-programmer) - An EEPROM programmer for parallel EEPROMs 

* [Hex Display](https://github.com/skagra/hex-reader) - A test tool to display up to 32 bits sampled from a digital circuit. 

* [atmega328-programmer](https://github.com/skagra/atmega328-programmer) - A programmer and prototyping tool for the Atmega 328 microcontroller. 

* [i2c Detect](https://github.com/skagra/i2c-detect) - An Arduino sketch to scan for attached `i2c` devices and to display their respective addresses.

# Tools

Here's short list of the tools used across these related projects.

* [Digital](https://github.com/hneemann/Digital) - Digital is an easy-to-use digital logic designer and circuit simulator.
* [Fritzing](https://fritzing.org/) - A simple circuit design application for schematics, breadboards and PCBs.
* [Visual Studio Code](https://code.visualstudio.com/) - A flexible IDE, together with the following plugins:
  * Visual Studio Code extension for Arduino
  * C/C++ (Microsoft)
  * C# (Microsoft)
  * CMake (Microsoft)
  * Dasm macro assembler for VSCode
* [Dasm assembler](https://dasm-assembler.github.io/) - a 6502 cross-assembler.
* [Dotnet SDK](https://dotnet.microsoft.com/en-us/download) - C# is used to implement various tools including the μcode assembler.
* [CMake](https://cmake.org/) - A `make` implementation.

# Datasheets and Documentation

Various related datasheets are documentation is collected [here](docs) for ease of reference.

