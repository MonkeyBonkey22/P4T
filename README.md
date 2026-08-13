# P4T  
A performance 4010 toolhead. Still in testing.  

![image of p4t](https://github.com/MonkeyBonkey22/P4T/blob/cfcda1ca6f172d31215f647a6b9a5e6fd60ac2dd/Images/P4T1.png) ![com](https://github.com/MonkeyBonkey22/P4T/blob/68c47a17571fd89dc315ea6d4ca1e546c70f236c/Images/COM.png)

## What is this?  
This is a one piece toolhead designed with center of mass and rigidity in mind. It prints with no supports at all, or minimal supports if you don't have good bridges.  

## Why?  
I wanted to switch to a more performant toolhead, but I don't have the space or power for a CPAP.  

## Features  
- Supports up to 12mm belts (Monolith and Voron)
- 4010 fans with A4T fan inserts

## Current release V1.4 

### Supported Extruders  
- Orbiter 2.0/2.5 (with braces)
- Sherpa Mini

### Supported Hotends  
- Dragon Ace Volcano / Dragon Ace (With MZE)
- Chube Compact

## General BOM
| Qty | Part | Purpose / Notes |
|----:|------|-----------------|
| 8 | M2×8 SHCS | 4010 fan mount |
| 8 | M2 Nut | 4010 fan mount |
| 4 | M3×30 SHCS | Toolhead to MGN12H |
| 2 | M3 Square Nut | Extruder mount |
| 2 | M3×6 FHCS | Probe mount |
| 2 | M3 Heatset Insert | Probe mount |
| 4 | M2.5×16 | Fan mount |
| 4 | M2.5 D3.5 Heatset Insert | Fan mount |
| 2 | 4010 Blower Fan | With A4T inserts |
| 1 | Hotend of choice | Hotend |
| 1 | Extruder of choice | Extruder |
| 1 | Cartographer V4 / Beacon Rev. H | Probe |
| 1 | 2510 Axial Fan | — |            
                               
| Hotend | Screws | Qty |
|:-----------------------|:---------|----|
| Dragon Ace Volcano (with MZE) | M2.5x40 SHCS | 4 |
| Chube Compact | M3x50 SHCS | 4 |                   

| Extruder | Screws | Qty |
|:-----------------------|:---------|----|
| Orbiter 2 | M3x12 SHCS | 2 |
| Sherpa Mini| M3x14/16 SHCS | 2 |                   

### Notes:        
**Make sure you have washers for your hotend's screws.**          
**You will need a Monolith Universal SLM Belt Clamp for Monolith belts.**       
**Orbiter 2 mounting braces are optional but highly recommended.**            
  **-Additional hardware: 3x M3x16 (replaces M3x12), 1x M3 Hex Nuts, 2x M3 Square Nuts, 1x M3x35.**            

## Printing
 - Ducts might need support.
 - Use standard Monolith print settings
 - Calibrate dimensional shrinkage for the filament you are using

## Credits
Chaz for early feedback         
theCody501 for testing
