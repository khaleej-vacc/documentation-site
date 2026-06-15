# 2. Departure Clearance Procedures
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filled on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

---

## 2.2 Departure clearance
### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

- Callsign;
- Aircraft type;
- Parking Stand;
- Destination;

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMC shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

!!! example
    **Pilot**: "Doha Ground, good evening, QQE990, Gulfstream 650ER, stand A6, clearance to Nice, with information W on board."

    **Controller**: "QQE990, information W correct, cleared to Nice via the LUBET2N departure, climb via the SID altitude 5000FT, squawk 2613."

    **Pilot**: "Cleared to Nice, LUBET2N departure, climb via the SID altitude 5000FT, squawk 2613, QQE990."

    **Controller**: "QQE990, readback correct, QNH 1004, report ready for pushback."

### 2.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!! info
    Controllers shall ensure that DCL is available to be used at all times.

### 2.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency.

### 2.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

---

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Doha primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use. 

Doha RNAV Standard Instrument Departures (SIDs) operate independently from those at Hamad. Both airports conduct simultaneous departures.

|   SID 15  | Inital Climb |   SID 33  | Inital Climb |
|:---------:|:------------:|:---------:|:------------:|
|  ALSEM3S  |    6000FT    |  ALSEM3N  |    5000FT    |
|  ALVEN3S  |    6000FT    |  ALVEN3N  |    5000FT    |
|  BUNDU3S  |    6000FT    |  BUNDU3N  |    5000FT    |
|  DATRI1S  |    6000FT    |  DATRI1N  |    6000FT    |
|  KUPRO1S  |    6000FT    |  KUPRO1N  |    5000FT    |
|  LUBET2S  |    6000FT    |  LUBET2N  |    5000FT    |
|  PATOM3S  |    6000FT    |  PATOM3M  |    5000FT    |
|  TULUB2S  |    6000FT    |  TULUB2N  |    5000FT    |
|  ULIKA1S  |    6000FT    |  ULIKA1N  |    6000FT    |
|  VAXIN3S  |    6000FT    |  VAXIN3N  |    5000FT    |

All IFR departures shall be instructed to contact Doha Approach (West) once airborne.

| First Fix |    15   |    33   |
|:---------:|:-------:|:-------:|
|   ALSEM   |    3S   |    3N   |
|   ALVEN   |    3S   |    3N   |
|   BUNDU   |    3S   |    3N   |
|   DATRI   |    1S   |    1N   |
|   KUPRO   |    1S   |    1N   |
|   LUBET   |    2S   |    2N   |
|   PATOM   |    3S   |    3N   |
|   TULUB   |    2S   |    2N   |
|   ULIKA   |    1S   |    1N   |
|   VAXIN   |    3S   |    3N   |

### 2.3.2 Radar vectors departure
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Doha Approach airspace, radar departures are given radar vectors to the first fix.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initial climb;
- Assigned SSR code

Aircraft on a radar vectors departure shall have the text RDV inserted to the scratchpad section of their entry on the departure list and have an initial climb set to **2,000 feet**.

All radar vectors departures shall be instructed to contact Doha Approach (West) once airborne.

!!! example
    **Pilot**: "Doha Ground, good evening, TCM1TM, Airbus A320, stand A15, clearance to Jeddah, unable RNAV, with information Z on board."

    **Controller**: "TCM1TM, information Z correct, cleared to Jeddah, fly runway heading, expect radar vectors after departure, maintain altitude 2000FT, squawk 2610."

    **Pilot**: "Cleared to Jeddah, fly runway heading, expect radar vectors after departure, maintain altitude 2000FT, squawk 2610, TCM1TM."

    **Controller**: "TCM1TM, readback correct, QNH 1014, report ready for pushback."

---

## 2.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-3. 

Several routing restrictions exist within Qatari airspace and are detailed in the Qatari Route Manual which must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Khaleej vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight.

!!! example
    **Controller**: "QQE650, cleared to Dubai, runway 15 via ALSEM3S, ALSEM - L305 - ITBUL, flight planned route. Climb via the SID altitude 6000FT, squawk 2612."

| Destination                                              | Level Restriction        | Routing                        |
|----------------------------------------------------------|--------------------------|--------------------------------|
| Northern Emirates (OMDB, OMDW, OMSJ, OMRK, OMFJ)         | FL210                    | ALSEM L305 ASTOG               |
| Transiting Tehran FIR (FL200 @ ALKAN)                    | FL230                    | VAXIN T800 DASUT               |
| Transiting Tehran FIR (FL190 @ RAGAS)                    | FL190                    | ALVEN T430 RAGAS               |
| Southern Emirates (OMAA, OMAD, OMAM, OMAL)               | FL270                    | KUPRO                          |
| Bahrain (OBBI, OBBS, OBKH)                               | 12,000FT                 | TULUB B457 / M444 / T444 KINID |
| Transiting Bahrain FIR onwards landing Kuwait FIR        | FL430                    | TULUB M444 KINID               |
| Transiting Jeddah FIR onwards landing Kuwait FIR         | FL280                    | TULUB B457 KINID               |
| Transiting Kuwait FIR                                    | FL320                    | LUBET L934 IMLAD               |

---

## 2.5 Requested cruising level
### 2.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 7.1 of the [Khaleej vACC Training vMATS](https://docs.khaleejvacc.net/Training%20vMATS/%28S1%29%20Developing%20Controller%20Training%20vMATS/7.%20Cruising%20Flight%20Levels/01-%207.1%20Cruising%20Flight%20level/). This is based on direction and type of flight. 

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

---

## 2.6 Delay mitigation
### 2.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! example
    **Controller**: "QQE101, hold position. Number 2 for startup, expect pushback at time 45."

---

## 2.7 Runway change procedure
Runway changes must be coordinated between Doha AIR, Hamad AIR, and Doha APP due to the interdependencies outlined in section 4.2. AIR must give GMC sufficient notice before altering the runway configuration. 

Coordination between AIR, GMC, and approach/departure is required for the final departure using the previous configuration. 

Aircraft already cleared for departure under the old configuration must be re-cleared if they have not yet requested pushback.

---

## 2.8 VFR aircraft
VFR traffic clearances are managed by AIR at the holding point. When an aircraft first contacts the ground frequency, it must provide the following information:

- Callsign;
- Aircraft type;
- Current position;
- Person(s) on board;
- Current ATIS;
- Intentions;

After the initial call with all required information, GMC will taxi the aircraft to the active runway and relay the details to AIR for coordination.

!!! example
    **Pilot**: "Doha Ground, A7DDD, Diamond DA40, at the civil aviation college apron, 2 POB, with information C, for local flight to the west, request taxi."

    **Controller**: "A7DDD, Doha Ground, information C is correct, taxi via Q and hold short runway 15."

    **Pilot**: "taxi via Q and hold short runway 15, A7DDD."

    **Controller**: "ADD, contact Doha Tower on 118.900."

    **Pilot**: "Doha Tower on 118.900, ADD."