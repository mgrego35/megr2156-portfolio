# A10 – Lead Screw Translating System

## Objective

Design and build a mechanically driven tensile tester capable of applying up to 2 kN axial tensile load with a controllable crosshead speed from 1 to 50 mm/min. Each team is responsible for the mechanical components outlined below. The system will provide consistent, well-aligned loading for polymers and light metals, suitable for instructional use and basic materials evaluation. Safety factor of 4.

## Leadscrew Diameter: Ethan Cornett

The first step in selecting the leadscrews was determining the minimum diameter required to safely support the tensile tester's maximum load of 2 kN. Since the design uses two identical leadscrews, the total load is distributed equally between them, resulting in an axial load of 1 kN per screw.

304 stainless steel was initially selected as the material for the leadscrews, with a yield strength of 205 MPa. A factor of safety of 4 was applied to determine the minimum required diameter.

The diameter was calculated using the axial stress relationship: O=F/A

The allowable stress was determined using the material yield strength and required factor of safety. The resulting theoretical minimum diameter was approximately 4.99 mm. I decided to use a diameter of 12.7mm or 1/2 inch.

This calculation established the minimum structural requirement before selecting a commercially available leadscrew.

The first step in selecting the leadscrews was determining the minimum diameter required to safely support the tensile tester's maximum load of 2 kN. Since the design uses two identical leadscrews, the total load is distributed equally between them, resulting in an axial load of 1 kN per screw.

304 stainless steel was initially selected as the material for the leadscrews, with a yield strength of 205 MPa. A factor of safety of 4 was applied to determine the minimum required diameter.

The diameter was calculated using the axial stress relationship: O=F/A

The allowable stress was determined using the material yield strength and required factor of safety. The resulting theoretical minimum diameter was approximately 4.99 mm. I decided to use a diameter of 12.7mm or 1/2 inch.

This calculation established the minimum structural requirement before selecting a commercially available leadscrew.

<img width="400" height="532" alt="Screenshot 2026-11-11 213542" src="https://github.com/user-attachments/assets/7ff521e8-fd3b-4e27-8fdd-5e27587be00f" />

### Rotational Speed Range

After establishing the minimum diameter, the next step was determining the rotational speed required to achieve the specified crosshead speed.

The tensile tester must operate between 1 mm/min and 50 mm/min. The relationship between linear crosshead speed and leadscrew rotational speed is:

V=nL

Where:

(V) = Linear crosshead speed (mm/min)

(n) = Leadscrew rotational speed (RPM)

(L) = Leadscrew lead (mm/rev)

The selected 1/2-10 Acme leadscrew has a lead of 0.100 inches per revolution, equivalent to 2.54 mm/rev, assuming a single-start thread.

Using this lead, the required rotational speed range is:

Minimum speed: 0.394 RPM

Maximum speed: 19.69 RPM

Both leadscrews will rotate at the same speed to maintain synchronized crosshead movement.

<img width="402" height="533" alt="Screenshot 2026-11-11 213514" src="https://github.com/user-attachments/assets/c8ce3f7e-f52e-454c-90d7-7d250c596331" />

### Maximum Leadscrew Torque

The next calculation determined the torque required to drive both leadscrews while maintaining the required 2 kN tensile load.

Because the system uses two leadscrews, each screw carries approximately 1 kN of the applied load. The torque calculation accounts for the screw lead and the torque coefficient used in the preliminary design.

The calculated torque requirement was approximately:

T_i = FL/2pi(n)

T_T = 2FL/2pi(n)

T_S =FR_T(2)(N)

Torque per leadscrew: 11.47 in·lbf

Combined torque: 22.94 in·lbf (2.59 N·m)

A factor of safety of 4 was then applied to determine the design torque requirement.

The resulting combined design torque was approximately 10.36 N·m.

This value provides the preliminary torque requirement for selecting the mechanical drive system. Actual operating torque will also depend on the selected nut, lubrication, alignment, and friction.

### Commercial Leadscrew Selection

After determining the minimum diameter, rotational speed range, and torque requirements, the team moved toward selecting a commercially available leadscrew.

The selected design uses two identical Roton 1/2-10 Acme leadscrews. The 1/2-inch nominal diameter exceeds the calculated minimum diameter of approximately 4.99 mm, while the 0.100-inch lead provides the required crosshead speed range at approximately 0.394–19.69 RPM.

