# STM32 Impulse Response

Real-time impulse response processing on the STM32F042K6 microcontroller for guitar effects.

## Hardware

**Board:** STMicroelectronics NUCLEO-F042K6

- ARM Cortex-M0 @ 48 MHz
- 32 KB Flash, 6 KB SRAM

## Project Goals

This project aims to implement an impulse response convolution for:

- 🎸 **Guitar cabinet simulations**
- 🌊 **Reverb effects**

## Status

🚧 **In Development** - nothing works, but the led is blinking and I'm reading voltage from PA0

## Building

```bash
make clean
make -j$(nproc)
```

## Flashing

```bash
st-flash write build/stm32_impulse_response.bin 0x8000000
```

## License

See LICENSE file for details.
