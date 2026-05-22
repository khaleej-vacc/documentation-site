---
title: Flow Management
---

# Airport Collaborative Decision Making (A-CDM)

Airport Collaborative Decision Making (A-CDM) is implemented within Khaleej vACC to improve departure predictability, reduce apron congestion, and support efficient traffic flow during both normal and high-density operations.

The system is designed to:

- Improve controller situational awareness
- Reduce unnecessary frequency congestion
- Support structured departure sequencing
- Improve realism during major events
- Prevent excessive taxiway saturation
- Ensure equitable startup allocation

---

## When Should A-CDM Be Used?

A-CDM procedures should normally be considered active when:

- Departure demand exceeds practical aerodrome capacity
- Major events are in progress
- Hajj or Umrah operations are active
- Significant outbound congestion is expected
- CTOT restrictions are in effect
- Controller workload requires structured sequencing

During low traffic periods, controllers may apply A-CDM procedures flexibly and pragmatically.

---

## Definitions

### Estimated Off-Block Time (EOBT)

General estimate as to when an aircraft will be ready to start-up or push-back.

!!! note
    EOBT is normally static and does not dynamically adjust to operational conditions.

---

### Target Off-Block Time (TOBT)

The time aircraft operators estimate that the aircraft will be fully ready for immediate startup or pushback.

This includes:

- Boarding complete
- Doors closed
- Boarding bridge removed
- Push vehicle connected and ready
- Aircraft prepared for immediate movement

---

### Target Start-Up Approval Time (TSAT)

Calculated time at which start-up approval can reasonably be expected.

TSAT considers multiple operational factors, including:

- Departure demand
- Taxi congestion
- Runway capacity
- CTOT restrictions
- Variable taxi times
- Apron saturation

!!! note "Important"
    Pilots **DO** know their **EOBT and TOBT**, however pilots **DO NOT** know their assigned **TSAT** unless advised by ATC.

---

## Controller Responsibilities

### Clearance Delivery (DEL)

DEL controllers are responsible for:

- Managing TOBT compliance
- Issuing TSAT information
- Sequencing startup requests
- Monitoring delayed or non-responsive aircraft
- Coordinating CTOT restrictions
- Maintaining orderly startup flow

---

### Ground (GND)

Ground controllers are responsible for:

- Maintaining efficient apron flow
- Preventing taxiway congestion
- Sequencing pushbacks strategically
- Coordinating apron conflicts
- Managing stand blockage issues
- Supporting departure flow continuity

---

### Tower (TWR)

Tower controllers are responsible for:

- Optimising runway throughput
- Maintaining departure spacing
- Coordinating arrival and departure balance
- Supporting continuous movement flow
- Applying wake turbulence efficiency

---

## Using CDM

<p style="text-align: center; font-style: italic;">
Figure 1.1
</p>

![panel](img/panel.png)

- Locate the following panel and click on the respective airport to enable CDM as a master user.

<p style="text-align: center; font-style: italic;">
Figure 1.2
</p>

![SUL](img/SUL.png)

- Expand your Start-Up list; it will appear as shown above.
- If the list is not visible, open it via **Quick Settings**.
- When CDM is active, pilots are expected to submit their TOBT via the [VDGS Dashboard](https://vats.im/vdgs).
- TSAT is automatically generated using operational conditions affecting aerodrome efficiency.

Controllers should provide TSAT information using the following phraseology:

> DLV Controller:  
> “GFA138, readback correct. Expect push at time 0830z.”

---

## Startup Sequencing Philosophy

Controllers should prioritise overall traffic flow efficiency rather than first-call priority alone.

Operational considerations may include:

- Taxiway congestion
- Stand blockage
- Departure direction
- CTOT restrictions
- Runway throughput
- Apron saturation

During periods of high demand, startups may be released in controlled batches to reduce congestion and improve taxi flow.

---

## Operational Techniques

### Startup Batching

During periods of high traffic demand, startups may be released in controlled groups to reduce apron congestion and excessive taxi delays.

---

### Directional Sequencing

Aircraft may be grouped by SID direction or runway exit point to improve runway efficiency and reduce crossing conflicts.

---

### Congestion Control

Ground controllers may temporarily suspend pushback approvals when taxiway saturation becomes excessive.

---

### Stand Protection

Aircraft occupying operationally critical stands may receive priority startup approval where operationally necessary.

---

!!! warning "CDM Management Responsibility"
    Only DEL, or FMP/Planner if online, should operate CDM as a master user.

    All other controllers should use:

    `.cdm slave [ICAO]`

    This ensures startup sequencing remains coordinated and predictable.

---

# Common Controller Errors

The following issues commonly reduce operational efficiency during high-density operations:

- Issuing startup too early
- Excessive simultaneous pushbacks
- Overloading taxiways
- Forgetting missed TSAT resequencing
- Poor DEL/GND coordination
- Prioritising first-call over traffic flow
- Ignoring stand blockage impacts

---

## Example Scenarios

### Missed TSAT

Aircraft reports ready after assigned TSAT.

Recommended controller actions:

- Remove aircraft from original sequence
- Recalculate startup opportunity
- Issue revised TSAT
- Resequence according to current demand

---

### Apron Saturation

Taxiways approaching practical capacity.

Recommended controller actions:

- Suspend additional push approvals
- Release aircraft in controlled batches
- Prioritise blocked stands where practical
- Coordinate holding areas proactively

---

# Arrival Manager (AMAN)

The Arrival Manager (AMAN) is a tactical sequencing aid controllers and flow managers may utilise during periods of increased arrival demand.

!!! note "Controllers remain responsible"
    AMAN exists to support controller decision-making and sequencing awareness.

    It shall not be relied upon as a replacement for controller judgement.

<p align="center">
  <strong>2.1 - EXAMPLE OF AMAN USAGE</strong><br>
</p>

![aman](img/aman.png#center)

---

# Key Principles

- Predictability over speed
- Flow over individual priority
- Prevention over recovery
- Structured sequencing reduces workload
- Efficient ground movement improves runway throughput
- Early coordination prevents saturation
