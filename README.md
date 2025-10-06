# Kontakt KSP Demo

This repository contains simple **Kontakt Script Processor (KSP)** examples.  
They are written to be used inside **Native Instruments Kontakt** (full version).

## Scripts
- `scripts/volume_knob.ksp`  
  Creates a knob to control instrument volume (-60 dB to 0 dB).

- `scripts/filter_toggle.ksp`  
  Creates a button to toggle a low-pass filter on/off (slot 0 in Group FX).

- `scripts/pan_knob.ksp`  
  Creates a knob to control stereo panning (0 = hard left, 50 = center, 100 = hard right).

## How to use
1. Open Kontakt and load a sample into a new instrument.
2. For `filter_toggle.ksp`, add a Low-Pass Filter into Group Insert FX (slot 0).
3. Open Script Editor and paste the content of one `.ksp` file.
4. Click Apply — the UI controls appear on the instrument front panel.

## Notes
- These scripts were written on Linux, without Kontakt available.  
- They are **unverified**, but follow official KSP documentation.  
- Goal: demonstrate proactive learning of Kontakt scripting and instrument design.