Using identical leadscrews also allows both sides of the crosshead to move together, helping maintain alignment during tensile testing.

### Commercial Leadscrew Selection

After determining the minimum diameter, rotational speed range, and torque requirements, the team moved toward selecting a commercially available leadscrew.

The selected design uses two identical Roton 1/2-10 Acme leadscrews. The 1/2-inch nominal diameter exceeds the calculated minimum diameter of approximately 4.99 mm, while the 0.100-inch lead provides the required crosshead speed range at approximately 0.394–19.69 RPM.

Using identical leadscrews also allows both sides of the crosshead to move together, helping maintain alignment during tensile testing.

Supporting images:

<img width="1900" height="168" alt="image" src="https://github.com/user-attachments/assets/aa0031a3-4414-48de-8108-a3649117f5ba" />

Design Outcome:

The calculations established the initial requirements for the tensile tester's leadscrew system. The team determined the minimum required screw diameter, the rotational speed range needed to achieve the specified crosshead speeds, and the preliminary torque requirement for the drive system.

These calculations provided the foundation for selecting the commercial leadscrews and developing the remaining mechanical design. Supporting images:

<img width="882" height="1166" alt="image" src="https://github.com/user-attachments/assets/47c75de2-f43a-4732-ab93-79f9e9fdb0b1" />

## Select A Nut/Flange: Lexie Cox

[POST LEXIE COX WORK HERE]

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

Next is the drawing for the crosshead. Sketches are shown below. Holes are measured as 1 inch.

<img width="815" height="560" alt="Screenshot 2026-11-11 022726" src="https://github.com/user-attachments/assets/bfb13a9d-6845-4214-ab2d-bd48df564444" />

## Parametric Modeling - Morgan Gregory

I began by parametrically designing the crosshead in SolidWorks as shown below.

<img width="921" height="80" alt="Screenshot 2026-11-11 024233" src="https://github.com/user-attachments/assets/29580b4e-d0f6-4a64-8e92-e44987ca6df0" />

<img width="1286" height="485" alt="Screenshot 2026-11-11 023803" src="https://github.com/user-attachments/assets/15550050-a56b-4826-ae16-8d31d3f2f1a3" />

<img width="1916" height="840" alt="Screenshot 2026-11-11 023825" src="https://github.com/user-attachments/assets/d7b39dca-a8ec-4d0b-ad0f-25a821cd01d5" />

<img width="1004" height="401" alt="Screenshot 2026-11-11 024035" src="https://github.com/user-attachments/assets/4a1bf308-5c17-4c5a-a4f2-e7d3bcb047f7" />

<img width="877" height="379" alt="Screenshot 2026-11-11 024724" src="https://github.com/user-attachments/assets/126b65e4-0d19-46a3-b7df-75318240341a" />

The SolidWorks Assembly is shown below and the part file for the crosshead and the assembly are below.

<img width="987" height="532" alt="Screenshot 2026-11-11 025027" src="https://github.com/user-attachments/assets/8e32cfa0-bbb3-433f-a800-716765722860" />

<img width="792" height="636" alt="Screenshot 2026-11-11 212015" src="https://github.com/user-attachments/assets/5f4432a0-2152-4537-a683-64869a254aef" />

<img width="721" height="625" alt="Screenshot 2026-11-11 212020" src="https://github.com/user-attachments/assets/b79079df-91e3-4370-81d2-e75f68558de0" />

[Crosshead.zip](https://github.com/user-attachments/files/34723579/Crosshead.zip)

[A10Assembly.zip](https://github.com/user-attachments/files/34723581/A10Assembly.zip)

## Tabulating Costs: Morgan Gregory

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| --- | ---: | --- | ---: | ---: | --- |
| Leadscrew | 2 | Ethan | $56.52 | $113.04 | [Roton 59837](https://www.roton.com/product/acme-stainless-steel-screw-right-59837/) |
| Nut/Flange | 2 | Lexie | $178.60 | $357.20 | [McMaster-Carr 97790A110](https://www.mcmaster.com/97790A110/) |

## Lessons Learned: Lexie Cox

[Insert Lexie Cox WORK HERE]

## References

https://mechanicalc.com/reference/beam-deflection-tables

https://repositum.tuwien.at/bitstream/20.500.12708/200949/1/Demmel%20Stella%20-%202024%20-%20Design%20manufacturing%20and%20testing%20of%20an%20open-source...pdf
