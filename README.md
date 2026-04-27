<p align="center">
   <img alt="Static Badge" src="https://img.shields.io/badge/Version-V0A%20(ALPHA)-yellow">
   <img alt="Static Badge" src="https://img.shields.io/badge/License-GPL--3.0-blue">
</p><p align="center">
   <img alt="Static Badge" src="https://img.shields.io/badge/MADE_WITH-ARCH-1793D1?style=flat&logo=archlinux&logoColor=%231793D1">
</p>

# Project Status

   **AMP-AM is currently in the early development phase and is considered unstable. The first stable release is scheduled for Q3 2026**

# AMP-AM (AMP Modus Aequale)

AMP-AM (standing for Modus Aequale, signifying a rhythmic, ideal tone and modular structure) is an open-source, transistor-based guitar combo amplifier project. It is designed to bridge the gap between solid-state reliability and the organic, harmonic richness of vacuum tube sound.

The project focuses on a modular architecture, originally developed as a high-fidelity upgrade for the **Epiphone 15C** PCB. By utilizing independent blocks, AMP-AM allows for seamless customization and easier adaptation to various amp enclosures.

This project is designed and maintained by: [Danylo Pyvovarov](https://github.com/pivikn).


   1. [Key Features](#key-features)
   1. [Signal Chain](#signal-chain)
   1. [Integrated Effects Modules](#integrated-effects-modules)

## Key Features
   - **Tube-like Architecture**: Uses **Mu-amp** stages to achieve a warm, organic sound and harmonicsaturation that mimics vacuum tube behavior.

   - **Dual Input Support**: Designed to handle two guitars simultaneously.

   - **Legendary Tone Stack**: Features a 3-band EQ based on the classic **Marshall JCM900 2100 SL-X preamp**.

   - **Integrated Compression**: Built-in compressor block based on the vintage **Ibanez CP835** circuitry.

   - **Modular Design**: Optimized for easy integration into different amp cabinets or for swapping internal effect modules.

## Signal Chain
   1. Input buffer
   1. Preamp 
   1. Compressor
   1. Tone Stack
   1. Recovery Stage
   1. Power Amp (LM1875)

## Integrated Effects Modules
|       Effect      |   based on   |  Satus  |
|-------------------|--------------|---------|
| Compressor        | Ibanez CP835 |  dev    |
| Over Drive        | Boss OD3     | planed  |
| Chorus            | Boss Ch1     | planed  |
