# Pic Microcontroller Expanding Output Pins

## Course Snapshot

| Field | Details |
| --- | --- |
| Instructor | Ashraf S A AlMadhoun |
| Hardware Focus | PIC Microcontroller |
| Course Link | https://www.udemy.com |
| Repository Updated | 2025-11-18 |

## Overview

Pic Microcontroller Expanding Output Pins is a hands-on course focused on practical PIC
Microcontroller development. This repository contains curated starter code, wiring notes,
and a repeatable workflow that mirrors the lessons from the video curriculum.

## Learning Objectives

- Understand the core goals of the **Pic Microcontroller Expanding Output Pins** lessons.
- Map the theoretical material onto executable firmware samples.
- Practice reviewing telemetry / console logs with the provided samples.
- Customize the code to match your target hardware setup.

## Hardware & Components

Consult `CIRCUIT.md` for wiring notes. Typical builds require a development board,
sensors/actuators described in the Pic Microcontroller Expanding Output Pins videos,
jumper wires, and a USB cable for programming plus logging.

## Setup Instructions

1. Install the latest Arduino IDE or your preferred toolchain.
2. Clone this repository or download it as a ZIP.
3. Review the `README.md`, `CIRCUIT.md`, and `data/` samples.
4. Upload the code to your dev board and monitor the serial console.

## Code Walkthrough

The `*.c` files are intentionally lightweight so you can focus on the core concept taught
in the course. Each file now includes metadata comments that summarize intent, I/O
expectations, and how telemetry maps to the lesson.

## Usage

```bash
# Build and inspect the sample on a desktop toolchain
gcc -Wall -Wextra -std=c11 *.c -o demo && ./demo

# Or upload via Arduino IDE to replicate the Pic Microcontroller Expanding Output Pins lab
```

## Sample Data

Open `data/sample-telemetry.jsonl` to inspect representative console output. This is
useful when validating your hardware wiring or cloud logging pipeline.

## Additional Notes (Legacy Content)

# PIC Microcontroller Expanding Output Pins

- Course: PIC Microcontroller Expanding Output Pins
- Author: Ashraf S A AlMadhoun
- Link: https://www.udemy.com/course/pic-microcontroller-shift-register-expanding-output-pins/?couponCode=JULYMAXDICOUNT

## Overview

Use shift registers and expanders to increase available output pins on PIC.

## Purchase With Discount

Enroll using the link above to get a discounted price and scale IO.
