---
title: "Bahrain Delivery [OBBI_DEL]"
toc_min_heading_level: 2
toc_max_heading_level: 6
---

## **Bahrain Delivery [OBBI_DEL]**

### Amendment History

| **Revision** | **Effective Date** | **Notes**           |
|--------------|--------------------|---------------------|
| Version 1    | 13AUG25            | Initial Publication |
| Version 2    | 30OCT25            | Revision #1         |

----

## Chapter 1. Position Overview 
**Bahrain Delivery (DLV)** provides aircraft with a departure clearance and is responsible for passing the ATIS (Automatic Terminal Information Service) to the pilot. DLV Controller should ensure the flight plan filed by the pilot is correct and that the departure list is updated to indicate the correct initial heading after departure, the initial altitude and assigned squawk code. 

Once clearance has been issued and readback correctly from the pilot the DLV controller will transfer the aircraft to the SMC controller when they report they are ready for pushback and start. During busy periods the SMC Controller can inform the DLV Controller of the requirement to not release aircraft in order to restrict the rate of departures, reducing the workload. 

----

## Chapter 2. GEN | Standard Operating Procedures 

### 2.1 Issuing IFR Clearances 
It is the responsibility of the **DLV Controller** to issue clearances to departing aircraft. You might expect the following information to be passed from the pilot tot he **DLV Controller** on initial contact.

- Stand Number.
- Aircraft Type.
- Current ATIS Information Code they are in receipt of.
- Current QNH as reported in the ATIS. 

----

An **IFR Clearance** should have the following information in this order: 

- Callsign
- Destination 
- Airway Clearance 
- Initial Heading After Departure
- Initial Altitude 
- Assigned Squawk 

***IFR Departure Clearance Example***

> **DLV Controller:** _**"GFA178, cleared to Dubai via the N697 Airway to SODAK, after departure fly heading 345 degrees, initial climb 4000ft, squawk 4212"**_

The DLV Controller **must** obtain a full and correct read back of the departure clearance. If they do not, then the pilot must be challenged to read back the full and correct departure clearance. 

***Challenge Example***

> **DLV Controller:** _**"GFA178, Negative. Cleared to Dubai via the N697 Airway to SODAK, after departure fly heading 345 degrees, inital climb altitude 4000ft, squawk 4212"**_

!!!node "Be Paitent and Assist"
    If you are required to challenge a pilot for a correct readback, repeat it back clearly and slowly to ensure the pilot has opportunity to understand the information provided. Be mindful that there are always new joiners to the VATSIM network, so assisting them is key!

Once the pilot has correctly read back the clearance, if the pilot did not provide the current ATIS letter on initial contact, the DLV Controller will provide this to the pilot once read back has been provided. 

> **DLV Controller:** _**"GFA178, read back is correct, information Alpha is current, report when ready for push and start."**_

When the aircraft has reported ready for push and start they will be transferred to the SMC Controller and it is to be assumed by the SMC Controller that the pilot has a **correct clearance and has confirmed the latest ATIS Letter.** 

### 2.1.1 Airway Clearances
Due to the lack of Standard Instrument Departures out of Bahrain all aircraft should provided with an airway clearance followed by an initial heading to fly after departure. 
The initial heading that the aircraft is given is based on their direction of flight (see Section 2.2 Departure Procedures) however the initial heading is to take them in the direction of the airway they have filed from the **BHR VHF Omnidirectional Range (VOR)**. 

The BHR VOR is located on the approach path to RWY30R prior to the threshold, this VOR has multiple airways associated to it, pilots will typically file a flightplan (FPL) which starts at BHR then an airway to take them into en-route environment. 

So an aircraft with the following route string **BHR A453 DAVUS** would be cleared to their destination via the A453 Airway to DAVUS. 

To prevent the aircraft after departure immediately turning for the BHR VOR they are provided with the initial heading to fly which will then allow the Approach Controller to safely and efficently to manage them onto the appropiate airway. 

