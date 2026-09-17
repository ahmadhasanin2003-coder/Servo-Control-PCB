# Servo-Control-PCB

A simple servo control circuit designed using the **NE555 timer IC**.

## Overview

This project generates a variable control signal for a servo using a 555 timer configured as an astable/pulse-generation circuit.

The servo position can be adjusted using a potentiometer, which changes the timing characteristics of the generated signal.

## Components

- NE555 Timer IC
- Potentiometer
- 1N4148 Diode
- LED
- Resistors
- Capacitor
- External power and servo connections

## Working Principle

The NE555 generates a periodic pulse signal. The potentiometer changes the charging/discharging timing of the capacitor, which changes the pulse characteristics supplied to the servo.

By adjusting the potentiometer, the servo position can be controlled.

## Tools Used

- KiCad
- NE555 Timer

## Project Files

The `hardware` directory contains the KiCad design files:

- `.kicad_pro` — KiCad project
- `.kicad_sch` — Schematic
- `.kicad_pcb` — PCB layout

## Status

**Schematic:** Completed  
**PCB:** In progress
