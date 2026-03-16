# Unit Testing for Embedded Development: From Real Silicon to Emulated Environments

This repository contains demonstrations and examples related to unit testing practices for embedded systems. It covers
various testing methodologies, including development testing, emulator testing, and on-device testing, addressing the
unique challenges and considerations for embedded software.

Target Device: STM32F405RGxx(STM32F407RGxx) (ARM Cortex-M4)

### Presentation

[Slides](Unit-Testing-for-Embedded-Development.pdf) for my talk at *Embedded World 2026* conference 

### Testing Approaches

Explores three primary testing methods:

1. Development Testing
    - Synthetic tests run on a computer or CI server
2. Emulator Testing
    - Synthetic tests cross-compiled for the target processor and run on an emulator
3. On-device Testing
    - Tests cross-compiled and executed directly on the target device

The code in this repository is designed to work seamlessly on both local development machines and TeamCity CI/CD
servers, ensuring consistent testing environments across different platforms.

