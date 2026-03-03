# OpenDeck-RP2040-v0

![Status](https://img.shields.io/badge/status-prototype-lightgrey)
![Version](https://img.shields.io/badge/version-v0-blue)
![MCU](https://img.shields.io/badge/MCU-RP2040-green)
![EDA](https://img.shields.io/badge/EDA-KiCad%209-informational)
![License](https://img.shields.io/badge/license-MIT-black)

OpenDeck-RP2040-v0 is an early hardware prototype of a DIY macro pad inspired by the Elgato Stream Deck.  
This project represents my **first-ever hardware design**, created as a learning experiment using KiCad with no prior background in electronics or PCB design.

---

## Project Overview

The goal of this project was to explore the fundamentals of hardware design, including schematic capture, PCB layout, and basic I/O expansion using a microcontroller.

At the time of creation(2025), I had no formal knowledge of electronics. I downloaded KiCad, had the concept of a Stream Deck–style device in mind, and designed this board through experimentation and self-learning. The result is a functional concept design rather than a finished or production-ready product.

---

## Hardware Summary

- Microcontroller: Seeed XIAO RP2040  
- Button input expansion: PCF8574 (I²C I/O expander)  
- LED output expansion: 74HC595 (shift register)  
- Inputs: 9 tactile push buttons  
- Outputs: 9 individual LED indicators  
- Interface: USB (via RP2040)

---

## Design Files & Visuals

### Schematic
<img width="632" height="771" alt="image" src="https://github.com/user-attachments/assets/29453806-2b31-4035-8527-7181a487ca8c" />

### PCB Layout
<img width="629" height="885" alt="image" src="https://github.com/user-attachments/assets/bf70e963-2020-4f5f-8c75-606056dfe74b" />

### 3D Render
<img width="743" height="926" alt="image" src="https://github.com/user-attachments/assets/f54618d6-4e0c-4853-b39d-d1fabfe9bca9" />

---

## Repository Contents

- KiCad schematic and PCB files
- Custom symbols, footprints, and 3D models
- Project documentation
- No finalized firmware
- No enclosure or mechanical design

---

## Project Status

**Status: Incomplete / Prototype (v0)**

- Firmware was never completed
- Hardware was not extensively tested
- Design was not revised after the initial version
- This version is considered **frozen**

I may revisit this concept in the future. Any continued development or improvements will be done in a **separate repository (v2)**.  
This repository will remain unchanged as an archive of the original prototype.

---

## Motivation

This project was inspired by the Elgato Stream Deck.  
It was created purely as a learning exercise to understand how an idea could be translated into a real PCB using KiCad, without prior experience in hardware design.

The intent was exploration, not perfection.

---

## Disclaimer

This design is experimental and provided for reference purposes only.  
It is not guaranteed to function as intended and is not suitable for production use.

---

## License

This project is licensed under the MIT License.
