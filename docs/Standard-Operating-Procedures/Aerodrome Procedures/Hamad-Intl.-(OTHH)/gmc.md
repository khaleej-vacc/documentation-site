# 3. Ground Movement Procedures
## 3.1 General Provisions
The Ground Movement Controller (GMC) is responsible for managing aircraft movements on all aerodrome movement areas except for runways and their associated taxiways. Departing aircraft are given pushback instructions and instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed to taxi as appropriate.

---

## 3.2 Designated areas of responsibility
### 3.2.1 GMC positions
Doha-Hamad Airport operates three GMC positions: GMC 1, GMC 2, and GMC 3.

![AOR30R](../../../img/OT/othh_aor.png#center)

#### 3.2.1.1 GMC 1 Responsibilities
GMC 1 manages aircraft movements in the following areas and their associated taxiways:

- Concourse B  
- Concourse C (East Side)  
- Concourse E  
- Remote Transfer G  
- Cargo Apron  
- Maintenance Apron  
- Apron 4  

#### 3.2.1.2 GMC 2 Responsibilities
GMC 2 manages aircraft movements in the following areas and their associated taxiways:

- Concourse A  
- Concourse C (West Side)  
- Concourse D  
- Apron 3
- Remote Transfer H1  
- Apron 5  

#### 3.2.1.3 GMC 3 Responsibilities
GMC 3 manages aircraft movements in the following area and its associated taxiways:

- Apron 6  

### 3.2.2 Handoff procedures
Aircraft must not be cleared beyond a controller’s area of responsibility unless prior coordination has been completed with the next controller. Hold short instructions may be used to prevent an aircraft from entering another controller’s area without coordination.


### 3.2.3 Splitting procedure
When a single GMC controller is online, they shall manage all surface movement areas from the GMC 1 position. 

If GMC 1 and GMC 2 are online without GMC 3, GMC 2 will cover the central and western side of the aerodrome (Everything **west of TWY D**) while SMC E must cover the east side of the aerodrome (Everything **east of TWY D**).

Unless otherwise authorized by Khaleej vACC staff, GMP (Hamad Delivery) must be online before a second or third GMC (Hamad Ground) position may be opened.

If GMP is not online, GMC shall assume the responsibilities of the lower controller.

<p align="center">
  <strong>Figure 3-1 - Connection Hierarchy</strong><br>
</p>
| Position      |       Prerequisite Position      |               Notes                   |
|---------------|--------------------------------|---------------------------------------|
|   OTHH_1_GND  |           N/A                  |       Bandbox                  |
|   OTHH_DEL  |           N/A                  |                         |
|   OTHH_2_GND  |           OTHH_1_GND,<br>OTHH_DEL                  |                         |
|   OTHH_3_GND  |           OTHH_1_GND,<br>OTHH_2_GND,<br>OTHH_DEL                  |                         |

---

## 3.3 Departure pushback procedures
### 3.3.1 General pushback procedures
When aircraft have been handed off from GMP, they shall be fully ready for pushback, and have reached their TOBT. Assuming no obstructions, they shall be instructed to push back immediately. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

Aircraft requesting push that are not squawking their assigned transponder code shall be instructed to hold position and squawk the correct code. They must not be allowed to move until doing so. 

Pushback direction is based primarily on aircraft location and runway configuration. 

All code F aircraft (A380/B747-8) are not permitted to be pushed onto taxiway W (between taxiway H and stand A4), taxiway E (between taxiway D and stand B2), or taxiway Y.

A pushback clearance must be a variant of those provided in 3.3.1 and include an instruction to “FACE NORTH”, “FACE EAST", “FACE SOUTH" or “FACE WEST” as appropriate with the taxiway to push onto.

!!! example
    **Pilot**: "Hamad Ground, QTR1, on stand A8 request pushback."

    **Controller**: "QTR1, Hamad Ground, pushback approved, face West on W."

    **Pilot**: "Pushback approved, facing West on W, QTR1."

Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
    **Pilot**: "Hamad Ground, FDB12, on stand G3C request pushback."

    **Controller**: "FDB12, Hamad Ground, behind the company 737 passing left to right, pushback approved, face South on E2, behind."

    **Pilot**: "Behind the company 737 passes from left to right, pushback approved, facing South on E2, behind, FDB12."

### 3.3.2 Pushback types
#### 3.3.2.1 Standard pushback
This type will normally have the aircraft stop abeam the adjacent stand. The phraseology for this type of pushback is identical to the pushback phraseology as provided in 3.3.1.

#### 3.3.2.2 Short pushback
A short pushback instruction shall require the aircraft to complete the pushback abeam the current stand such that the adjacent stand will not be blocked.

!!! example
    **Pilot**: "Hamad Ground, IBE0392, on stand H10 request pushback."

    **Controller**: "IBE0392, Hamad Ground, short pushback approved, face south on J to finish abeam stand H10."

    **Pilot**: "Short pushback approved, facing south on J to finish abeam stand H10, IBE0392."

#### 3.3.2.3 Long pushback
A long pushback instruction shall require aircraft to complete the pushback operation two stands away from where the pushback was commenced. This manoeuvre may be used when aircraft are vacating a stand to be used by another aircraft that is taxiing in.

!!! example
    **Pilot**: "Hamad Ground, QTR1184, on stand A7 request pushback."

    **Controller**: "QTR1184, Hamad Ground, long pushback approved, face west on W1 to finish abeam stand A3."

    **Pilot**: "Long pushback approved, facing west on W1 to finish abeam stand A3, QTR1184."

### 3.3.3 Simultaneous pushback operations
Simultaneous pushbacks may be permitted from adjacent stands provided aircraft are instructed to manoeuvre in accordance with 3.3.2 such that on completion of both aircraft’s pushback operation, they will be separated on the taxiway by two aircraft stands.

### 3.3.4 Pushback Operations

<p align="center">
  <strong>Figure 3-2 - Pushback Instructions</strong><br>
</p>
| **Concourse/Apron**     | **Instruction Details**                                                                                                                                                    |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Concourse A**         | Aircraft face West onto taxiway W and W1. <br> Stand A11: face North or South depending on departure runway. <br> Occasionally pushed onto W2 facing West.                 |
| **Concourse B**         | Aircraft face East onto taxiway E and E1. <br> Stand B10: face North or South depending on departure runway. <br> Occasionally pushed onto E2 facing East.                 |
| **Concourse C**         | Stands C1-C8: push back facing South onto E1 or W1. <br> Stands C9-C12: push back facing North onto E4 or W4. <br> Occasionally pushed onto E2/W2 (South) or E3/W3 (North).|
| **Concourse D**         | Aircraft face North onto W4. <br> Occasionally pushed onto W3 facing North. <br> Stands 223-226 push on to J in the appropriate direction based on active runway |
| **Concourse E**         | Aircraft face North onto E4. <br> Occasionally pushed onto E3 facing North. <br> Stands 124R, 125 and 126 push on to C in the appropriate direction based on active runway. |
| **Apron 3**   | Aircraft face East or West depending on departure runway onto N.                                                                                                           |
| **Remote Transfer H**   | Stands H1-H2: push back facing West onto W2. <br> Stand H3C: push back facing South onto W2. <br> Stands H4-H6: push back facing North onto W3. <br> Stands H7-H10: push back North or South onto J. <br> Occasionally pushed onto W1 (South/West) or W4 (North). |
| **Remote Transfer G**   | Stands G1-G2: push back facing East onto E2. <br> Stand G3C: push back facing South onto E2. <br> Stands G4-G6: push back facing North onto E3. <br> Stands G7-G10: push back North or South onto C. <br> Occasionally pushed onto E1 (South/East) or E4 (North). |
| **Apron Cargo**         | Aircraft face North or South depending on departure runway onto F.                                                                                                         |
| **Apron V & Emiri Apron** | Stands V1-V7: face North or South onto V. <br> Stands V8-V12: push back North or South onto C.                                                                           |
| **Apron 4**             | Aircraft face North or South depending on departure runway onto C or Q.                                                                                                    |
| **Apron 5**             | Aircraft face North or South depending on departure runway onto K. <br> Stands 551-564: face West onto Y.                                                                  |
| **Apron 6**             | Departures from runway 34L: face South onto S2 or S4. <br> Departures from runway 34R: face North. <br> Departures from runways 16L or 16R: face North onto S2 or S4.      |

!!! warning
    Particular caution should be exercised when pushing traffic on Concourse D and E on to taxiway J and C respectively

---

## 3.4 Departure taxi procedures
### 3.4.1 General departure taxi procedures
Aircraft should be assigned the most suitable taxi route for their designated departure runway. 

Code F aircraft (A380/B747-8) are not permitted to taxi onto taxiway W (between taxiway H and stand A4), taxiway E (between taxiway D and stand B2), or taxiway Y. 

!!! info
    Aircraft should not be taxied to the runway holding points, transfer of control to AIR shall be made early enough such that the aircraft is not required to stop its taxi.

!!! example
    **Pilot**: "QTR3B, request taxi."

    **Controller**: "QTR3B, Taxi via E1, C, hold short taxiway L2."

    **Pilot**: "Taxi via E1, C, hold short taxiway L2, QTR3B."

To deconflict traffic, and to reduce the length of taxi clearances, intermediate holding points shall be used wherever possible.

!!! example
    **Pilot**: "QTR98K, request taxi."

    **Controller**: "QTR98K, taxi via W2, hold short J."

    **Pilot**: "Taxi via W2, hold short J, QTR98K."

### 3.4.2 Taxiway Reporting Points
Mandatory taxiway reporting points have been introduced at Hamad. Aircraft are required to stop at these points unless explicitly instructed by ATC to proceed further. 

The reporting points may **not** be used when RVR is below 600M.

!!! note
    Taxiway reporting points are not currently provided in any generally available scenery. Until such a time as they are, pilots should not be expected to stop at them and should continue to be issued "hold short of taxiway" instructions as in the existing procedures to avoid confusion.

Reporting points are outlined below:

<p align="center">
  <strong>Figure 3-3 - Position Reporting Points</strong><br>
</p>
| **Runway** | **Reporting Point** | **Location**               |
|------------|---------------------|----------------------------|
|  16L/34R   | DUKAN               | Taxiway B, short of A12    |
|            | FALAH               | Taxiway C, short of A12    |
|            | MAKIN               | Taxiway B, short of A1     |
|            | LAFAN               | Taxiway C, short of A1     |
| Taxiway C  | OMRAN               | Taxiway C, between R and F |
|  16R/34L   | FLORA               | Taxiway J, short of L11    |
|            | NAJIM               | Taxiway K, short of L11    |
|            | RAYAN               | Taxiway M, short of M13    |
|            | ASTON               | Taxiway R, short of M      |
|            | SHIPO               | Taxiway S, short of M      |
|            | KATTY               | Taxiway J, short of L1     |
|            | HARMO               | Taxiway K, short of L1     |
|            | DAFNA               | Taxiway M, short of M2     |
|            | NUSUK               | Taxiway R, short of K      |
|            | DASHA               | Taxiway S, short of K      |
|            | FALCO               | Taxiway K, short of R      |
|            | FANAR               | Taxiway K, short of S      |


!!! example
    **Controller:** "Taxi via E4 and C, hold at LAFAN, short of taxiway A1."

!!! warning
    Handoff to the tower controller shall be initiated earlier than the hold to allow for the appropriate sequencing to take place. For example, when taxiing to 34L, traffic should be passed to Tower when reaching the E1/A3 intersection on taxiway B/C, and similar for the other runways.


### 3.4.3 Departure Taxi Diagrams

Blue lines indicate departure taxi routes. Yellow lines indicate arrival taxi routes. Runway holding points are shown in red.

Taxiways with a red background are not code F (A380/B747-8) compatible.

=== "34L"

    <p style="text-align: center; font-style: italic;">
    Figure 3.4-3 - Hamad RWY34L Departure Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_dep_34L.png#center)

=== "34R"

    <p style="text-align: center; font-style: italic;">
    Figure 3.4-4 - Hamad RWY34R Departure Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_dep_34R.png#center)

=== "16L"

    <p style="text-align: center; font-style: italic;">
    Figure 3.4-1 - Hamad RWY16L Departure Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_dep_16L.png#center)

=== "16R"

    <p style="text-align: center; font-style: italic;">
    Figure 3.4-2 - Hamad RWY16R Departure Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_dep_16R.png#center)

---

### 3.5 Arrival Taxi Diagrams

=== "34L"

    <p style="text-align: center; font-style: italic;">
    Figure 3.5-2 - Hamad RWY34L Arrival Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_arr_34L.png#center)

=== "34R"

    <p style="text-align: center; font-style: italic;">
    Figure 3.5-1 - Hamad RWY34R Arrival Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_arr_34R.png#center)

=== "16L"

    <p style="text-align: center; font-style: italic;">
    Figure 3.5-4 - Hamad RWY16L Arrival Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_arr_16L.png#center)

=== "16R"

    <p style="text-align: center; font-style: italic;">
    Figure 3.5-3 - Hamad RWY16R Arrival Taxi Flow
    </p>
    ![Hamad Taxi Flow](../../../img/OT/othh_arr_16R.png#center)

---

### 3.5.1 Stand allocation procedure
<p align="center">
  <strong>Figure 3.5.1-1 - Stand Allocation Procedures</strong><br>
</p>
|  Apron/Concourse  |                     Operator                    |
|:-----------------:|:-----------------------------------------------:|
|    Concourse A    |           International Operators, QTR          |
|    Concourse B    |           International Operators, QTR          |
|    Concourse C    |           International Operators, QTR          |
|    Concourse D    |           International Operators, QTR          |
|    Concourse E    |           International Operators, QTR          |
| Apron 3           |                       QTR                       |
| Remote Transfer G | Low Cost Carriers, International Operators, QTR |
| Remote Transfer H | Low Cost Carriers, International Operators, QTR |
|    Cargo Apron    |              Cargo, QTR (Overflow)              |
| Apron V & Emiri Apron  |            Government & State Aircraft          |
|      Apron 4      |                       QTR                       |
|      Apron 5      |                       QTR                       |
|      Apron 6      |                       QTR                       |


### 3.5.2 Stand restrictions
<p align="center">
  <strong>Figure 3.5.2-1 - Stands</strong><br>
</p>
| **Location**                                                                  | **Aircraft Code Handling**                                                                                                                                                      |
|-------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Concourse A to E (including Apron 3 and Remote Transfer Aprons)** | All stands can handle aircraft up to code E. Stands with designators of L or R are limited to code C.                                                                           |
| **Cargo Apron**                                                               | All stands can handle aircraft up to code E.                                                                                                                                    |
| **Apron V & Emiri Apron**                       | All stands can handle aircraft up to code E. Stands with designators of L or R are limited to code C.                                                                           |
| **Apron 4**                                                                   | All stands can handle aircraft up to code C.                                                                                                                                    |
| **Apron 5**                                                                   | All stands can handle aircraft up to code E. Stands with designators of L or R are limited to code C. Stands 551 to 564 are limited to code C.                                  |
| **Apron 6**                                                                   | All stands can handle aircraft up to code E. Stands with designators of L or R are limited to code C.                                                                           |
| **Specific Stands**                                                           | Stands A3, A5, B1, B3, C12, C13, V1, V2, 604, 607, 611, and 614 can handle aircraft up to code F. H1 and G1 can handle aircraft up to code F with certain handling limitations. |

---

## 3.6 Low visibility operations (LVO)
### 3.6.1 LVO taxi routes
When LVO is in effect, aircraft should avoid crossing the runways whenever possible. All taxiways are approved for LVO operations, and there are no taxiway restrictions.

During LVO, only designated CAT II/III holding points shall be used (4.7.2).

---

## 3.7 Parking Stands
Throughout this document references will be made to the various concourses/aprons at Hamad. Below are the concourses and their associated stand references, as well as A380 Stand details. This information is visible on the Parking Chart.

<p align="center">
  <strong>Figure 3.7-1 - Stand Information</strong><br>
</p>
| **Concourse**         | **Stand Information**                  | **A380 Stands**   |
|-----------------------|----------------------------------------|-------------------|
| **Concourse A**       | Stands A1-A11                          | A3, A5            |
| **Concourse B**       | Stands B1-B10                          | B1, B3            |
| **Concourse C**       | Stands C1-C13                          | C12, C13          |
| **Concourse D**       | Stands 217-226                         | None Available    |
| **Concourse E**       | Stands 118-126                         | None Available    |
| **Remote Transfer G** | Stands G1-G10                          | G1                |
| **Remote Transfer H** | Stands H1-H10                          | H1                |
| **Apron 3**           | Stands 301-309                         | None Available    |
| **Apron 4**           | Stands W425E-W429E                     | None Available    |
| **Apron 5**           | Stands 501-564                         | None Available    |
| **Apron 6**           | Stands 601-637                         | 604, 607, 611, 614|
| **Cargo**             | Stands F1-F16                          | None Available    |
| **Maintenance**       | Stands Q1-Q51                          | Q4, Q20, Q21, Q40, Q41|
| **Victor Apron**      | Stands V6-V12                          | None Available    |
| **Emiri Apron**       | Stands V1-V5                           | V1, V2            |