# 033 Flight Planning and Monitoring

## 01 - Flight Planning for VFR Flights

### Altimeter correction

From FL to true altitude
- Pressure correction: Reduce by 30 ft per 1 hPa below 1013 hPa
- Temperature correction: 4% for each 10 °C above ground (use pressure-corrected height!)

## 02 - Flight Planning for IFR Flights

### Minimum altitudes

- Obstacle clearance: 1000 ft AGL or 2000 ft AGL in mountaineous areas
- MOCA (Minimum Obstacle clearance Altitude): Obstacle clearance + VOR reception in 22 NM (noted with * on IFR charts)
- MEA (Minimum Enroute Altitude): Like MOCA, but VOR reception along all parts of the route (equal or higher than MOCA)
- MORA (Minimum Off-Route Altitude): Obstacle clearance 10 NM off-route
- MSA (Minimum Sector altitude): Obstacle clearance 25 NM around a fix

Special: MAA is the Maximum authorized altitude

### Approach classification

- Type A: DH 250 ft AGL or higher
- Type B: DH Below 250 ft AGL

## 03 - Fuel Planning – CAT.OP.MPA.106 and CAT.OP.MPA.150 plus AMC1, 2 and 3

### Basic fuel scheme

Mnemonic: TTCAFAED

- Taxi fuel
- Trip fuel
- Contingency fuel (5% trip OR 5 min hold/1500ft OR 3% trip if en-route alternative)
- Alternate fuel (fuel to fly to alternative, if defined)
- Final reserve fuel
  - Piston: 45 mins
  - Jet: 30 mins hold/1500ft
- Additional fuel
  - Flights without alternate: 15 min hold/1500ft
  - To fly to ERA (En-Route Alternative) with failure at most critical point
- Extra fuel: Expected delays
- Discretionary fuel: added by the commander

### Basic fuel scheme with variation

Lowest of:

- 3% of contingency fuel, if an ERA is available. ERA range is circle with radius of 20% trip distance. Center is bigger of:
  - 25% of trip distance from DEST
  - 20% trip distance + 50 NM from DEST
- 20 mins of trip fuel flow

### Requirement for alternate airport

- No alternate if:
  - Isolated aerodrome
  - Flight time < 6 hrs + 2 RWYs + Ceiling > 2000 ft (or Circling + 500 ft) + VIS 5 km at +-1 hr of ETA
- 1 alternate if conditions above minimum at destination (in this case, calculate for closer alternate)
- 2 alternates if conditions below minimum at destination (in this case, calculate for farer alternate)

### Reduced Contingency Fuel (RCF)

Also known as DPP (Decision Point Procedure). Use the larger of the two following:

- RCF-1 (to destination)
  - Trip fuel from DEP via DP to DEST
  - Contingency fuel from DP to DEST
- RCF 2 (to alternate)
  - Tip fuel from DEP via DP to ALT
  - Contingency fuel from DEP to ALT
 
Other fuel types are same for both

### Pre-determined Point Procedure (PDP)

Also known as LPD (Last point of Diversion). Use the larger of the two following:

- PDP-1 (to destination)
  - Trip fuel from DEP via PDP to DEST
  - Contingency from DEP via PDP to DEST
  - Additional fuel:
    - Piston: Lesser of 45 min + 15% OR 2 hours
    - Jet: 2 hours (including FRF)
- PDP-2 (to alternate)
  - Trip fuel from DEP via PDP to ALT
  - Contingency fuel from DEP via PDP to ALT
  - Additional fuel:
    - Piston: 45 mins
    - Jet: 30 mins hold/1500ft

### Fuel tankering

Tankered fuel is min of:

- MTOM - TOM
- MLM + TF - TOM
- Opt. Mass - TOM

## 04 - Pre-Flight Preparation

### Point of safe return

- Distance to PSR = t_total * GS_return * GS_out / (GS_return + GS_out)
- Time to PSR = d_PSR / GS_out

### Point of equal time

- Distance to PET = (GS_return * distance) / (GS_out + GS_return)
- Time to PET = d_PET / GS_out

## 05 - ICAO Flight Plan (ATS Flight Plan (FPL))

### Flight plan items

- Item 8 (Flight rules): V, I, Z (VFR->IFR) or Y (IFR-VFR)
- Item 9:
  - Wake: S to 7000 / H from 136000
- Item 15 (Cruising speed) is TAS
- Item 19 (Fuel endurance) is total fuel, without taxi

### Repetitive flight plans

- Minimum 10 trips in 10 days

## 06 - Flight Monitoring and In-flight Re-planning

### Hints for calculation

- Consider the direction, when working from both sides of a diagram
