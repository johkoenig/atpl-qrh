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

### Autoland failure modes

- Fail-operational: If one A/P fails, the remaining A/P can perform the autoland (approach, flare, landing) as a fail-passive system
- Fail-passive: If the A/P fails, no significant out-of-trim condition occurs, but no autoland is possible

## 08 - Trims – Yaw Damper – Flight Envelope Protection

## 09 - Autothrust – Automatic Thrust Control System

## 10 - Communication Systems

## 11 - Flight Management System (FMS)/Flight Management and Guidance System (FMGS)

## 12 - Alerting Systems, Proximity Systems

## 13 - Integrated Instruments – Electronic Displays

## 14 - Maintenance, Monitoring and Recording Systems

## 15 - Digital Circuits and Computers
