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

TAS = CAS + (CAS/600 * Alt(FL))

### AoA sensors

- Vane Sensor: Free-flowing vane
- Null-seeking (slotted) probe: Two slots, seeking pressure equvalence

Both use piezoelectric sensing and are prone to position error

### Altitude sensors

- Sensitive Altimeter: Using two aneroid capsules, and mechanical link to display
- Servo altimeter: Electric sensing to aneroid capsules (requires power, but less lag)

### ADIRU

- ADC: Air data computer, can be restarted in-flight
- IRU: Inertial reference unit, needs alignment on ground

### Mach Speed

- M = TAS / LSS
- M = sqrt(p_dyn / p_stat)
- LSS = 38.95 * sqrt(T in K)

### Temperatures

- TAT = SAT * (1 + 0.2 * M^2)
- SAT = TAT / (1 + K * 0.2 * M^2)

Recovery factor "K" is only applied in one direction as the real-world calculation with the actual instrument.

## 03 - Magnetism – Direct Reading Compass and Flux Valve

### Direct reading compass error

Amount of over-/understeer (Bank + Lat/2), depending on hemisphere:
- Northern: ANDS and UNOS
- Southern: SAND and ONUS

Max allowed error with runway aligned: +-10°

### Magnetism

- Hard iron: Permanent, i.e. determined by measurement, compensated by deviation
- Soft iron: Temporary, i.e. induced by earths magentic field

### Compass correction

- Compass swing: Amount of deviation due to aircraft
- Compass calibration: Reading residual deviation, noting on card
- Compass compensation: Correction of the deviation

### Gyromagnetic compass

- Combination of gyro and magentic compass
- FEAT: Flux Valve -> Error detection -> Amplifier -> Torque Motor
- Slaved/Free: Gyro is (not) connected to a flux valve

## 04 - Gyroscopic Instruments

### Gyro spin errors

- Vertical axis: Only topple
- Horizontal axis: Drift and topple

### Air-driven attitude indicator errors

- Roll error (pendulus error)
- Pitch error (erection error)

On acceleration, the ADAI moves up + right

### Standard turn

- Rate-of-turn = Bank angle / TAS
- 3° per second

### ADI (Attitude display indicator)

- AI: Attitude indicator
- FDI: Flight director indicator (GS, LOC, VOR)

### Skid and Slip

- Slip: Overbank (Ball & turn same)
- Skid: Underbank (Ball & turn opposite)

### Gyro error

- Real wander: Wander of the gyro axis (e.g. mechanical failure)
- Transport wander: Change in orientation in space (flying A->B)
- Apparent wander: wander of the earth system
- Gimbal error: In turns, due to tue errection system

Apparent wander rate for free gyro: 15°/h * sin(lat)

### Axis & degrees of freedom

- Turn coordinator: 1x, vertical
- Attitude indicator: 2x, vertical
- Dyn. Gyro: 2x, horizontal

### AHRS (Attitude & Heading Reference System)

- Accelerometers
- Gyroscopes
- Magnetometers

## 05 - Inertial Navigation

### General Systems

| System | Age | Technology | Alignment | Components | Alignment time |
|--|--|--|--|--|--|
| INS | older | mechanical | True north + horizontal | 3 Gyros, 2 Accelerometers | 15 - 20 mins |
| IRS | newer | laser or fibre optic gyros | Fixed in aircraft | 3 Gyros, 3 Accelerometers | 10 mins |

The higher the Lat, the more time it takes to align. Impossible > 78° N/S

### Alignment of IRS

- Detect parity vector
- Detect earth inclination
- Rectify north
- Calculate latitude from rotation

### Finding drift of system at the end of the flight

- Final position difference / Operating time = NM/h
- Alternative: Ground speed by IRS/INS when parked

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

### ADS contracts (ADS-C)

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
- If one RA fails: New DH
- If two RAs fail: No GWPS

### Stall warning system (SWS)

- Uses thrust, flap and slat setting information
- Stall warning is created based on CAS, not AoA
- Margin is 5 kts or 5% CAS, whichever is greater

### TCAS

- Mode II uses XPDR Mode S datalink to coordinate RAs
- In high-density areas, range is reduced
- Up to 30 aircraft
- Vertical commands only
- Bearing by directional antennas
- Distance by signal time measurement
- Other aircraft XPDR Mode A: TA only
- Other aircraft XPDR Mode C: TA + RA
- Other aircraft XPDR Mode S: TA + coordinated RA

### GPWS Modes

| Mode	| Meaning |	Initial Aural Alert	 | Second Aural Warning |
|--|--|--|--|
| Mode 1 | Excessive descent rate | SINK RATE, SINK RATE | WHOOP WHOOP PULL UP 
| Mode 2 | 	Excessive terrain closure rate (=dangerous ground proximity) | TERRAIN TERRAIN | WHOOP WHOOP PULL UP 
| Mode 3 | Altitude loss after take-off or go-around | "DON`T SINK" 	| NONE
| Mode 4a	| Unsafe Terrain Clearance with Landing Gear not Down | TOO LOW GEAR, TOO LOW TERRAIN	| NONE
| Mode 4b	| Unsafe Terrain Clearance with Flaps not in Landing Configuration | TOO LOW FLAPS or TOO LOW TERRAIN | NONE
| Mode 5	| Downward glideslope deviation | GLIDESLOPE, GLIDESLOPE at half volume | GLIDESLOPE, GLIDESLOPE at full volume
| Mode 6a | When passing the decision height | MINIMUMS, MINIMUMS	| NONE
| Mode 6b |	Excessive bank angle | BANK ANGLE, BANK ANGLE	| NONE
| Mode 7 | When expecting or already encountering wind shear | CAUTION WINDSHEAR | WINDSHEAR, WIDSHEAR

Mnemonic: **S**end **t**he **d**runk to **g**o to **France** to **g**et **m**y **b**est **w**ine

### TAWS / HTAWS

- Enhancing GPWS to EGPWS
- While GPWS just looks down (Radio alt.), the TAWS has a 3D terrain database
- Response time for caution: 40 - 60s
- Response time for warning: 20 - 30s

## 13 - Integrated Instruments – Electronic Displays

### EFB software types

- Type A: Malfunction has no effect on safety
- Type B: Malfunction may cause a minor failure condition

### Vision Systems

- Synthetic Vision System (SVS): Shows synthetic data from database in PFD
- Enhanced Vision System (EVS): Generates real-time imaginary on PFD from external sensors (Camera, IR)

### HUD components

- Colimated display
- Projector
- Computer

### ND Modes

- MAP or ARC: Symbol at bottom, Track Up, +-45° view
- VOR or ROSE/APP: Symbol at center, Heading Up, 360° view
- PLAN: True North Up

## 14 - Maintenance, Monitoring and Recording Systems

- FDR collecting flight data for investigation purposes
- CVR collecting flight crew deck audio data for investigation purposes
- FDM/ACMS collecting flight data for safety and training

## 15 - Digital Circuits and Computers

### Components of a computer

- Hardware: Everything physical
- Software: OS, programs, databases

### Bus types

- Internal: Connecting internal parts of a PC
- External: Connecting external components

### Busses 

- adress
- data
- control
