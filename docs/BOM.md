# Rev A BOM

31 BOM lines, 62 assembled parts. Source: [`CAN485-dongle-jlcpcb-bom.csv`](../hardware/rev-a/CAN485-dongle-jlcpcb-bom.csv).

H1/H2, fiducials, test points, and solder jumpers are PCB/mechanical features and are not in the assembly BOM.

| Qty | Designators | Value | Footprint | MPN | LCSC | Manufacturer |
|---:|---|---|---|---|---|---|
| 2 | C1,C2 | 4u7 | `Capacitor_SMD:C_0805_2012Metric` | CL21A475KAQNNNE | C1779 | Samsung |
| 15 | C4,C5,C6,C7,C8,C9,C11,C16,C18,C20,C23,C24,C26,C29,C31 | 100n | `Capacitor_SMD:C_0402_1005Metric` | CL05B104KO5NNNC | C1525 | Samsung |
| 2 | C12,C17 | 4n7 | `Capacitor_SMD:C_0402_1005Metric` | 0402B472K500NT | C1538 | FH |
| 2 | C13,C14 | 30p | `Capacitor_SMD:C_0402_1005Metric` | CC0402JRNPO9BN300 | C107004 | YAGEO |
| 1 | C15 | 1u | `Capacitor_SMD:C_0402_1005Metric` | CL05A105KA5NQNC | C52923 | Samsung |
| 3 | C19,C21,C27 | 10n | `Capacitor_SMD:C_0402_1005Metric` | CL05B103KB5NNNC | C15195 | Samsung |
| 5 | C3,C22,C25,C28,C30 | 10u | `Capacitor_SMD:C_0805_2012Metric` | CL21A106KAYNNNE | C15850 | Samsung |
| 1 | D1 | SMAJ5.0A | `Diode_SMD:D_SMA` | SMAJ5.0A | C83329 | Littelfuse |
| 1 | D2 | Green | `LED_SMD:LED_0805_2012Metric` | LTST-C171KGKT | C98224 | Lite-On |
| 1 | D3 | Orange | `LED_SMD:LED_0805_2012Metric` | LTST-C171KFKT | C284932 | Lite-On |
| 1 | D4 | Blue | `LED_SMD:LED_0805_2012Metric` | LTST-C171TBKT | C98225 | Lite-On |
| 1 | D5 | NUP2105LT1G | `Package_TO_SOT_SMD:SOT-23` | NUP2105LT1G | C14486 | onsemi |
| 1 | F1 | 0.5A | `CAN485-dongle:Fuse_1812_4532Metric` | MF-MSMF050-2 | C17313 | Bourns |
| 2 | FB2,FB3 | BLM18KG601SN1D | `Inductor_SMD:L_0603_1608Metric` | BLM18KG601SN1D | C85833 | Murata |
| 1 | J1 | USB4085-GF-A | `CAN485-dongle:USB_C_Receptacle_GCT_USB4085_Left` | USB4085-GF-A | C7095263 | GCT |
| 1 | J2 | DB2EVC-3.81-5P-GN | `CAN485-dongle:DB2EVC-3.81-5P` | DB2EVC-3.81-5P-GN | C395701 | DORABO |
| 2 | L1,L2 | ACT45B-510-2P | `CAN485-dongle:ACT45B-510-2P` | ACT45B-510-2P-TL003 | C76584 | TDK |
| 2 | R1,R2 | 22R | `Resistor_SMD:R_0402_1005Metric` | 0402WGF220JTCE | C25092 | UNI-ROYAL |
| 2 | R3,R4 | 5k1 | `Resistor_SMD:R_0402_1005Metric` | 0402WGF5101TCE | C25905 | UNI-ROYAL |
| 2 | R5,R6 | 10k | `Resistor_SMD:R_0402_1005Metric` | 0402WGF1002TCE | C25744 | UNI-ROYAL |
| 2 | R7,R8 | 60R4 | `Resistor_SMD:R_0603_1608Metric` | ERJ3EKF60R4V | C403298 | Panasonic |
| 1 | R9 | 120R | `Resistor_SMD:R_0603_1608Metric` | 0603WAF1200T5E | C22787 | UNI-ROYAL |
| 3 | R10,R11,R14 | 1k | `Resistor_SMD:R_0402_1005Metric` | 0402WGF1001TCE | C11702 | UNI-ROYAL |
| 1 | R12 | 1M | `Resistor_SMD:R_0402_1005Metric` | 0402WGF1004TCE | C26083 | UNI-ROYAL |
| 1 | U1 | STM32F072CBT6 | `Package_QFP:LQFP-48_7x7mm_P0.5mm` | STM32F072CBT6 | C81720 | STMicroelectronics |
| 1 | U2 | TLV75533PDBVR | `Package_TO_SOT_SMD:SOT-23-5` | TLV75533PDBVR | C404027 | Texas Instruments |
| 1 | U3 | ADM2582EBRWZ-REEL7 | `Package_SO:SOIC-20W_7.5x12.8mm_P1.27mm` | ADM2582EBRWZ-REEL7 | C39494 | Analog Devices |
| 1 | U4 | ADM3053BRWZ-REEL7 | `Package_SO:SOIC-20W_7.5x12.8mm_P1.27mm` | ADM3053BRWZ-REEL7 | C117821 | Analog Devices |
| 1 | U5 | TPD4E05U06DQAR | `Package_SON:USON-10_2.5x1.0mm_P0.5mm` | TPD4E05U06DQAR | C138714 | Texas Instruments |
| 1 | U6 | SM712.TCT | `Package_TO_SOT_SMD:SOT-23` | SM712.TCT | C12067 | Semtech |
| 1 | Y1 | 8MHz | `Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm` | XC32M4-8.000-F18LJDT | C2905353 | HCI |
