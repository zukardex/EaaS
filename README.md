# EaaS
# Entropy-as-a-Service: A Post-Quantum Random Number Generator Using Johnson-Nyquist Noise for E-Gaming

## Abstract
This project presents a hardware-based random number generator (HRNG) leveraging Johnson-Nyquist noise as a true entropy source. The system integrates a resistive noise source, ADC, and FPGA/microcontroller for real-time random number generation, enhanced through post-processing techniques like whitening. This can be used for generating a True Random Number Generator (TRNG) for Entropy-as-a-Service (EaaS) in online gaming platforms.

## Problem Statement
The risk of prediction in online gaming is one of the most challenging tasks to be addressed when launching gambling games. Conventional methods of generating random numbers are prone to prediction because currently used software-based algorithms, such as Linear Congruential Generators, produce pseudo-random numbers. Popular hardware random number generators, including those from Intel, have recently been reported as exploited. With the upcoming quantum computing era, the risks will be heightened to their peak.

## Solution
To solve this problem, a true random number generator is required. For this purpose, we propose a hardware random number generator based on Johnson-Nyquist thermal noise as a source of entropy. The entropy from this source will be extracted, amplified, and processed for conversion to a digital format. This true random number can then be utilized for secure gaming applications.

## Features
- Utilizes Johnson-Nyquist noise as a true entropy source.
- Integration with FPGA/microcontroller for real-time processing.
- Post-processing techniques such as whitening for enhanced randomness.
- Suitable for Entropy-as-a-Service (EaaS) models.
- Designed for use in secure online gaming applications.

## Applications
- Online gambling and gaming platforms.
- Cryptographic key generation.
- Secure communications.
- Blockchain and financial applications.

## Technologies Used
- **Hardware:** FPGA/Microcontroller, ADC, Resistive Noise Source.
- **Software:** Post-processing algorithms (whitening, entropy extraction).
- **Security:** Post-quantum cryptographic readiness.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/zukardex/EaaS.git
   ```
2. Navigate to the project directory:
   ```sh
   cd EaaS
   ```
3. Follow hardware setup instructions in the documentation.

## Usage
1. Connect the hardware components as per the schematics.
2. Compile and upload the firmware to the FPGA/microcontroller.
3. Run the post-processing script to generate secure random numbers.


---


