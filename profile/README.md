# DIY Synth MNL

Open-source Eurorack modules and the tools to build them. Hobbyist designs, fully documented.

Blog: **[diysynthmnl.github.io](https://diysynthmnl.github.io)**

## About

Hi! I'm Rex. I design and build open-source Eurorack modules as a hobby — I've been at it since 2019 with no formal electronics education. **Anyone can design and build synth modules** — I'm here to help. I try to be thorough with design documentation so these repos can demystify how the modules work and give you ideas for your own designs.

I'm currently a one-person team. Every project here includes schematics, KiCad source, and (where complete) BOMs, panel artwork, and build docs. Each repo's README has a **Build status** section showing exactly what's ready and what's still TODO.

## Modules

### VCOs

| Module | Chip | Status |
|---|---|---|
| [Electric Druid VCDO1](https://github.com/DIYSynthMNL/Eurorack-Electric-Druid-VCDO1) | VCDO1 wavetable | Schematic Rev 0.1.5 · BOM ✓ · Working on documentation |
| [AS3340 VCO](https://github.com/DIYSynthMNL/Eurorack-3340-VCO) | AS3340 | Schematic Rev 0.1.2 · BOM ✓ · Prototype in progress |

### VCFs

| Module | Chip | Status |
|---|---|---|
| [AS3320 Low Pass VCF](https://github.com/DIYSynthMNL/Eurorack-3320-VCF) | AS3320 | Schematic Rev 0.1.5 · PCB rev 0.1.0 separated · Re-separation pending |

### VCAs

| Module | Chip | Status |
|---|---|---|
| [AS2164 Quad Exponential VCA](https://github.com/DIYSynthMNL/Eurorack-2164-Quad-Exponential-VCA) | AS2164 (SSI2164 drop-in) | Schematic Rev 0.1.4 · Working on documentation |
| [AS3330 Dual Lin/Exp VCA](https://github.com/DIYSynthMNL/Eurorack-3330-Dual-Lin-Exp-VCA) | AS3330 | Schematic Rev 0.1.7 · Prototype in progress |

### LFOs

| Module | Chip | Status |
|---|---|---|
| [Electric Druid VCLFO 10](https://github.com/DIYSynthMNL/Eurorack-VC-LFO) | VCLFO10 | Planning |

### Envelope Generators

| Module | Chip | Status |
|---|---|---|
| [AS3310 VC ADSR](https://github.com/DIYSynthMNL/Eurorack-3310-ADSR) | AS3310 | Schematic Rev 0.1.3 · Working on documentation |

### Effects

| Module | Status |
|---|---|
| [Multi Saturation](https://github.com/DIYSynthMNL/Eurorack-Multi-Saturation-Module) | Schematic Rev 0.6 · PCB Rev 0.1 separated · Rev 0.2 fixes pending |
| [PT2399 Delay](https://github.com/DIYSynthMNL/Eurorack-PT2399-Delay) | Schematic Rev 0.1.1 · Working on documentation |

### Sequencers

| Module | Status |
|---|---|
| [Pi Pico Random Looping Sequencer](https://github.com/DIYSynthMNL/Pi-Pico-Random-Looping-Sequencer) | Hardware Rev 0.1.0 · MicroPython firmware · [Demo on YouTube](https://youtu.be/u1J9JrJe1Y0) |

### Clock

| Project | Status |
|---|---|
| [Eurorack Clock Module (hardware)](https://github.com/DIYSynthMNL/Clock-Module) | 4HP, Arduino Nano + 64×32 OLED · PCB in progress |
| [Eurorack Clock Module Firmware](https://github.com/DIYSynthMNL/Eurorack-Clock-Module-Firmware) | PlatformIO, AVR ATmega328P · Working firmware |

### Power

| Project | Status |
|---|---|
| [EuroBusboard (8 outputs)](https://github.com/DIYSynthMNL/EuroBusboard) | Schematic Rev 0.1 · Multiple connector variants (10-pin IDC / JST / both) |
| [EuroBusboard 8 IDC 16PIN](https://github.com/DIYSynthMNL/EuroBusboard-8-IDC-16PIN) | Doepfer A-100 16-pin IDC standard · PCB in progress |

### Case

| Project | Notes |
|---|---|
| [Multi-Angle Eurorack 1-Row Case](https://github.com/DIYSynthMNL/Multi-Angle-Eurorack-1-Row-Case) | 84HP single-row DIY case with re-orientable side panels |

## Shared resources

- **[DIYSynthMNL.pretty](https://github.com/DIYSynthMNL/DIYSynthMNL.pretty)** — KiCad footprint library used across all modules (audio jacks, Eurorack power headers, vactrols, big-pad resistors/caps, panel mounting holes)

## Where to start

- **New to module DIY?** Build the [EuroBusboard](https://github.com/DIYSynthMNL/EuroBusboard) first — fewer parts and a great way to learn the KiCad-to-PCB workflow before tackling an analog module.
- **Want sound first?** The [Multi Saturation](https://github.com/DIYSynthMNL/Eurorack-Multi-Saturation-Module) and [PT2399 Delay](https://github.com/DIYSynthMNL/Eurorack-PT2399-Delay) are utility-style effects modules with well-trodden parts lists.
- **Building a voice?** Pair the [AS3340 VCO](https://github.com/DIYSynthMNL/Eurorack-3340-VCO) + [AS3320 VCF](https://github.com/DIYSynthMNL/Eurorack-3320-VCF) + [AS2164 Quad VCA](https://github.com/DIYSynthMNL/Eurorack-2164-Quad-Exponential-VCA) + [AS3310 ADSR](https://github.com/DIYSynthMNL/Eurorack-3310-ADSR).

## Contributing

Spotted a mistake in a schematic, want to add a build photo, or have a calibration tip? Open an issue or PR on the relevant repo — every README has a Build status section showing what's still TODO.
