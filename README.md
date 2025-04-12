# max7split

**max7split** is a Lua module for controlling an 8-digit 7-segment LED display using the MAX7219 driver chip.  
It supports BCD decoding, decimal points, right-aligned rendering, and dual-segment display output (4+4 digits).

## Features

- Display text or numbers on two separate 4-digit segments
- Right-aligned output for better numeric formatting
- Adjustable brightness (0x00–0x0F)
- Clear entire display or one segment (left/right)
- Shutdown and resume display operation
- Decimal point support (e.g., `1.2`, `12.`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Raadgie/max7split.git
