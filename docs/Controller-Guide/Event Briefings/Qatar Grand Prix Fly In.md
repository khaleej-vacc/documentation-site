---
title: Qatar Grand Prix Fly In
---

Welcome to the controller briefing for the Qatar Grand Prix Fly In.

Please navigate to the relevant pages under the Table of Contents on the right hand side. <br> **Ensure that all relevant sections are read prior to logging on.**

## 1. General Notices

- All controllers **must** have the latest [sector file package](https://www.khaleejvacc.net/sectorfiles).
- VACS **should be in use at all times**. Where no profile is available, Discord coordination should be used as a substitute.
- Event traffic should always be prioritised.
- There are **no event slots** for this event, and VATCAN will **not** be in use.
- A-CDM **will** be in use at OTHH. See [4.3.1 Usage of CDM](#531-usage-of-cdm).
- OTHH will be operating **Independent Parallel Approaches** for the duration of the event. See [3.6 Doha Director](#46-doha-director-doh_fx_app).

---

## 2. Enroute (CTR)

| Radio Callsign                | Logon Callsign | Coordination Name | Frequency |
| :---------------------------: | :------------: | :---------------: | :-------: |
| Bahrain Radar (Central Super) | OBBB_1_CTR     | ACC CS            | 127.525   |
| Doha Control (North Low)      | OTDF_N1_CTR    | ACC N             | 135.725   |
| Doha Control (North High)     | OTDF_N2_CTR    | ACC NH            | 133.150   |
| Doha Control (South)          | OTDF_S_CTR     | ACC S             | 132.975   |

Sectorisation and extra information for the Doha FIR can be found [here](https://docs.khaleejvacc.net/Standard-Operating-Procedures/Enroute%20Procedures/Doha%20%28OTDF%29/2.%20Airspace/ "Opens in new tab"){target="_blank"}.

### 2.1 Bahrain Radar Central (OBBB_x_CTR)

This applies to all Bahrain Central sectors (CH, CL and CS).

Traffic via GEXIM and GIRMO is expected to be mainly non-event traffic. GIRMO will mainly carry OKKK traffic.

Bahrain must ensure that arrivals into OTHH and OTBD are at the following levels:

| Arrivals via | Level                                          | Next Sector                |
| :----------: | :--------------------------------------------: | :------------------------: |
| GEXIM        | **FL270** <br> FL290 as contingency only       | ACC S (OTDF_S_CTR)         |
| GIRMO        | **FL210**                                      | ACC N (OTDF_N1_CTR)        |

- FL270 is the primary level at GEXIM. FL290 shall only be used as a contingency when traffic levels are high.
- All arrivals into Doha must be handed off with **at least 8NM in trail**.

### 2.2 Doha Control North (OTDF_N1_CTR / OTDF_N2_CTR)

- Arrivals via GIRMO will be transferred to ACC N (OTDF_N1_CTR) at **FL210**.
- Clear traffic for the arrival only. **Do not** assign a runway or expected approach type.
- Traffic shall be released to **RDR N (DOH_R1_APP)** at or above FL210.

### 2.3 Doha Control South (OTDF_S_CTR)

- Arrivals via GEXIM will be transferred from OBBB to ACC S (OTDF_S_CTR) at **FL270**, or FL290 as a contingency.
- Clear traffic for the arrival only. **Do not** assign a runway or expected approach type.
- Traffic shall be cleared to **FL250** before release to **RDR N (DOH_R1_APP)**.

---

## 3. Terminal (APP)

| Radio Callsign          | Logon Callsign | Coordination Name | Frequency |
| :---------------------: | :------------: | :---------------: | :-------: |
| Doha Radar (North)      | DOH_R1_APP     | RDR N             | 121.100   |
| Doha Radar (South)      | DOH_R2_APP     | RDR S             | 120.675   |
| Doha Approach (West)    | DOH_A1_APP     | APP W             | 119.725   |
| Doha Approach (East)    | DOH_A2_APP     | APP E             | 124.775   |
| Doha Director (16L/34R) | DOH_F1_APP     | FIN E             | 119.400   |
| Doha Director (16R/34L) | DOH_F2_APP     | FIN W             | 124.050   |

![Doha FIR Sectors](../../../img/OT/Doha_FIR_Sectors.png#center)

General procedures for the Doha TMA can be found [here](https://docs.khaleejvacc.net/Standard-Operating-Procedures/Terminal%20Procedures/Doha%20%28DOH%29/general-procedures/ "Opens in new tab"){target="_blank"}.

### 3.1 Runway Allocation

The table below is an **example only** and is **not** to be used unless confirmed:

| Arrivals via                | Downwind | Runway   | APP Sector          | FIN Sector          |
| :-------------------------: | :------: | :------: | :-----------------: | :-----------------: |
| HAYYA, VEDED, ALKAN, TOSNA  | Eastern  | 16L/34R  | APP E (DOH_A2_APP)  | FIN E (DOH_F1_APP)  |
| TOVOX, LAEEB, ORLEK         | Western  | 16R/34L  | APP W (DOH_A1_APP)  | FIN W (DOH_F2_APP)  |

### 3.2 Doha Radar North (DOH_R1_APP)

| Arrivals                    | Departures                          |
| :-------------------------: | :---------------------------------: |
| HAYYA, VEDED, ALKAN, TOSNA  | TULUB, LUBET, ALVEN, VAXIN, ALSEM   |

- All arrivals shall be cleared to **13,000FT** before release to the relevant APP sector (DOH_Ax_APP).
- Transfer traffic **no later than 5,000FT before it reaches its cleared level**, so the next sector can issue further descent without the aircraft levelling off.

### 3.3 Doha Radar South (DOH_R2_APP)

| Arrivals             | Departures                    |
| :------------------: | :---------------------------: |
| TOVOX, LAEEB, ORLEK  | KUPRO, BUNDU, ULIKA, DATRI    |

- All arrivals shall be cleared to **13,000FT** before release to the relevant APP sector (DOH_Ax_APP).
- Transfer traffic **no later than 5,000FT before it reaches its cleared level**, so the next sector can issue further descent without the aircraft levelling off.

### 3.4 Doha Approach West (DOH_A1_APP)

- All departures shall be cleared to **12,000FT** before release to the relevant RDR sector (DOH_Rx_APP).
- Arrivals on the western downwind shall be cleared to **6,000FT** before release to the relevant FIN sector (DOH_Fx_APP). Traffic must be released **no later than KIPIK**.
- Arrivals shall be handed off to FIN at **190KT**, unless otherwise coordinated.

### 3.5 Doha Approach East (DOH_A2_APP)

- All departures shall be cleared to **12,000FT** before release to the relevant RDR sector (DOH_Rx_APP).
- Arrivals on the eastern downwind shall be cleared to **5,000FT** before release to the relevant FIN sector (DOH_Fx_APP). Traffic must be released **no later than EGNUG**.
- Arrivals shall be handed off to FIN at **190KT**, unless otherwise coordinated.

### 3.6 Doha Director (DOH_Fx_APP)

!!! warning "Independent Parallel Approaches"
    OTHH will be operating Independent Parallel Approaches during the event.

| Sector              | Responsibility                                  |
| :-----------------: | :---------------------------------------------: |
| FIN E (DOH_F1_APP)  | Runway 16L/34R                                  |
| FIN W (DOH_F2_APP)  | Runway 16R/34L, and all OTBD traffic            |

- When **only one** Director is online, FIN E (DOH_F1_APP) is combined and **all handoffs shall be made to DOH_F1_APP**. This includes OTBD traffic.
- Traffic on the eastern downwind for runway 16L/34R is **not** to be turned until maintaining **2,500FT**.

#### 3.6.1 Final Approach Spacing

Arrivals shall be spaced by **at least 5.5NM** on the localiser.

- This spacing creates a gap between each arrival so that **one departure can be released** from the same runway before the next arrival.
- 6NM is a **minimum**. Do not compress below it, even if traffic is building on the downwind. Extend downwinds or use speed control instead.
- Where RECAT wake turbulence separation requires more than 6NM, the larger spacing shall be applied.
- Spacing should be set up before the localiser intercept. Use the speed control in 3.6.2 to hold it on final.

!!! note
    Coordination between FIN and Hamad Tower for departure gaps will be added with the Aerodrome section.

#### 3.6.2 Speed Control

| Aircraft       | Speed Restriction                  |
| :------------: | :--------------------------------: |
| All aircraft   | 190KT to 10 DME, 160KT to 4 DME    |
| A380           | 190KT to 10 DME, 160KT to 5 DME    |

#### 3.6.3 Platform Altitudes

=== "Northerly Config"

    | ICAO | Runway | Platform Altitude    |
    | :--: | :----: | :------------------: |
    | OTHH | 34R    | 2,500FT at LAGMA     |
    | OTHH | 34L    | 3,500FT at IMKAT     |
    | OTBD | 33     | 4,500FT at NAJMA     |

=== "Southerly Config"

    | ICAO | Runway | Platform Altitude    |
    | :--: | :----: | :------------------: |
    | OTHH | 16L    | 2,500FT at TOVAN     |
    | OTHH | 16R    | 3,500FT at GOLSI     |
    | OTBD | 15     | 4,500FT at MAXMO     |

---

## 4. Aerodrome (TWR/GND/DEL)

| Radio Callsign           | Logon Callsign | Coordination Name | Frequency |
| :----------------------: | :------------: | :---------------: | :-------: |
| Hamad Tower (East)       | OTHH_1_TWR     | AIR 1             | 118.525   |
| Hamad Tower (West)       | OTHH_2_TWR     | AIR 2             | 118.025   |
| Hamad Ground (East)      | OTHH_1_GND     | GMC 1             | 120.225   |
| Hamad Ground (Central)   | OTHH_2_GND     | GMC 2             | 118.650   |
| Hamad Ground (West)      | OTHH_3_GND     | GMC 3             | 118.575   |
| Hamad Ground (Overflow)  | OTHH_4_GND     | GMC 4             | 118.075   |
| Hamad Ground (Planner)   | OTHH_5_GND     | GMC P             | 119.075   |
| Hamad Clearance Delivery | OTHH_DEL       | GMP               | 120.875   |

![AOR30R](../../../img/OT/othh_aor.png#center)

### 4.1 Hamad Tower (OTHH_x_TWR)

- Hamad Tower should adhere to CTOTs to the best of their ability, to limit sector overload in the Doha TMA and adjacent sectors.
- If the conditions allow for it, ensure RRSM is used at all times with arrivals and departures.
- Ensure the arrival taxi routes below are used:

| Runway | Taxi Route |
|:------:|:-----------:|
|   16L  |      Continue via R, hold short of TWY C     |
|   16R  |    Continue southbound on TWY K/M     |
|   34L  |    Continue southbound on TWY M/K, hold FALCO<br>**OR**<br>Continue northbound on TWY K if planned stand is north of TWY L6    |
|   34R  |      Continue via R, hold short of TWY C     |

### 4.2 Hamad Ground (OTHH_x_GND)

- Ensure you do not taxi aircraft past your AoR. Remember to instruct aircraft to hold short of a taxiway before handoff to AIR. It is not your responsibility to taxi traffic to holding points.

### 4.3 Hamad Clearance Delivery (OTHH_DEL)

- CDM must be used at all times.
- Only **GMP (OTHH_DEL)**, or **GMC P (OTHH_5_GND)** if online, shall enable CDM for OTHH as the master user. All other controllers shall use the `.cdm slave OTHH` command instead.
- Pilots are expected to submit their TOBT via the [VDGS Dashboard](https://vats.im/vdgs "Opens in new tab"){target="_blank"}.
- Non-event aircraft may be given ATC clearance as normal, with CDM used for start clearance.

#### 4.3.1 Usage of CDM

1. When an aircraft calls for clearance, check that it has a TOBT. If the pilot has not submitted one via the VDGS Dashboard, set it for them.
2. Pilots **do not** know their TSAT, so pass it with the clearance:

    > **GMP:** "QTR138, readback correct. Expect push at time 08:30z."

3. When an aircraft calls ready for push, left click the **TOBT** column and generate a **TSAT**.
4. If the TSAT is in **dark green**, hand the aircraft over to the relevant GMC controller. Otherwise, instruct the pilot to monitor GMC at **TSAT ±2 minutes** and standby for further instructions.

---

!!! note
    If any pilot does not adhere to any ATC restrictions, you shall quote **Code of Conduct B12** and utilise the `.wallop` command if necessary.
