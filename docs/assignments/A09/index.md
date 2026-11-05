# A9 – Pulley System Design

## Instructions

Design a pulley system to transfer power between two parallel axes separated by a center distance of 4–6 inches. The system must meet the following requirements:

- Pulley Diameter: Both pulleys shall have a diameter of 3 inches.

- Rotational Speed: Select an operating speed between 1000–2000 rpm.

- Belt Tension (Static): Select a belt tension between 4–6 lbf under stationary conditions.

- Material: Pulleys may be made from aluminum, ABS, or steel, and may include a groove and shaft diameter of your choosing (within reasonable manufacturing limits).

- Safety Factor: The design must satisfy a minimum safety factor of 3.

- Assume the belt is made from polyurethane rubber, with a yield strength of 3.25 MPa (471 psi) at 20% strain

## Choosing a Belt

The first thing to do is to choose a belt from the link in the resources section by first calculating minimum dimensions. I first listed all knowns and unknowns for the problem.

<img width="751" height="314" alt="Screenshot 2026-11-03 212245" src="https://github.com/user-attachments/assets/17435df0-93af-4368-85b4-9b9cc6e420c2" />

Next I created a free body diagram shown below of the pulley in order to find the tension in the upper and lower sides.

<img width="844" height="217" alt="Screenshot 2026-11-03 212319" src="https://github.com/user-attachments/assets/1c5ac850-754e-4a44-8fbe-91d966931e5a" />

I then used the FBD and the equations to calculate the tensions in each side, and using the larger force to find the minimum cross sectional area, which allowed me to find the minimum diameter. 

<img width="908" height="380" alt="Screenshot 2026-11-03 212338" src="https://github.com/user-attachments/assets/1a10c76c-00c0-443d-a78a-cfd51c992d9d" />

The last thing I needed to calculate in order to pick out the belt was the length. My length calculations are based on the center distance and the half circumference of each wheel.

<img width="912" height="288" alt="Screenshot 2026-11-03 212345" src="https://github.com/user-attachments/assets/d76e4550-497e-486b-94c9-e38dea0157c3" />

The minimum diameter and length that fit best are .25 inches and 19.5 inches respectively. The material given was polyurethane rubber. My choice of belt is shown below.

<img width="890" height="676" alt="Screenshot 2026-11-03 213205" src="https://github.com/user-attachments/assets/0da9255c-bae8-4313-9571-284e5d260a1a" />

<img width="649" height="395" alt="Screenshot 2026-11-03 213221" src="https://github.com/user-attachments/assets/9ae91685-f0be-4c30-92c4-a956f036b3ed" />

## Choosing a Shaft

Now that we have chosen the belt it is time to find the minimum dimensions for the shaft. The given material is 1060 hardened steel.

I began by listing all knowns and unknowns. I also included the FBD for the shaft.

<img width="697" height="304" alt="Screenshot 2026-11-05 012734" src="https://github.com/user-attachments/assets/40bb6b9b-bbdf-4b4d-8fbc-87f3323bb566" />

I then used the torque stress equation to calculate the minimum diameter shown below.

<img width="815" height="552" alt="Screenshot 2026-11-05 012904" src="https://github.com/user-attachments/assets/95e66e8d-b775-417b-9822-eb33a6b2da28" />

The chosen shaft diameter is .25 inches which is above the .217 required minimum.

## Designing the Journal Bearing

I began by listing all knowns and unknowns.

<img width="569" height="201" alt="Screenshot 2026-11-05 013231" src="https://github.com/user-attachments/assets/069574ec-d662-4757-bd13-8e8985d71aa3" />

I then found the equation below in Machinery's Handbook in order to find the minimum outer diameter.

<img width="443" height="253" alt="Screenshot 2026-11-05 013417" src="https://github.com/user-attachments/assets/625d33b5-2f91-40c8-b2c2-e2edf0c84b83" />

The pressure needed to be calculated first. I found the pressure using the equation below starting from the force divided by the area and finding the formula for the "area of contact" which was the circumference times the length of the bearing.

<img width="696" height="86" alt="Screenshot 2026-11-05 013728" src="https://github.com/user-attachments/assets/006aec58-0b8d-49ff-ad1e-47144d0e618a" />

Then I used this value to find the outer diameter.

<img width="667" height="92" alt="Screenshot 2026-11-05 013735" src="https://github.com/user-attachments/assets/a09b6c37-e91c-48e5-adb2-d3fd3a5c9d93" />

Next I used the rotational velocity (N) to calculate the linear velocity. I converted it into fpm from in/min in order to calculate the PV rating.

<img width="749" height="149" alt="Screenshot 2026-11-05 013741" src="https://github.com/user-attachments/assets/a7cd280e-7849-4d8d-a028-8b1dc18525f0" />

The calculation of the PV rating is shown below.

<img width="721" height="102" alt="Screenshot 2026-11-05 013747" src="https://github.com/user-attachments/assets/d32d36ca-c0fd-46f0-bed2-f05290c23e77" />

In order to choose the material for the bearing I used the table below. The PV rating requirement was above 795.6

<img width="897" height="584" alt="Screenshot 2026-11-05 002352" src="https://github.com/user-attachments/assets/4b53caf2-a771-45ea-9a58-7da06399da2e" />

Final chosen material: Nylon

I chose the nylon because it is cheap compared to other materials on the list and it performs well under these conditions looking at the PV rating.

## Designing the 


## References

https://www.fabdigit.com/materials/steel-1060/q-t/

https://protoxyz.com/materials/plastic/ABS
