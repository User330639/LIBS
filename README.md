# LIBS
Personal Altium libs repository
## Conventions
### Schematics
- Only black and white colors
- Arial 10 for refdes
- Arial 9 for comments and everything else
- All pins are passive with rare exceptions
- All pins are 5mm long
- No hidden pins allowed
- Generally 5mm pins pitch
### PCB
- Pads are generally rounded rectangles
- SM opening - 0.05mm except for special cases
- NPTH must have SM expansion from the hole edge
- NPTH must have negative pad sizes
- There are dedicated layers for board outline (M1), assembly (M2/M3), 3D (M4/M5) and courtyard (M13/M14) with no other optional (non-system) layers allowed
- Widths: silk - 0.2mm, assembly - 0.1mm, courtyard - 0.05mm
- Courtyard must contain a cross at the component origin
- Courtyard lines must be aligned to 0.1mm grid
- Shields generally have pads with '0' designator
- Accurate 3D models are required

*To be updated*