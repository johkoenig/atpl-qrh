# 090 Communications

## Contents

- [01 - Concepts](#01---concepts)
  - [Definitions](#definitions)
  - [Q-Codes for Bearings](#q-codes-for-bearings)
  - [Operating times](#operating-times)
- [02 - General Operating Procedures](#02---general-operating-procedures)
  - [Definitions](#definitions-1)
  - [Radio check / Readibility](#radio-check--readibility)
  - [Responses to traffic information:](#responses-to-traffic-information)
  - [Detailed holding instructions](#detailed-holding-instructions)
  - [SELCAL check calls](#selcal-check-calls)
- [03 - Relevant weather information](#03---relevant-weather-information)
  - [Automated weather observations via datalink](#automated-weather-observations-via-datalink)
  - [Automated Dependent Surveillance (ADS) variants:](#automated-dependent-surveillance-ads-variants)
- [04 - Voice Communication Failure](#04---voice-communication-failure)
  - [Continuance of speed and level](#continuance-of-speed-and-level)
  - [Light gun signals](#light-gun-signals)
  - [Lost Comm. IFR in VMC](#lost-comm-ifr-in-vmc)
  - [Other means of re-establishing a lost communication](#other-means-of-re-establishing-a-lost-communication)
- [05 - Distress and Urgency Procedures](#05---distress-and-urgency-procedures)
  - [Distress call](#distress-call)
  - [Message Priorities](#message-priorities)
  - [Discrete Frequency](#discrete-frequency)
  - [Other considerations](#other-considerations)
- [06 - VHF Propagation and Allocation of Frequencies](#06---vhf-propagation-and-allocation-of-frequencies)
  - [Frequency ranges](#frequency-ranges)
  - [Attenuation](#attenuation)
  - [Polarity](#polarity)
  - [Direct line-of-sight distance](#direct-line-of-sight-distance)
- [07 - Other communications](#07---other-communications)
  - [Runway conditions](#runway-conditions)
  - [Air Reports](#air-reports)

## 01 - Concepts

### Definitions

- **EAT**: Estimated Approach time, i.e. time when the aircraft is leaving the fix for the approach
- **Final**: 4 NM
- **Long Final**: 8 NM

### Q-Codes for Bearings

|  |  TO | FROM (Radial) |
|:--:|:--:|:--:|
| True (T) | QUJ | QTE |
| Magnetic (M) | QDM | QDR |

### Operating times

- HJ: Daytime (Surise to sunset)
- HN: Nighttime (Sunset to sunrise)
- HX: No specific hours
- HS: When scheduled operations take place
- H24: continous day and night (24/7)

## 02 - General Operating Procedures

### Definitions

- **MSAW**: Minimum safe altitude warning

### Radio check / Readibility

#### Call

- Name of the station adressed
- Own callsign
- "Radio Check"
- Frequency

#### Levels

| No. | Description |
|:--:|--|
| 1 | Unreadable |
| 2 | Readable now an then |
| 3 | Readable but with difficulty |
| 4 | Readable |
| 5 | Perfectly readable |

### Responses to traffic information:

- Positive: "Traffic in Sight"
- Negative: "Looking out" or "Negative contact" (with optional "request vectors")

### Detailed holding instructions

FLIRT:

- **F**ix
- **L**evel
- **I**nbound track
- **R**ight/Left
- **T**ime per leg

### SELCAL check calls

- "Request SELCAL check"
- "SELCAL ok"

## 03 - Relevant weather information

### Automated weather observations via datalink

- Every 30 sec in the first 10 minutes of flight during climb-out
- Every 15 mins thereafter

### Automated Dependent Surveillance (ADS) variants:

- **B**: Broadcast
- **C**: Contract

## 04 - Voice Communication Failure

### Continuance of speed and level

- No Radar: 20 mins
- Radar: Also 20 mins acc. EASA (used to be 7 mins)
- Vectored: Next significant point, in most direct manner possible

### Light gun signals

|  | Air | Ground |
|--|--|--|
| Steady Green | Cleared to land | Cleared for take-off |
| Flashing green | Return for landing | Cleared for taxi |
| Flashing white | Land & Proceed to Apron | Return to starting point |
| Steady red | Give way to other aircraft | Stop |
| Flashing red | Airport unsafe, do not land | Clear active runway |

### Lost Comm. IFR in VMC

- Stay VMC
- Land at next suitable aerodrome
- Report to ATC in the most direct manner

### Other means of re-establishing a lost communication

- Other aircraft
- Previous frequency
- Alternate frequency
- Other aeronautical stations

## 05 - Distress and Urgency Procedures

### Distress call

- MAYDAY (3x)
- Station adressed
- Your callsign
- Nature of emergency
- Pilot's intentions
- Present position, altitude/FL, heading

### Message Priorities

| Priority | Type | Code | Description |
|:--:|--|:--:|--|
| 1 | Distress (MAYDAY) | SS | Immediate assistance necessary |
| 2 | Urgency (PAN PAN) | DD | "MEDICAL" only for medical flighs, not medical emergencies |
| 3 | Direction Finding | ?? | |
| 4 | Flight Safety | FF | |
| 5 | Meteorological | GG | |
| 6 | Flight Regularity | KK | |

### Discrete Frequency

| User | In the air | On the groud |
|--|:--:|:--:|
| Aircraft in distress | x | x |
| ATC | x | x |
| Officer of emergency ops | x | x |
| Everybody involved | | x |
| Firefighting | | x |

### Other considerations

- Use current frequency
- MAYDAY means all others have to stop transmitting, unless:
  - situation is resolved
  - emergency is transferred to discrete frequency
  - it is absolutely necessary and the distress communication isn't disturbed
- PAN PAN means you should not interfere
- If nobody is answering, acknowledge and relay
- Operator must be informed about PAN PAN / MAYDAY

## 06 - VHF Propagation and Allocation of Frequencies

### Frequency ranges

#### General

- NAV: 108 - 117.975 MHz
- COM: 118 - 136.975/992 MHz

Both are VHF, Wavelength is ~ 5 m 

#### Special

- Emergency: 121.5 MHz (Protected 121.475 - 121.525 or 121.495 - 121.505)
- Ground: 121.550 - 121.9917 MHz

### Attenuation

Attenuation is increased by:

- Increased air density (=reduced temperature)
- Increased frequency (= reduced wavelength)

### Polarity

- Orientation of the antenna
- Receiver and Transmitter should have same polarity (i.e. both horizontal or both vertical)

### Direct line-of-sight distance

Double distance requires 4x transmission power

$$
D = 1.23 \cdot \left( \sqrt{h_1} + \sqrt{h_2} \right)
$$

- Distance D in nautical miles (nm)
- Heights h in feet (ft)

## 07 - Other communications

### Runway conditions

| Description | Gradient |
|--|--|
| Good | > 0,4 |
| Good/Medium | 0.39 - 0.36 |
| Medium | 0.30 - 0.35 |
| Medium/Poor | 0.26 - 0.29 |
| Poor | < 0.25 |
| Unreliable | Not measureable |

### Air Reports

#### Regular Air Reports

- Via Datalink
- No report if no datalink
- If special air report has been made, omit regular

#### Reasons for Special Air Reports

- Volcanic ash or pre-eruption
- MOD/SEV TURB or mountain wave
- MOD/SEV Icing
- TS, other than isolated (e.g. embedded, squall lines)

