# 062 Radio Navigation

## 01 Basic Principles

### Keying

| Type | Description | Used for |
|:--:|--|--|
N0N  | No Modulation, just carrier wave | Old NDB |
A1A | Morse code Modulation | Old NDB/BFO to ID |
A2A | Amplitude Modulated Morse code | New NDBs/ADF |
A3E | Amplitude Modulated Speech | VHF Voice and VORs |

### Modulations

- Amplitude Modulation: Carrier waves amplitude increases/decreases
- Frequency Modulation: Carrier waves frequency increases/decreases
- Phase Modulation: Carrier waves frequency is reversed

### Antennas

- Directional (Mnemomic: Pilots hate landing sideways)
  - Parabolic
  - Helical (sometimes)
  - Loop
  - Slotted Array
- Omnidirectional
  - Dipole
  - Monopole
  - Quadrupole
  - Sense Antenna
 
### Single/Double Sideband

In single sideband, half of the signal is cut off to reduce the necessary transmitting power. HF-COM uses SSB, VHF-COM uses DSB

### Layers of the ionosphere

| Layer | Height | Occurence | Effect |
|:--:|:--:|--|--|
| D | 50 - 90 km | Daytime | Absorbs HF and lower |
| E | 90 - 120 km | Day & night | Reflects HF and MF |
| F1 | 120 - 200 km | Daytime | Reflects higher HF freq |
| F2 | 200 - 400 km | Day & night | Reflects HF |

As a consequence, the frequencies propagate as follows:

| Freqency range | Daytime prop. | Nighttime prop. |
|:--:|--|--|
| VLF | Ground + Sky wave | Ground + Sky wave |
| LF | Ground | Ground + Sky wave |
| MF | Ground | Ground + Sky wave | 
| HF | Ground + Sky wave | Ground + Sky wave |
| Above | Space wave | Space Wave |

## 02 Radio Aids

### NDB

- 190 - 1750 kHz (LF, HF)
- Range 10 - 25 nm
- Variance/Deviation at aircraft position must be applied
- Acc. +- 5%

### NDB distubances

- Thunderstorm
- Coastal effect (at acute angle 0-30°, at night, with station far from coast)
- Dip error
- Quadrantal error
- Mountain effect (diffraction)

### Beat frequency oszillator (BFO)

- To listen N0N A1A
- Often automatically activated
- AFD is erratic when ID'd via BFO
- A2A NDBs can be identified on ADF mode

### VHF DF classes

- Class A: +- 2°
- Class B: +- 5°
- Class C: +- 10°
- Class D: > 10°

### VOR and ILS 

- General: 108 - 117.975
- ILS on 108 - 111.95 with odd decimal and odd decimal +50 (e.g. 111.1, 109.75)
- Variance and deviation at VOR position must be applied

### ILS types

- Type A is with DH >= 250 ft
- Type B with less DH, see table

| Cat | DH | Min RVR | Guidance |
|--|--|--|--|
| Cat. I | >= 200 ft | 550 m | 100 ft |
| Cat. II | >= 100 ft | 300 m | 50 ft |
| Cat IIIa | <= 100 ft | 175 m | 0 ft |
| Cat IIIb | <= 50 ft | 50-175 m | 0 ft |
| Cat IIIc | 0 ft | 0 m | 0 ft |

### ILS lobes

- 90 Hz lobe is left / up
- 150 Hz lobe is right / down
- Perfectly aligned means no DDM (difference in depth of modulation)

### Markes

| Marker | Distance | Color | Morse code | Tone |
|--|--|--|--|--|
| Outer | 4 nm | Blue | -- | 400 Hz |
| Middle | 1050 m | Amber | -.-.-. | 1300 Hz |
| inner | 75 - 450 m | White | ...... | 3000 Hz |

### Backcourse ILS

- Noe glide path
- LOC reversed on CDI
- LOC normal on HSI if front-course is selected

### Deflection

- LOC: Full-scale +- 10°
- ILS: Full scale +- 2.5°
- GP: Full scale +- 0.7°

### ILS Coverage

| Signal | Horizontal | Vertical |
|--|--|--|
| LOC | 10° for 25 nm and 35° for 10 nm | 7° above |
| GS | 8° for 10 nm | 0.45 - 1.75 x GS-angle |

### ILS disturbances

- Side lobes (for GS only above)
- Multipath reflection from objects within coverage area
- Scalloping

### ILS areas on ground

- ILS coverage area: Objets here may cause multipath reflections
- ILS sensitive area: Controlled, needs to be free for Cat. II/III
- ILS critical area: Must be always free for any ILS operation

