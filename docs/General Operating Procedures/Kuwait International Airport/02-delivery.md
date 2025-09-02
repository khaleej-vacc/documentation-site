---
title: Kuwait Delivery [OKKK_DEL]
toc_min_heading_level: 2
toc_max_heading_level: 5
---

# **Kuwait Delivery [OKKK_DEL]**

# Amendment History

| **Revision** | **Effective Date** |      **Notes**      |
|:------------:|:------------------:|:-------------------:|
|   Version 1  |       13AUG25      | Initial Publication |

----

# Chapter 1. Position Overview 
**Kuwait Delivery (DLV)** provides aircraft with a full departure clearance and is responsible for passing the local QNH as well as verifying the aircraft type of the departing aircraft. DLV Controller should ensure the flight plan filed by the pilot is correct and that the departure list is updated to indicate the correct assigned Standard Instrument Departure procedure, temporary altitude and assigned squawk code. 

Once clearance has been issued and readback correctly from the pilot the DLV controller will transfer the aircraft to the GMC controller when they report they are ready for pushback and start. During busy periods the GMC Controller can inform the DLV Controller of the requirement to not release aircraft in order to restrict the rate of departures. 

----

# Chapter 2. GEN | General Operating Procedures 

## 2.1 Issuing IFR Clearances 
It is the responsibility of the **DLV Controller** to issue clearances to departing aircraft. Pilots are expected to report the following information on initial contact with the **DLV Controller** when requesting clearance. 

- Callsign 
- Stand Number
- Aircraft Type
- Current ATIS Information Code they are in receipt of


The DLV Controller should ensure that both the **aircraft stand number and aircraft type** are confirmed by the pilot prior to issuing them with a departure clearance. Any departure clearance issued should be valid against the RouteChecker with a flight level that is **appropiate for the direction of flight**. 

An **IFR Clearance** should have the following information in this order: 

- Callsign
- Destination 
- Standard Instrument Departure (SID) 
- Initial Altitude 
- Assigned Squawk 

***IFR Departure Clearance Example***

> **DLV Controller:** **"JZR101, cleared to Bahrain, via the BOXIK4E Departure, climb initially altitude 4000ft, squawk 4212"**

!!!node "Departure Runway?"
    It is not a requirement for the DLV Controller to issue the departure runway in the IFR Clearance, it is expected the pilot has correctly listened to the D-ATIS

The DLV Controller **must** obtain a full and correct read back of the departure clearance. If they do not, then the pilot must be challenged to read back the full and correct departure clearance. 

***Challenge Example***

> **DLV Controller:** _**"JZR101, Negative. Cleared to Bahrain via the BOXIK4E Departure, climb initially altitude 4000ft, squawk 4212"**_

!!!node "Be Paitent and Assist"
    If you are required to challenge a pilot for a correct readback, repeat it back clearly and slowly to ensure the pilot has opportunity to understand the information provided

Once the pilot has correctly read back the clearance, if the pilot did not provide the current ATIS letter, you must provide it.

> **DLV Controller:** _**"JZR101, read back is correct, Information Alpha is current, report fully ready for push and start."**_

When the aircraft has reported ready for push and start they will be transferred to the GMC Controller and it is to be assumed by the GMC Controller that the pilot has a **correct clearance and is squawking his assigned transpoder code.** 

> **DLV Controller:** **JZR101, hold position, contact Kuwait Ground 121.700.**

### 2.1.1 Datalink Clearances (DCL)
Bahrain offers the ability for pilots to request and receive their **departure clearance via datalink (DCL).** This helps reduce frequency congestion and reduces the workload of the DLV Controller. This service can only be provided to pilots whom's aircraft has sufficent systems installed such as ACARS to send and receive text messages from a controlling unit. 

It is a requirement of the DLV Controller to ensure datalink is available at all times.

### 2.1.2 Incorrect Filed Flight Plans
It is the responsibility of the DLV Controller to ensure flight plans are correctly filed and using valid routings in conjunction with the RouteChecker. 
If routes are not filed correctly you must inform the pilot that they have filed an incorrect flight plan by **private message.** 

If a pilot calls on frequency before you have the chance to send the **private message** please advise the pilot on frequency to expect a route change via **private message**.

You can use tools such as SimBrief to provide pilots with valid routings. **Khaleej vACC** actively ensures routes are updated in SimBrief for pilots to use. 

### 2.1.3 Filed Flight Levels 
**Kuwait Delivery (DLV)** must ensure pilots are filing correct flight levels in accordance with their filed routings. If Pilots have incorrectly filed flight levels in their flight plan you must inform the pilot to refile their flight plan via **private message**. 

Kuwait utilises the Semi-Circular Rule. Flights flying Westbound should file **Even** levels and flights flying Eastbound should file **Odd** levels. 