### 2.1.2 Datalink Clearances (DCL)
Bahrain offers the ability for pilots to request and receive their **departure clearance via datalink (DCL).** This helps reduce frequency congestion and reduces the workload of the DLV Controller. This service can only be provided to pilots whom's aircraft has sufficent systems installed such as ACARS to send and receive text messages from a controlling unit. 
It is a requirement of the DLV Controller to ensure datalink is available at all times.

### 2.1.3 Incorrect Filed Flight Plans
It is the responsibility of the DLV Controller to ensure flight plans are correctly filed and using valid routings in conjunction with the RouteChecker. 
If routes are not filed correctly you must inform the pilot that they have filed an incorrect flight plan by **private message.** 

If a pilot calls on frequency before you have the chance to send the **private message** please advise the pilot on frequency to expect a route change via **private message**.

You can use tools such as SimBrief to provide pilots with valid routings. **Khaleej vACC** actively ensures routes are updated in SimBrief for pilots to use. 

### 2.1.4 Filed Flight Levels 
**Bahrain Delivery (DLV)** must ensure pilots are filing correct flight levels in accordance with their filed routings. If pilots have incorrectly filed flight levels in their flight plan you must inform the pilot to refile their flight plan via **private message**. 

Bahrain utilises the Semi-Circular Rule. Flights flying Westbound should file **Even** levels and flights flying Eastbound should file **Odd** levels. 

### 2.1.5 Flight Level Capping 
Multiple destinations across the Gulf Region have level capped routings due to operational reasons. The DLV Controller shall ensure adherence to the below table, it is the responsibility of the DLV Controller to ensure aircraft have filed a correct level in the their flight plan prior to issuing a clearance. If an incorrect level has been filed the DLV Controller shall inform the pilot (through private message/on frequency) that they are required to file a revised flight plan with the new level in accordance with the below table for level capped routings. 

| **Destination** | **Max Altitude / Flight Level** |
|:---------------:|:-------------------------------:|
|       OT**      |             11000ft             |
|       OM**      |              FL250              |
|       OKKK      |              FL260              |
|       OEDF      |              6000ft             |

### 2.1.6 Flow Restrictions

#### 2.1.6.1 Target Off Block Time (TOBT)
When A-CDM procedures are active (typically during busy events), pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controllers client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is cancelled, and a new TOBT is assigned.

Please note TOBTs are only issued during certain events, this will outlined to via Khaleej vACC Staff if TOBT procedures are to be implemented for that particular event. You are required to tell the appropriate member of staff if you're not familiar with A-CDM procedures. 

### 2.2 Departure Procedures
Bahrain does not have any published Standard Instrument Departures (SIDs). Instead, Delivery will assign an initial heading to departing aircraft. 

The Aircraft will then be provided radar vectors from Bahrain Approach after departure. 

| **Runway** | **Initial Takeoff Heading** |     **Route**    |
|:----------:|:---------------------------:|:----------------:|
|     30R    |             300°            |    B457 NARMI    |
|     30R    |             345°            | All Other Routes |
|     12L    |             075°            | All Routes       |

!!!node "Initial Climb"
    The initial climb for aircraft departing Bahrain International Airport is **3000ft for propeller aircraft** and **4000ft for jet aircraft.** 

### 2.3 VFR Procedures 

- VFR Flights shall not take place above FL150 to prevent entering the Class A Airspace.
- VFR Flights are not permitted when the ceiling is less than 1500ft or when the ground visibility is less than 5KM. 
- **Bahrain Tower (TWR)** and **Bahrain Approach (APP)** both hold the authority to delay VFR flights into either **Class D Control Zone** or the **Class C Terminal Manevuering Area** if traffic levels permit.
- All VFR departures shall be assigned a discrete SSR code so that positive identification is established. 
- VFR aircraft are assigned discrete, or specific, four-digit squawk codes to allow for positive identification on radar, especially when flying through controlled airspace.

