# VL53L7CX ULD (ST import)

This repository contains an unmodified import of the **STMicroelectronics VL53L7CX Ultra Lite Driver (ULD)** sources.

- **Upstream package:** VL53L7CX ULD driver (e.g., STSW-IMG036 / ULD release)
- **What’s included:** ULD API sources and the original `platform.h` interface header
- **What’s not included:** platform implementation, board examples, CubeIDE projects

## License

BSD-3-Clause.  
Original ST license documents are preserved under `License/`. See `LICENSE.txt` for the full license text.

## Notes

You must provide your own platform/adapter implementation (I2C read/write, delays, optional reset) in your application repository.

