# Vintage Capacitors

This project collects information on capacitors found in vintage computers, monitors, etc.

## File format
```
Each file line:

<equipment-type> <equipment-vendor> <equipment-model> <capacitor-symbol> <capacitance> <voltage> <location> <type>

equipment-type:   Computer, Monitor, TV, FDD, Laptop, ...
equipment-vendor: Sony, Commodore, Atari, ...
equipment-model:  C64, 800XL, Amiga 2000, ...
capacitor-symbol: C102, C234, ...
capacitance:      10uF, 0.1uF, 10nF, ...
voltage:          50V, 160V, 400V, ...
location:         motherboard, analog board, PSU, ...
type:             BP       - thru-hole bipolar electrolytic capacitor
                  BP HF    - thru-hole bipolar high-frequency electrolytic capacitor
                  EL       - thru-hole polarized electrolytic capacitor
                  FLT RIFA - filter RIFA capacitor that needs immediate replacement
                  SMD      - SMD mounted polarized electrolytic or tantalum capacitor
                  SMD/EL   - SMD or EL capacitor - two mounting methods on PCB
                   
```
