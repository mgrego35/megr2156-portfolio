# A7 – FEA on Bracket

## The Assignment

The assignment this week was to perform a finite element analysis on the bracket we designed in A6. This will allow us to see whether or not it needs to be changed or if it fits into the parameters we were given.

## Keeping Consistency

For the stress analysis each time, the same process/study was used. 

## First FEA

The first analysis did not go as expected at all. The parameters we needed to keep consistent were .005 inch maximum deflection, a safety factor of 4 which means a maximum stress of 10 ksi given the yield strength of 40 ksi. The stress and deflection that resulted are shown in the images below.

<img width="1194" height="608" alt="Screenshot 2026-10-21 143544" src="https://github.com/user-attachments/assets/5cfdea95-441c-46c6-852f-057df406458e" />

<img width="1266" height="618" alt="Screenshot 2026-10-21 143553" src="https://github.com/user-attachments/assets/3239fa45-5c9e-41eb-8168-33324c043e18" />

The stress gave a safety factor of around .025, very far from 4, and the deflection was 43.866 inches and it was shown at the end of A. The max stress was found to be spread throughout part B. To combat this, I decided to make part B extend way further than it did before which gave me the new bracket shown below.

<img width="906" height="166" alt="Screenshot 2026-10-21 144653" src="https://github.com/user-attachments/assets/bf989b06-9c8c-46e8-afd5-31aafef525d2" />

<img width="824" height="607" alt="Screenshot 2026-10-21 144645" src="https://github.com/user-attachments/assets/f673c17b-ac7f-46a1-b316-92ecd51061f7" />

## Second FEA

The second FEA went way better than the first, but it still did not meet the expectations it was supposed to. The max stress was 29.033 which gives a safety factor of 1.38, and it occurred at the top of where A and B met. The max deflection was also off, being .021 inches at the end of A again. The images below show the stress and deflections mapped.

<img width="1355" height="624" alt="Screenshot 2026-10-21 145334" src="https://github.com/user-attachments/assets/c6a4f744-9725-405a-967f-002a92e3b6c3" />

<img width="1386" height="603" alt="Screenshot 2026-10-21 145353" src="https://github.com/user-attachments/assets/1f4bc7a4-67ec-4c16-a4e1-1cdcc3547537" />

To fix the stress areas, and ensure that the third design would be my last, I first changed the sketch variables to make the thicknesses slightly bigger, which can be seen in the sketch below.

<img width="906" height="163" alt="Screenshot 2026-10-21 151439" src="https://github.com/user-attachments/assets/afc2b56b-4781-4de3-9bab-c5c7123996e2" />

<img width="1416" height="599" alt="Screenshot 2026-10-21 151430" src="https://github.com/user-attachments/assets/71bcfbb2-149a-488d-a217-89138c36e115" />

I then added fillets of .2 inches to ensure extra strength at the top connection between B and C.

<img width="999" height="589" alt="Screenshot 2026-10-21 151302" src="https://github.com/user-attachments/assets/6a55543a-a988-4a58-907c-3190b2a5f209" />

<img width="856" height="632" alt="Screenshot 2026-10-21 151404" src="https://github.com/user-attachments/assets/4302c780-6f9f-43b4-aba4-e7f23de6b24f" />

The result is shown below.

<img width="800" height="538" alt="Screenshot 2026-10-21 151449" src="https://github.com/user-attachments/assets/1fbfa088-4471-4f96-88ca-91811e434363" />

## Third FEA

The third FEA went perfectly. The maximum stress was 7.857 ksi, which occurred between B and C at the corner of the fillet, giving a safety factor of 5.09. The maximum deflection was .004 inches and it occurred at the end of A, which is .001 inches under our maximum. The stress and deflection maps are shown below.

<img width="1314" height="669" alt="Screenshot 2026-10-21 150933" src="https://github.com/user-attachments/assets/69a03e7b-9cd3-4a4e-bbbf-2953c71a74ae" />

<img width="1428" height="654" alt="Screenshot 2026-10-21 150940" src="https://github.com/user-attachments/assets/b56310dc-e369-4dbc-9db4-264c7ee77fab" />

## Analysis










