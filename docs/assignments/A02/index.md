# A2 – Truss Stress Analysis

## Objectives

- Design a lightweight planar truss using A500 steel or an alternative material.

- Create free body diagrams (FBDs) for joints and critical pins.

- Calculate the required cross-sectional area of truss elements with a safety factor.

- Determine pin sizes based on shear forces with a safety factor.

- Solve equations symbolically and numerically for both truss and pin design.

- Estimate the total weight of the truss and pins.

- Create a CAD model with accurate dimensions and connections.

- Compare CAD weight predictions with hand calculations.

- Document key engineering lessons learned from the process.

## The Assignment

The assignment given was to design a truss given this template shown below.

<img width="437" height="266" alt="Screenshot 2026-09-03 032750" src="https://github.com/user-attachments/assets/1e7e93a3-3c69-493a-ba2f-213d8cbc92e1" />

## Truss Design

The first step was to design the truss. I kept it simple with a cross beam going through the middle of the trapezoid from point A to point C. The truss design is shown below.

<img width="436" height="231" alt="Screenshot 2026-09-03 032647" src="https://github.com/user-attachments/assets/e513cffd-bb40-4ed0-98e0-0ddc6a741743" />

## Calculations of Internal Forces

The first thing I needed to do was find the internal forces. This will allow us to find the minimum cross sectional dimensions of the beams. I chose the force P to be 28 kilonewtons. The first point I drew a free body diagram for was point D. this point was the easiest to get started on. The internal forces of AD and CD were found using this free body diagram.

<img width="948" height="267" alt="Screenshot 2026-09-03 033915" src="https://github.com/user-attachments/assets/0a218129-88d0-4a50-9f01-d4c565eaa67f" />

The next point I analyzed was point C in order to find AC and BC.

<img width="950" height="498" alt="Screenshot 2026-09-03 034203" src="https://github.com/user-attachments/assets/a7de99a5-26f4-464a-902e-a304783f65c0" />

The final point I needed to analyze was point B in order to find AB and By.

<img width="947" height="231" alt="Screenshot 2026-09-03 034317" src="https://github.com/user-attachments/assets/b0e93202-6d42-46bf-844c-46b5dc7b70a6" />

After finding By I could find Ay shown below.

<img width="913" height="75" alt="Screenshot 2026-09-03 034908" src="https://github.com/user-attachments/assets/d4fe37e4-bf56-4741-88e1-03472a444811" />

A chart of all of the final internal forces is shown below.

<img width="443" height="249" alt="Screenshot 2026-09-03 034958" src="https://github.com/user-attachments/assets/46ada717-e676-4be6-a59d-79d403aa0657" />

## Cross Sectional Area of Beam Calculation

The largest force (35 kilonewtons) was used to calculate the minimum cross sectional area. The yield strength of 270 mPa was used (found on https://beamdimensions.com/materials/Steel/ASTM/ASTM_A500/) for the calculations alongside a safety factor of 3.5.

<img width="920" height="246" alt="Screenshot 2026-09-03 040205" src="https://github.com/user-attachments/assets/aeaf21b6-95de-43f9-9f64-2b4faefcb7fc" />

## Cross Sectional Area of Pins Calculation

The largest force at a pin connection (9.34 kilonewtons) was used for the minimum cross sectional area of the pins with a safety factor of 4 and a yield strength of 170 ksi.

<img width="962" height="405" alt="Screenshot 2026-09-03 040223" src="https://github.com/user-attachments/assets/04001772-c195-46c0-b412-5a37d5e389fc" />

## Lesson Learned

I learned how to use safety factors and yield strengths, alongside known forces in order to find minimum dimensions to create a safe end product.






