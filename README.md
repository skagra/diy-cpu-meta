# DIY CPU Meta

The repository collects together links and common materials related to the DIY CPU project.

The DIY CPU project began as a learning exercise in digital electronics, with goals to:

* Design a CPU from the ground up that is op-code compatible with the 6502.
* Implement and validate the design in a digital circuit simulator.
* Implement the design physically, primarily using the `74HC` series of ICs.

# Core Projects

* [DIY CPU](https://github.com/skagra/diy-cpu) - This the main project.  It contains:
  * Design and emulations using generic components of almost full 6502 equivalent together with a simplified version.
  * Realizations of those designs using `74HC` series of ICs.
  * A microcode assembler capable of converting a custom symbolic micro-code language into microcode ROMs and decoding ROMs.
  * Micro-code implementing almost all of the 6502 instruction set which runs on the emulated CPU.
  * Microcode implementing a subset of the 6502 instruction set which runs on the emulation simplified CPU and the equivalent physical hardware.
  * **This project will soon be broken** up into 3 repositories for the full design with microcode, the simplified design with microcode and the micro-code assembler.

* [DIY CPU Controller](https://github.com/skagra/diy-cpu-controller) - A micro controller based control unit and debugger for the Diy CPU.   This will eventually be replaced, according to the design, the the physical hardware with a `74HC` based circuit.

* [DIY Clock](https://github.com/skagra/diy-clock) - A flexible clock implementation for DIY-CPU.

* [DIY Display](https://github.com/skagra/diy-display) - A simple memory mapped I/O display for the diy-cpu project. 

* [DIY Display Tester](https://github.com/skagra/diy-display-tester) - A test rig for the DIY Display.

# Related Projects

* [EEPROM programmer](https://github.com/skagra/eeprom-programmer) - EEPROM programmer for parallel EEPROMs 

* [Hex Display](https://github.com/skagra/hex-reader) - A test tool to display up to 32 bits sampled from a digital circuit. 

* [atmega328-programmer](https://github.com/skagra/atmega328-programmer) - A programmer and prototyping tool for Atmega 328 microcontrollers. 

* [i2c Detect](https://github.com/skagra/i2c-detect) - An Arduino sketch to scan for attached i2c devices and to display their respective addresses.