#### 2.3.1 VFR Departures
VFR Departures VFR Flights planning to depart **Bahrain International Airport (OBBI)** to leave the **Control Zone (CTR)** must first have prior approval from the APP Controller to enter the **Terminal Manevuering Area (TMA)**. There are no published VFR routes in the Bahrain CTR. Aircraft shall therefore be cleared on track to their destination.

#### 2.3.2 VFR Clearances
DLV is responsible for issuing VFR Clearances as well. Prior to issuing a VFR Clearance to any traffic, DLV must coordinate with TWR to ensure the TWR controller can accept local traffic into his CTR. TWR has the authority to delay traffic into his CTR if the traffic load is high. The TWR Controller must provide a estimated delay time to the DLV Controller to pass to the pilot. 

#### 2.3.3 VFR Circuits
Once **Bahrain Delivery (DLV)** has recieved confirmation from the TWR controller that they are happy to accept **VFR Circuit Traffic** they can continue with issuing a VFR clearance to the aircraft. Please see below the standard pattern information below.

!!!node "Act Promptly"
    When you see a pilot file a VFR FPL ensure you act promptly and efficently and coordinate with the relevant controller to ensure they are able to accept the aircraft into their airspace. Do not wait for the pilot to call up on frequency before coordinating with the relevant ATS Unit. 

| **Runway Configuration** | **Direction** | **Altitude** |
|:------------------------:|:-------------:|:------------:|
|            30R           |   Right Hand  |    1000ft    |
|            12L           |   Left Hand   |    1000ft    |

***VFR Circuit Clearance Example***

> **DLV Controller:** _**"A9C-ZZ, cleared right hand circuits RWY30R, not above altitude 1000ft VFR, squawk 7001"**_

The DLV Controller **must** obtain a full and correct read back of the departure clearance. If they do not, then the pilot must be challenged to read back the full and correct departure clearance. 

Once the pilot has correctly read back the clearance, if the pilot did not provide the current ATIS letter on initial contact, the DLV Controller will provide this to the pilot once read back has been provided. 

> **DLV Controller:** _**"A-ZZ, read back is correct, information Alpha is current, report ready for startup."**_

!!!node "Callsign Shortening" 
    After initial contact has been made and established with the aircraft, you can shorten the callsign from A9C-ZZ to A-ZZ, read as Alpha - Zulu - Zulu. This is to reduce frequency congestion.


### 2.4 VFR Departures into Uncontrolled Airspace

There are no published VFR routes in the Bahrain CTR. Aircraft shall therefore be cleared on track to their destination. 

All VFR departures shall be assigned a discrete SSR code so that positive identification is established. 

**Example:**
Pilot:
>"BAHRAIN Delivery, A9C-AA, requesting departure to the South on track Sakhir Air base (OKBH)"

Controller:
>"A9C-AA, BAHRAIN Delivery, cleared on track SAKHIR, altitude 1000 feet VFR, Squawk 6006"

Pilot:
>"Cleared on track SAHIR, Altitude 1000 feet VFR, Squawk 6006"

Controller:
>"A9C-AA, Readback Correct, information Charlie current, QNH 1011, report ready for startup"

### 2.4.1 VFR Departures into Controlled Airspace

VFR aircraft requesting clearance to climb into approach airspace (above 2,500 ft inside the CTR or above 1,000 ft AGL outside the CTR) shall only be cleared after prior coordination with APP. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

**Example:**
Pilot:
>"Bahrain Delivery, A9C-AA, request departure to the west on track DAMMAM, altitude 6000 feet."

Controller:
>"A9C-AA, Bahrain Delivery, cleared on track DAMMAM, altitude 6000 feet VFR, squawk 6001."

Pilot:
>"Cleared on track DAMMAM, altitude 6000 feet VFR, squawk 6001."

Controller:
>"A9C-AA, readback correct, information Charlie current, QNH 1011, report ready for start-up."