### DME

- Frequency: 960 - 1125 MHz (252 channels, UHF)
- Response on freq. +- 63 MHz
- Interrogator on aircraft
- Transponder on ground

### DME modes

- Search (more pulse pairs until locked)
- Track (normal operation mode)
- Memory (in case of signal loss up to 10 secs)

### MLS

- Frequency: 5031 - 5090 Mhz (200 channels, 300 kHz spacing, SHF)
- Range 40° over 20 nm
- used where ILS can't be used due to buildings or terrain
- For curved & segmented approaches, must be paired with DME-P

### Usage

- Select channel number
- Select glideslope angle (can be different for diff. aircraft)

## 03 Radar

### General

- works using pulses
- Min. range defined by pulse length: MinR = 300 000 x PL / 2
- Max. range defined by pulse repetition frequency: MaxR = 300 000 / (PRF x2)
- Double eff. range = 16x stronger signal (power of 3 = 3D)

### Radar applications

- Primary surveillance radar (PSR)
- Secondary surveillance radar (SSR) - only one not relying on echos, therefore higher range and no disturbances
- Airborne weather radar (AWR)
- Aerodrome surveillance radar (ASR, ground or approach)

### Airborne weather radar

- SHF signal ~ 9 GHz (wavelength 3 cm)
- Used slotted planar antenna (less side lobes, less groupd clutter)
- Cosecant or pencil beam, newer systems have pencil beam
- Returns are based on reflectivity of precipitation (hail, rain)
- Turbulence detection by doppler shift

### Stabilization of AWR

- Stabilization for pitch and roll angle
- Auto-tilt: Adjust tilt by altitude
- Auto-stabilization: Adjust tilt by attitude

### PSR details

- Ground clutter can be removed by MTI (Mofing target indicator)

### SSR details

- On freq. 1030 Mhz (interrogation) and 1090 Mhz (response)
- Response every 15 sec (for first 10 mins), then every 15 mins

| Mode | content | alt. precision | pulse type |
|--|--|--|--|
| A | 4-digit code | none | 
| C | altitude | 100 ft | 
| S | datalink | 25 ft | longer P4 pulse |

### GNSS details

- Actually not good enougth for aviation, therefore augmented by GBAS (LAAS) or SBAS (WAAS)
- Various systems (GLONASS, GPS) are interoperable to provide more accurate position
- 30 sattelites for Galileo, 24 sattelites for GPS

### NAVSTAR GPS

| channel | freqency | service | codes and users |
|--|--|--|--|
| L1 | 1575 MHz | SPS (standard pos. serv.) | C/A for civ. and P for mil. |
| L2 | 1227 MHz | PPS (prec. pos. serv.) |P for mil. |

Using both signals (mil. only) allows elimination of ionospheric propagation delay

### RAIM levels (Receiver autonomous integrity monitoring)

- 4 sattelites: unable to detect faulty signal
- 5 sattelites: able to detect faulty, unable to identify (FD = fault detection)
- 6 sattelites: able to detect and identify faulty (FDE = fault detection and exclusion)

### Augmentation systems

- ABAS: with extra data from aircraft
  - RAIM: GPS receiver integrity
  - AAIM: Integrity over all aircraft sensors (GPS + IRS & baro)
- GBAS: with extra data from ground (e.g. LAAS)
  - Coverage: 35° to 15 mn, 10° to 20 nm (little bit less than ILS LOC)
  - Ground station measures satellite error and deliveres it to aircraft via VHF datalink (integrity info + approach data)
- SBAS: with extra data from sattelites, e.g. WAAS (USA), EGNOS (Europe), GAGAN (India), MSAS (Japan)
  - usage of multiple extra geostationary sattelites + ground stations (communicating with sattelites)
  - Improved integrity, failure detection goes down to 6 secs

### Segments of the NAVSTAR GPS

- Space (24 sattelites transmitting one-way)
- Control (Worldwide operator stations)
- User (Receiver)

### Contents of navigation message of the NAVSTAR/GPS

- Sattelite clock correction parameters
- UTC parameters
- Ionospheric model
- Sattelite health data

### Errors of NAVSTAR GPS

User-equivalent range error (UERE) includes all errors except of geometric(!) DOP

- Ionospheric errors
- Sattelite clock errors
- Ephemeris data error (satellite at wrong position)
- Multiplath errors
- Receiver quality
- Dilution of Precision (DOP) - sattelites aligned on shallow angles

## 06 Global Navigation Satellite Systems (GNSSs)
## 07 Performance Based Navigation (PBN)
