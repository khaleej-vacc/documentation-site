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

### Minimum Separation

Aircraft operating in the Bahrain FIR, excluding the TMA and CTR, will be separated by 1000ft vertically.

| **Traffic distance from Radar Head** |  **Minimum Lateral Separation** |
|--------------------------------------|---------------------------------|
|             > 150 NM                 |               10NM              |
|             < 150 NM                 |               5NM               |

!!!node "Exceptions"
    When one aircraft is supersonic, the minimum lateral separation is **increased to 20 NM**.

---

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
| ALKAN        | FL240             | OBBB_1                  | OBBI                          |                 |
| OBROS        | FL160             | OBBB_1                  | OBBI                          |                 |

!!!node "LOAs"
    For traffic inbound into the OMAE or OTDF FIRs, please refer to our LOA with the Arabian vACC [here](https://docs.khaleejvacc.net/Published%20Documents/Letter%20of%20Agreements/Arabian%20Letter%20of%20Agreement/).

---

## Enroute Holds

| **Hold Identifier** | **Vertical Limits** | **Inbound Holding Course** | **Leg Time** | **Turn Direction** |
|:-------------------:|:-------------------:|:--------------------------:|--------------|--------------------|
|        ITNAS        |   6000ft -  FL460   |            320°            |    1.5       |        Right       |
|        VELOG        |   5000ft -  FL290   |            142°            |    1.5       |        Left        |
|        ALMOK        |   6000ft -  FL460   |            288°            |    1.5       |        Right       |
|        SOLOB        |   6000ft -  FL460   |            294°            |    1.5       |        Right       |
