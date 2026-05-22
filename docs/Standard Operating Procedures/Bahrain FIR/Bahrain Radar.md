---
title: "Bahrain Radar [OBBB_CTR]"
toc_min_heading_level: 2
toc_max_heading_level: 6
---

### Amendment History

| **Revision** | **Effective Date** | **Notes**           |
|--------------|--------------------|---------------------|
| Version 1    | 13AUG25            | Initial Publication |
| Version 2    | 30OCT25            | Revision #1         |
| Version 3    | 07MAY26            | Revision #2         |

---

## Sub-Sectors

<p align="center">
  <strong>SECTOR DIAGRAM</strong><br>
</p>
![Bahrain RDR](img/BahrainRDR.png#center)

| **Position** | **Sector** | **Frequency** |
|--------------|-------------------|-------------------------|
| OBBB_1_CTR        | Central Super/Bandbox             | 127.525                |
| OBBB_2_CTR        | East Higher             | 132.125              |
| OBBB_3_CTR        | North Higher             | 127.575               |
| OBBB_CH_CTR        | Central Higher             | 124.300               |
| OBBB_CL_CTR        | Central Lower             | 122.300               |
| OBBB_N_CTR        | North Lower             | 126.700                |
| OBBB_E_CTR        | East Lower             | 132.850                |

### Connection Hierarchy

| **Position** | **Prerequisite Sector** | **Notes** |
|--------------|-------------------|-------------------------|
| OBBB_1_CTR        | N/A             | Bandbox Position                |
| OBBB_2_CTR        | OBBB_1_CTR             |              |
| OBBB_3_CTR        | OBBB_1_CTR             |                |
| OBBB_CH_CTR        | OBBB_1_CTR             |                |
| OBBB_CL_CTR        | OBBB_CH_CTR, OBBB_1_CTR             | Can be opened without BBCH with prior permission.               |
| OBBB_N_CTR        | OBBB_3_CTR, OBBB_1_CTR             | Can be opened without BB3 with prior permission.                |
| OBBB_E_CTR        | OBBB_2_CTR, OBBB_1_CTR             | Can be opened without BB2 with prior permission.                |

## Sector Responsibilities

| **Sector** | **Primary Responsibility** |
|------------|----------------------------|
| OBBB_1_CTR | Central supervisory/bandbox operations and overall FIR flow management. |
| OBBB_2_CTR | OMAE inbound and outbound traffic flows. |
| OBBB_3_CTR | Northern Gulf and Kuwait traffic flows. |
| OBBB_CH_CTR | Upper-level central Bahrain FIR operations. |
| OBBB_CL_CTR | Lower-level inbound sequencing into OBBI. |
| OBBB_N_CTR | Northern lower airspace and Kuwait coordination. |
| OBBB_E_CTR | Eastern lower airspace and UAE coordination. |

---

## Surrounding Airspaces

<p align="center">
  <strong>BAHRAIN ACC</strong><br>
</p>
![Bahrain AIR](img/BahrainAIR.png#center)

---

## General Procedures

### Airway Clearances

In the Bahrain FIR, airway clearances **must** be given on initial contact.

> **ENR Controller:** _**"FDB738, Bahrain Radar, Identified. Cleared airway P559 NALPO."**_

### Radar Identification Procedures

Aircraft shall not be considered radar identified until the controller has verified the aircraft position and observed the assigned squawk code.

Acceptable methods of radar identification include:

- Observation of an aircraft squawking an assigned discrete SSR code.
- Identification transfer from another radar controller.
- Position correlation with reported navigation fixes.
- ADS-B or Mode S identification where applicable.

***Radar Identification Example***

> **ENR Controller:** _**"GFA512, Bahrain Radar, identified, cleared airway P559 NALPO."**_

If an aircraft is observed squawking an incorrect code, the controller shall instruct the pilot to reset the assigned transponder code prior to continuing radar services.

!!!node "Radar Identification"
    Controllers shall ensure radar identification is maintained at all times whilst providing radar separation services.

### Radar Identification Procedures 
Aircraft shall not be considered radar identified until the controller has verified the aircraft position and observed the assigned squawk code. 

Acceptable methods of radar identification include: 

- Observation of an aircraft squawking an assigned discrete SSR code.
- Identification transfer from another radar controller.
- Position correlation with reported navigation fixes.
- ADS-B or Mode S identification where applicable.

***Radar Identification Example*** 

> **ENR Controller:** _**"GFA512, Bahrain Radar, identified, cleared airway P559 NALPO."**_

If an aircraft is observed squawking an incorrect code, the controller shall instruct the pilot to reset the assigned transponder code prior to continuing radar services. 

!!!node "Radar Identification" 
  Controllers shall ensure radar identification is maintained at all times whilst providing radar separation services.    

### Minimum Separation

Aircraft operating in the Bahrain FIR, excluding the TMA and CTR, will be separated by 1000ft vertically.

| **Traffic distance from Radar Head** |  **Minimum Lateral Separation** |
|--------------------------------------|---------------------------------|
|             > 150 NM                 |               10NM              |
|             < 150 NM                 |               5NM               |

!!!node "Exceptions"
    When one aircraft is supersonic, the minimum lateral separation is **increased to 20 NM**.

### RVSM Procedures

Reduced Vertical Separation Minimum (RVSM) operations are applicable within the Bahrain FIR between FL290 and FL410 inclusive.

Controllers shall ensure:

- Aircraft are RVSM approved when operating within RVSM airspace.
- Standard vertical separation of 1000 ft is maintained within RVSM airspace.
- Non-RVSM aircraft are handled in accordance with applicable separation requirements.

---

### Supersonic Operations 

Supersonic aircraft operating within the Bahrain FIR require increased separation standards. 

When one aircraft is operating at supersonic speeds:
- Minimum lateral separation shall increase to 20 NM.
- Controllers should anticipate rapid closure rates and descent planning requirements.

### Sector Coordination & Handoffs

Controllers operating within the Bahrain FIR shall ensure coordination is completed prior to transferring aircraft between sectors.

This includes coordination of:

- Cleared level
- Direct routings
- Speed restrictions
- Holding instructions
- Non-standard operations

Where operationally practical, silent handoffs may be utilised between Bahrain ACC sectors provided there are no changes to the aircraft’s clearance or profile.

Non-standard climb, descent or routing requests must be coordinated with the receiving FIR prior to approval.

!!!node "Transfer Expectations"
    Aircraft should normally be transferred prior to entering the receiving controller’s area of responsibility unless otherwise coordinated.

## Initial Descents 

Bahrain Radar is responsible for initiating descents of arrivals to neighbouring FIRs, prominently the OMAE and OTDF FIRs. This must be done in accordance with the established Letters of Agreement and local procedures. This facilitates orderly sequencing by the receiving ACC into congested terminal manoeuvring areas such as Dubai International Airport. 

| **Waypoint** | **Descent level** | **Responsible Sectors** |       **Destination**         | **Extra notes** |
|--------------|-------------------|-------------------------|-------------------------------|-----------------|
| KUMBO        | FL220             | OBBB_N/1                | OKKK                          |                 |
| DEKTA        | FL290             | OBBB_3/N/1              | OTHH                          |                 |
| GIRMO        | FL210             | OBBB_CL/1               | OTHH                          |                 |
| LADNA        | FL330             | OBBB_CH/1               | OTHH                          |                 |
| GEXIM        | FL290             | OBBB_CL/1               | OTHH                          |                 |
| DEGSO        | FL310             | OBBB_2/1                | OMDB, OMDW, OMSJ, OMRK, OMFJ  | Airway M677     |
| TOMSO        | FL310             | OBBB_2/1                | OMDB, OMDW, OMSJ, OMRK, OMFJ  | Airway P559     |
| ALKAN        | FL240             | OBBB_E                  | OBBI                          |                 |
| OBROS        | FL160             | OBBB_E                  | OBBI                          |                 |
| OBROS        | FL180             | OBBB_E                  | OEDF                          |                 |

!!!node "LOAs"
    For traffic inbound into the OMAE or OTDF FIRs, please refer to our LOA with the Arabian vACC [here](https://docs.khaleejvacc.net/Published%20Documents/Letter%20of%20Agreements/Arabian%20Letter%20of%20Agreement/).
    
## Speed Control Procedures

Bahrain Radar may utilise speed control to assist with sequencing and traffic flow management.

Typical speed control measures include:

- Mach Number restrictions above FL280.
- IAS restrictions during descent sequencing.
- Reductions for spacing into OBBI, OMAE and OTDF arrivals.

Unless otherwise instructed:

- Aircraft shall comply with 250 KIAS below FL100.
- Controllers should avoid excessive speed reductions that may negatively affect sequencing efficiency.

***Speed Control Example***

> **ENR Controller:** _**"UAE221, reduce speed Mach decimal 78."**_

> **ENR Controller:** _**"QTR818, maintain 280 knots."**_

## Enroute Holds

| **Hold Identifier** | **Vertical Limits** | **Inbound Holding Course** | **Leg Time** | **Turn Direction** |
|:-------------------:|:-------------------:|:--------------------------:|--------------|--------------------|
|        ITNAS        |   6000ft -  FL460   |            320°            |    1.5       |        Right       |
|        VELOG        |   5000ft -  FL290   |            142°            |    1.5       |        Left        |
|        ALMOK        |   6000ft -  FL460   |            288°            |    1.5       |        Right       |
|        SOLOB        |   6000ft -  FL460   |            294°            |    1.5       |        Right       |
