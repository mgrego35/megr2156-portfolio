# A10 – Lead Screw Translating System

## Objective

Design and build a mechanically driven tensile tester capable of applying up to 2 kN axial tensile load with a controllable crosshead speed from 1 to 50 mm/min. Each team is responsible for the mechanical components outlined below. The system will provide consistent, well-aligned loading for polymers and light metals, suitable for instructional use and basic materials evaluation. Safety factor of 4.

## Designing the Crosshead: Morgan Gregory

To begin, I needed to find both the length, from research, and the base, from the nut flange. The length was chosen to be 300 mm and the base was chosen from the flange nut diameter to be 31.75 mm. The rest of the knowns and unknowns are shown below.

<img width="455" height="330" alt="Screenshot 2026-11-11 020504" src="https://github.com/user-attachments/assets/8dc532b3-8446-4551-a224-889a41be7492" />

I then found the maximum shear and yield stresses using the safety factor of 4.

<img width="394" height="189" alt="Screenshot 2026-11-11 020707" src="https://github.com/user-attachments/assets/1f9778c0-b5ab-462f-9892-c042be2955da" />

Now it is important to calculate minimum values such as thickness of the beam. I began by doing the stress analysis. I analyzed shear stress first and bending stress second. The math is shown below, with minimum h values. 6061 aluminum was the chosen material for its lighter weight and cost effectiveness.

<img width="850" height="290" alt="Screenshot 2026-11-11 021022" src="https://github.com/user-attachments/assets/372fbd67-1a38-4e70-aba5-360c699e18f2" />

The minimum value of h for came from the bending stress so far at 11.33 mm.

Now it was important to find the h with the max deflection of .1 mm.

<img width="818" height="217" alt="Screenshot 2026-11-11 021127" src="https://github.com/user-attachments/assets/bb982256-2dc1-4926-972d-f099b99f52c8" />

The deflection gave the final value of h as 21.3 mm.

Next is the CAD design for the crosshead. I began by creating a sketch of a rectangle and extruding it by the height as shown below. 










## References

https://mechanicalc.com/reference/beam-deflection-tables

https://repositum.tuwien.at/bitstream/20.500.12708/200949/1/Demmel%20Stella%20-%202024%20-%20Design%20manufacturing%20and%20testing%20of%20an%20open-source...pdf