### 2.1.4 Flight Level Capping 
Multiple destinations across the Gulf Region have level capped routings due to operational reasons. The DLV Controller shall ensure adherence to the below table, it is the responsibility of the DLV Controller to ensure aircraft have filed a correct level in the their flight plan prior to issuing a clearance. If an incorrect level has been filed the DLV Controller shall inform the pilot that they are required to file a revised flight plan with the new level in accordance with the below table for level capped routings. 

| **Destination** | **Max Altitude / Flight Level** |
|:---------------:|:-------------------------------:|
|       ORMM      |              FL160              |
|       OEDF      |              FL250              |
|       OBBI      |              FL270              |
|       OTHH      |              FL330              |

### 2.1.5 Flow Restrictions

#### 2.1.5.1 Target Off Block Time (TOBT)
When A-CDM procedures are active (typically during busy events), pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controllers client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is cancelled, and a new TOBT is assigned.

Please note TOBTs are only issued during certain events, this will outlined to via Khaleej vACC Staff if TOBT procedures are to be implemented for that particular event.

## 2.2 Departure Procedures
In Kuwait all departures should be cleared via a **Standard Instrument Departure (SID)** which is selected based on the first waypoint in their filed Flight Plan (FPL). 
All **Standard Instrument Departures (SIDs)** in Kuwait are RNAV (Area Navigation) and provide aircraft with a pre-defined route taking them from the departure airport into the **Control Area (CTA)** where they will be taken into the en-route environment. 

| **Runway** | **Identifier** | **Initial Altitude** |
|:----------:|:--------------:|:--------------------:|
|   33L/33R  |     ALVAX4F    |        4000ft        |
|   33L/33R  |     ASVIR4F    |        4000ft        |
|   33L/33R  |     BOXIK4F    |        4000ft        |
|   33L/33R  |      KFR4F     |        4000ft        |
|   33L/33R  |     RALKA4F    |        4000ft        |
|   33L/33R  |     SESRU4F    |        4000ft        |

| **Runway** | **Identifier** | **Initial Altitude** |
|:----------:|:--------------:|:--------------------:|
|   15L/15R  |     ALVAX4E    |        4000ft        |
|   15L/15R  |     ASVIR4E    |        4000ft        |
|   15L/15R  |     BOXIK4E    |        4000ft        |
|   15L/15R  |      KFR4E     |        4000ft        |
|   15L/15R  |     RALKA4E    |        4000ft        |
|   15L/15R  |     SESRU4E    |        4000ft        |

!!!node "Identifiers" 
    Note, all SIDs from the 33s end in 4F and all the SIDs from the 15s end in 4E.

## 2.3 VFR Procedures 
DLV is responsible for issuing VFR Clearances as well. Prior to issuing a VFR Clearance to any traffic, DLV must coordinate with TWR to ensure the TWR controller can accept local traffic into his CTR. TWR has the authority to delay traffic into his CTR if the traffic load is high. The TWR Controller must provide a estimated delay time to the DLV Controller to pass to the pilot. 

### 2.3.1 VFR Circuits
Once **Kuwait Delivery (DLV)** has recieved confirmation from the TWR controller that they are happy to accept **VFR Circuit Traffic** they can continue with issuing a VFR clearance to the aircraft. Please see below the standard pattern information below.

!!!node "Act Promptly"
    When you see a pilot file a VFR FPL ensure you act promptly and efficently and coordinate with the relevant controller to ensure they are able to accept the aircraft into their airspace. Do not wait for the pilot to call up on frequency before coordinating with the relevant ATS Unit. 

| **Runway Configuration** | **Direction** | **Altitude** |
|:------------------------:|:-------------:|:------------:|
|            33R           |   Right Hand  |    1000ft    |
|            15R           |   Right Hand  |    1000ft    |
|            33L           |   Left Hand   |    1000ft    |
|            15L           |   Left Hand   |    1000ft    | 

!!!node "Circuit Selection for Runway"
    The TWR Controller will advise the DLV Controller which runway the circuits will be conducted on, standard is 15L/33R. 

***VFR Circuit Clearance Example***

> **DLV Controller:** _**"9K-VFR, cleared right hand visual circuits, RWY33R, not above altitude 1000ft, VFR, squawk 7001"**_

The DLV Controller **must** obtain a full and correct read back of the departure clearance. If they do not, then the pilot must be challenged to read back the full and correct departure clearance. 

***Challenge Example***

> **DLV Controller:** _**"9K-VFR, Negative. Cleared right hand visual circuits, RWY33R, not above altitude 1000ft, VFR, squawk 7001"**_

!!!node "Be Paitent and Assist"
    If you are required to challenge a pilot for a correct readback, readback it back clearly and slowly to ensure the pilot has opportunity to understand the information provided

