---
title: Bahrain Delivery [OBBI_DEL]
---

!!!node "Covering"
    This section details all the necessary and required Standard Operating Procedures for Delivery Operations at **Bahrain International Airport (OBBI)**

# 1. Bahrain Delivery
Bahrain Delivery (OBBI_DEL) is responsible for validating flight plans and issuing IFR/VFR clearances to departing aircraft. This includes thoroughly reviewing the filed route by the pilot, ensuring the correct altitude or flight level (FL) has been filed in accordance with their direction of flight and issuing the crew with a clearance in accordance with the departures procedures laid out at Bahrain International Airport (OBBI). In the event a pilot incorrectly files a flight plan (FPL) it will be the responsibility of the delivery controller to rectify the flight plan (FPL) in coordination with the pilot prior to allowing the aircraft to depart. 

# 2. Departure Clearance
## 2.1 General

DLV is responsible for issuing IFR/VFR clearances for departing aircraft. Pilots should be expected to report the following information on first contact with Bahrain Delivery.

 - Callsign
 - Aircraft Type
 - Stand Number
 - Current ATIS Information
 - Destination
### 2.2 IFR Clearances
An IFR clearance shall be provided by the delivery controller once it has been established the pilot has correctly filed a flight plan and requests clearance from the controller. The IFR clearance should contain the following:

- Callsign
- Destination
- Initial Airway and TMA Exit Waypoint 
- Initial Heading after Departure 
- Assigned SSR Code 
### 2.2.1 Phraseology 
In Bahrain, the standard BCAA phraseology is used for IFR clearances, the following phraseology **must strictly be adhered to**. 
> **Pilot:** _GFA173, Stand 19, Airbus A320, requesting IFR clearance to Jeddah_
>
> **DLV:** _GFA173, cleared to Dubai via N697 SODAK P559 NALPO, after departure right heading 345 degrees, radar vectors, initial climb 4000ft, squawk 4417_

> **Pilot:** _Cleared to Dubai via the N697 SODAK P559 NALPO, after departure turn right heading 345 degrees, radar vectors, initial climb 4000ft, squawk 4417, GFA173_

> **DLV:** _GFA173, readback correct, Information A, Report ready for push and start_

> **Pilot:** _Bahrain Delivery, GFA173, Stand 19, request push and start_

> **DLV:** _GFA173, hold position contact Bahrain Ground on 121.850_

!!!node "Responsible Controlling"
    DLV must recieve a complete and correct readback of the clearance from the pilot. If they do not the pilot must be challenged to ensure the clearance has been recieved correctly.

### 2.2.2 Datalink Clearance (DCL)  
Clearance for aircraft may also be provided via datalink (DCL), which helps reduce the workload of the controller in busy environments and reduces frequency congestion. This can only be used providing the pilot has the necessary systems fitted in their aircraft such as ACARS. Controllers must ensure that DCL is available for use at all times. 

!!!node "Rerouting is not approved via DCL"
    For pilots who file incorrect flightplans the controller shall revert to giving the pilot a voice clearance. This is due to limitations within the DCL/ACARS systems which prevents non standard messages.

### 2.2.3 Departure Procedures 
Bahrain does not have any published Standard Instrument Departures (SIDs). Instead, Delivery will assign an initial heading to departing aircraft Aircraft will then be provided radar vectors from Bahrain Approach after departure. 

| **Runway** | **TMA Exit Point** | **Initial Heading** |
|:----------:|:------------------:|:-------------------:|
|     30R    |        NARMI       |         300         |
|     30R    |        TULUB       |         345         |
|     30R    |        SODAK       |         345         |
|     30R    |        ASTAD       |         345         |
|     30R    |        LOTOR       |         345         |

| **Runway** | **TMA Exit Point** | **Initial Heading** |
|:----------:|:------------------:|:-------------------:|
|     12L    |        TULUB       |         120         |
|     12L    |        NARMI       |         075         |
|     12L    |        SODAK       |         075         |
|     12L    |        ASTAD       |         075         |
|     12L    |        LOTOR       |         075         |

!!!node "Initial Climb"
    The initial climb for aircraft departing Bahrain International Airport is **3000ft for propeller aircraft** and **4000ft for jet aircraft.** 

### 2.2.4 Rerouting Traffic 
The responsibility of ensuring that all aircraft have the accurate and realistic route lies with DLV. The DLV should utilise the RouteChecker tool for this purpose. 

If a pilot files an invalid route, they shall be informed by DLV of such as soon as they have connected to the network by private message or on frequency. 

