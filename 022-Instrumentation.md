# 022 Instrumentation

## 01 - Sensors and Instruments

### Pressure sensing systems

| Type | Pressure Range | Applications |
|--|--|--|
| Aneroid capsules | Low | Altimeter |
| Bellows | Medium | Pneumatic systems |
| Bourdon Tube | High | Hydraulic systems |

### Thrust measurement

- EPR (Engine Pressure Ratio = Exhaust pressure / Intake Pressure)
- N1 (RPM of low-pressure shaft)

### RPM measurement

- Mechanical/Magnetic: Magnet rotating
- Electrical: Generator feeding synchronous motor, turning a drap cup
- Electronic/Magnetic: Pulse measurement with hall sensor

### Temperature measurement

- Bimetallic strip: Up to 400 °C
- Temperature-dependent resistor: Up to 500 °C
- Thermocouples: Up to 2000 °C

## 02 - Measurement of Air Data Parameters

### Airspeed

- IAS
- CAS = IAS corrected for Instrument & Position error
- EAS = CAS corrected for compressibility
- TAS = EAS corrected for density

- M = TAS / LSS
- LSS = 38,95 x sqrt(T in Kelvin)

### AoA sensors

- Vane Sensor: Free-flowing vane
- Null-seeking (slotted) probe: Two slots, seeking pressure equvalence

Both use piezoelectric sensing and are prone to position error

### Altitude sensors

- Sensitive Altimeter: Using two aneroid capsules, and mechanical link to display
- Servo altimeter: Electric sensing to aneroid capsules (requires power, but less lag)

## 03 - Magnetism – Direct Reading Compass and Flux Valve

## 04 - Gyroscopic Instruments

## 05 - Inertial Navigation

## 06 - Aeroplane: Automatic Flight Control Systems

### Stabilization (Basic) Modes / Inner loop

Stabilizing the aircraft around its center of gravity

- Pitch angle hold
- Bank angle hold / Wings level
- Vertical Speed

### Guidance functions / Outer loop

Controlling the movement of the center of gravity in 3-dimensional space

- Vertical: IAS, ALT, VNAV (FPA), G/S, ...
- Lateral: HDG, LNAV (TRK), LOC, VOR, ...
- Mixed: T/O, G/A, APP

### Temporary override modes

- CWS: A/P stays engaged, control movements are sensed and applied by A/P system, new attitude is kept
- TCS: A/P is disengaged while button is pressed, A/C is flown manually, after release of button former A/P mode is re-engaged

### Autopilot phases

- Initial: Attitude change to obtain a new trajectory
- Capture: Predefined rate of change to capture the desired parameter without over-/undershoot
- Tracking/Hold: The set parameter will be maintained

### Autoland operation modes

- Fail-operational: If one A/P fails, the remaining A/P can perform the autoland (approach, flare, landing) as a fail-passive system
- Fail-operational hybrid: Fail-passive A/P with secondary independent guidance system
- Fail-passive: If the A/P fails, no significant out-of-trim condition occurs, but no autoland is possible

Order of A/P modes: LOC -> G/S -> FLARE -> RETARD -> TO/GA (Mnemonic: Let's go fly real touchdowns)

### Warning suppression for autoland

- Loss of one AP below alert height
- Loss of LOC < 15 ft
- Loss of G/S < 100 ft

## 08 - Trims – Yaw Damper – Flight Envelope Protection

### Mach Trim System

- Activated above a certain mach speed (Mcrit), at which the centre of pressure moves backwards on the wing, causing a pitch down moment
- Trims pitch up to counteract the mach tuck

### Pitch Trim System

- Conventional aircraft: When A/P is engaged
- Fly-by-Wire: Works in-flight, when airspeed is within certain limits
- Green band area for Take/Off settings

### Yaw Damper

- Particularly necessary with low directional stability (e.g. in high altitude and high speed flight)
- Activated when acceleration on the yaw axis
- Has a dutch roll filter to distinguish between turn yaw and dutch roll yaw
- Supports coordinated turns
- Moves the rudder without moving the pedals

### Flight envelope protection

- Uses stick shaker to announce critical flight attitudes
- Warns in case of overspeed or reaching stall speed

## 09 - Autothrust – Automatic Thrust Control System

### Modes

- Speed modes: SPEED, V/S
- Thrust modes: N1, EPR, THR IDLE, TOGA

### Autothrust by flight phase

- Ground, T/O, initial climb: N1 (constant thrust)
- Continued Climb with V/S, Cruise, Alt Hold and Approach: IAS (and optionally MACH in cruise)

## 10 - Communication Systems

### Datalink technologies

- HF
- VHF
- SATCOM/UHF (CPDLC via ACARS, a.k.a. FANS 1/A)
- FANS 2/B

CPDLC is for ATC only, ACARS is for AOC and ATC

At first, the capabilities have to be reported by AFN (Air Traffic Facilities Notification) LOGON

# ADS contracts (ADS-C)

- periodic
- on demand (of ATC)
- on event (Speed, Level, Waypoint change)

## 11 - Flight Management System (FMS)/Flight Management and Guidance System (FMGS)

### General

- FMS databases are updated, loaded and activated manually
- If a new DB becomes effective during flight, continue on the one current at start
- databases contain airport, route and NAVAID info

### Operating modes

- Dual (standard): Two FMGCs, synchronized via cross-talk
- Independent: Cross-talk fails, both act seperately
- Single: One FMGC fails, the other serves both MCDUs

## 12 - Alerting Systems, Proximity Systems

### Warning levels

- Advisory: Later action may be required
- Caution: Later action will be required
- Warning: Immediate action is required

### Procedure following a master warning/caution

- Acknowledge the failure
- Silence the alarm
- Apply the procedure
- Inform ATC

### Radio altimeter

- 4200 - 4400 MHz FM
- Two antennas, spaced to avoid interference

### Stall warning system (SWS)

- Uses thrust, flap and slat setting information
- Stall warning is created based on CAS, not AoA
- Margin is 5 kts or 5% CAS, whichever is greater

## 13 - Integrated Instruments – Electronic Displays

## 14 - Maintenance, Monitoring and Recording Systems

## 15 - Digital Circuits and Computers