Once the pilot has correctly read back the clearance, if the pilot did not provide the current ATIS Letter, the DLV Controller will provide this to the pilot once read back has been provided. 

> **DLV Controller:** _**"9-FR, read back correct, Information Alpha is current, report ready for startup."**_

When the pilot requests startup, ensure he has set the correct transponder code. If he is squawking the assigned code, switch them to GND or any facility higher. 

> **DLV Controller:** _**"9-FR, hold position, contact Kuwait Ground 121.700."**_


!!!node "Callsign Shortening" 
    After initial contact has been made and established with the aircraft, you can shorten the callsign from 9K-VFR to 9-FR, read as Niner - Foxtrot - Romeo. This is to reduce frequency congestion.

### 2.3.2 VFR Departures Leaving the Control Zone (CTR)
For pilots filing VFR Flight Plans (FPLs) to leave the **Kuwait Control Zone (CTR)**, again the DLV Controller must coordinate this promptly with the TWR Controller, who will coordinate with the APP Controller as to whether they can both accept the aircraft in their respective airspace. The TWR Controller will be responsible for providing the DLV Controller with a **Visual Reporting Point (VRP)** to be cleared via depending on the aircrafts filed routing or direction of flight. Once approved, the **DLV Controller** will issue a clearance to the aircraft. 

#### 2.3.2.1 VFR Departure Routes Procedures 

| **Runway** | **Identifier** | **Direction of Flight** |                                                                                                       **Procedure**                                                                                                       |
|:----------:|:--------------:|:-----------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| RWY15L/15R |   VFR Q East   |           East          |                          Pilot should climb to 1000ft on runway heading, when passing the departure end of runway (DER) pilots shall turn left towards Qurain Shopping Area and report overhead.                          |
| RWY15L/15R |   VFR G West   |           West          | Pilots should climb to 1000ft on runway heading, when passing the departure end of runway (DER) pilots shall turn right towards Petrol Station located on the 7th Ring Road beside the drag circuit and report overhead.  |
| RWY33L/33R |   VFR F East   |           East          |                          Pilots should climb to 1000ft on runway heading, when passing the departure end of runway (DER) pilots shall turn right towards Mishrif Fairground on report overhead.                           |
| RWY33L/33R |   VFR U West   |           West          |                        Pilots should climb to 1000ft on runway heading, when passing the departure end of runway (DER) pilots shall turn left towards Alshedadiya University and report overhead.                         |


***VFR Zone Exit Clearance Example***

> **DLV Controller:** _**"9K-VFR, You are cleared to exit the Control Zone to the East, via Quebec East, RWY15L, not above altitude 1000ft VFR, Squawk 7001"**_

The DLV Controller **must** obtain a full and correct read back of the departure clearance. If they do not, then the pilot must be challenged to read back the full and correct departure clearance. 

***Challenge Example***

> **DLV Controller:** _**"9K-VFR, Negative. You are cleared to exit the Control Zone to the East, via Quebec East, RWY15L, not above altitude 1000ft VFR, Squawk 7001"**_

!!!node "Visual Reporting Points (VRPs)" 
    The TWR Controller will issue the DLV Controller with a VRP for the aircraft to leave the Control Zone via

Once the pilot has correctly read back the clearance, if the pilot did not provide the Current ATIS Letter and/or QNH on initial contact, the DLV Controller will provide this to the pilot once read back has been provided. 

> **DLV Controller:** _**"9-FR, Read Back is correct, Information Alpha is current, QNH 1001"**_

When the aircraft reports ready for engine start up they will be transferred to the GMC Controller and it is to be assumed by the GMC Controller that the pilot has a **correct clearance and has confirmed the latest ATIS Letter and Local QNH.**

## 2.4 Departure List Management 
The **DLV Controller** is responsible for ensuring the departure list is correct and maintained prior to handing aircraft off to the GMC Controller. This includes ensuring filed routings are correct, Standard Instrument Departures (SIDs) have been assigned, initial altitudes has been set correctly and a squawk code has been assigned. 

The A/C Status Column must be updated to show the aircraft is on frequency. 

### 2.4.1 Squawk Code Not Set 
If an aircraft who has received his clearance and calls ready for push and start but has not set their assigned squawk code the **DLV Controller** must advise the aircraft to set squawk code. Aircraft will not be handed off to GMC for push back until the squawk code has been set. 

## 2.5 Transferring Aircraft to the GMC Controller
When an aircraft has received his clearance and calls for push and start with his assigned squawk code set the **DLV Controller** will then hand the aircraft off to the **GMC Controller** to be sequenced for push and start. 

> **DLV Controller:** _**"KAC107, hold position, Contact Kuwait Ground on 121.700"**_