### 2.2.4.1 Rerouting by Voice 
DLV may use the following phraseology to reroute traffic by voice.  

> **DLV:** _GFA179, Cleared to Hamad, ASTAD N318 LUBET, Flight planned route, after departure right heading 345 degrees, radar vectors, initial climb 4000ft, squawk 4010_

Althought this reroute can be conveyed over voice, it consumes time on frequency which maybe needed for other traffic. Therfore the preferred method of rerouting traffic is by Private Message. This allows any questions from the pilot to be answered without clogging the frequency. 

### 2.2.4.2 Rerouting by Private Message 
This is preferential method of rerouting aircraft. Refer to the Alias. 

### 2.2.5 Cruising Flight Level (CFL)
DLV must ensure all traffic are cleared on the appropiate CFL. 

Bahrain operates the Semi-Circular Rule which means aircraft flying Westbound will operate at Even Flight Levels and aircraft flying Eastbound will operate at Odd Flight Levels. 

### 2.2.5.1 Level Capped Routings 
Due to the crowded airspace in the Gulf Region and the short distance of various flights there are level capped routings within the region. 

| **Destination** | **Max Altitude / Flight Level** |
|:---------------:|:-------------------------------:|
|       OT**      |             11000ft             |
|       OM**      |              FL250              |
|       OKKK      |              FL260              |
|       OTDF      |              6000ft             |

### 2.2.6 Delay Mitigation
### 2.2.6.1 Target Off-Block Time (TOBT)
When A-CDM procedures are active (typically during busy events), pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controllers client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly. 

The TOBT system allows aircraft to push back, taxi to the runway holding point and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is cancelled, and a new TOBT is assigned. 

## 2.3 VFR Clearances
DLV is responsible for issuing VFR Clearances as well. Prior to issuing a VFR Clearance to any traffic, DLV must coordinate with TWR to ensure the TWR controller can accept local traffic into his CTR. TWR has the authority to refuse traffic if the traffic load is too high.

!!!node "Rare Occurence"
    It's not often you will have the pleasure of controlling VFR in Bahrain due to it's geographical location, however, it is the responsibility of the controller to ensure they're up to speed with the SOPs for dealing with VFR professionally and competently.

### 2.3.1 VFR Circuits

| **Runway Configuration** | **Direction** | **Altitude** |
|:------------------------:|:-------------:|:------------:|
|            30R           |   Right Hand  |    1000ft    |
|            12L           |   Left Hand   |    1000ft    |

!!!node "Jet Engine Aircraft"
    It must be noted, **Jet Engined Aircraft have a circuit altitude of 2000ft**

### 2.3.1.2 Phraseology
> **Pilot:** _Bahrain Delivery, A9C-ZZ type Cessna 172 with information A, Stand 85, requesting VFR circuits_

> **DLV:** _A9C-ZZ, cleared right hand circuits RWY30R, not above altitude 1,000ft VFR, squawk 6004_

> **Pilot:** _Cleared right hand circuits RWY30R, not above altitude 1,000ft VFR, squawk 6004, A9C-ZZ_

> **DLV:** _A9C-ZZ, readback is correct, information A is current advise when ready for engine start up_

### 2.3.2 VFR Departures Leaving the CTR
Not all VFR flights will want to remain in the Control Zone (CTR). In this instance, VFR aircraft can request clearance to a destination or to leave the control zone. Again, this must be coordinated with TWR and APP to ensure they can sufficently handle the traffic depending on traffic levels within both the Control Zone (CTR) and Terminal Maneuvering Area (TMA). It is best to do this prior to the aircraft has called you on frequency once you have reviewed their flight plan and analysed their intentions. Once you have recieved approval from adjacent control units you can go ahead with issuing a clearance. 

### 2.3.2.2 Phraseology 
> **Pilot:** _Bahrain Delivery, A9C-ZZ type Cessna 172 with information A, Stand 85, request clearance to leave the control zone to the West on track Al Khobar_

> **DLV:** _A9C-ZZ, you are cleared to exit the control zone to the West on track Al Khobar, not above altitude 6000ft, squawk 6001_

> **Pilot:** _Cleared to leave the control zone to the West on track Al Khobar, not above altitude 6000ft, squawk 6001, A9C-ZZ_

> **DLV:** _A9C-ZZ, readback correct, Information A is current, advise when ready for engine start up_

> **Pilot:** _A9C-ZZ, request engine start up_

> **DLV** _A9C-ZZ, contact Bahrain Ground on 121.850_