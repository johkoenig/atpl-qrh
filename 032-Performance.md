# 032 Performance

## 01 - General

### 01-01 Performance legislation

#### Performance definition

- Measured: On new aircraft
- Gross: Average performance in the fleet (= Measured, reduced by operating conditions)
- Net: Individual performance (= Gross, reduced by a safety margin)

#### Screen height

- Class B: 50ft
- Class A
  - 50ft: AoB > 15° at T/O and normal landings
  - 35ft: dry T/O and steep approaches
  - 15ft: wet T/O

#### Flight phases

- Take-Off: Brake release point to Screen height
- T/O climb: Screen height to 1500 ft AGL
- En-Route 1500 ft AGL to 1000 ft AGL
- Approach: 1000 ft AGL to Screen height
- Landing Screen height to Full-Stop

#### Consideration of wind during take-off

- Up to 50% headwind
- More than 150% tailwind

#### Certified thrust ratings

- Maximum Take-off Thrust (TO/TOGA): The highest thrust available for take-off/go-around, time-limited (usually 5 minutes, 10 minutes in OEI situations).
- Go-Around Thrust (TOGA): Part of Maximum Take-off, same category.
- Maximum Continuous Thrust (MCT): The highest thrust that can be used without time limit (e.g. after an engine failure during climb).

### 01-02 General performance theory

#### Terms and Equations

- Range = Speed * Max. flight time
- Spec. (air) range: SAR or SR = Range / Fuel burnt [NM/kg or NM/l]
- Spec. ground range: SGR = Range over ground / Fuel burnt [NM/kg or NM/l]
- Specific fuel consumption:
  - Jet: SFC = Fuel mass flow / Thrust [kg/Ns]
  - Prop: SFC = Fuel mass flow / Power [kg/kWh]
- Climb Gradient: CG = change in height / air distance [%]
- Flight path gradient: FPG = change in height / ground distance [%]
- Flight path angle: FPA = arctan(FPG)

#### Power/Thurst and Drag over IAS Curve

| Property | Jet | Prop | Note |
|--|--|--|--|
| Vert. Axis | Thurst/Drag | Power |
| Thrust/Power line | Horizontal | Curved |
| Lowest point | v_MD | v_MP | Max. Endurance (v_x) |
| Tangent | 1.32 * v_MD | v_MD | Max. Range (v_y) |

Notes:
- Prop = Power = v_MP (at lowest)
- Jet does not have a v_MP (PPP-Rule)

#### Power vs. TAS curves

| Property | Jet | Prop | Note |
|--|--|--|--|
| Power avail. | Linear from origin | Curved |
| Lowest point | v_MP | v_MP | Same for both |
| Tangent | v_MD | v_MD | Same for both |

#### Movement of Drag force vs. TAS curve

| Change | Increase | Decrease | Mnemonic (MAD) |
|--|--|--|--|
| Mass | Up + Right | Down + Left | M = / |
| Altitude | Right | Left | A = - |
| Dirty (Flaps, ...) | Up | Down | D = \| |

#### Movemnt of power and drag curves

| Flight phase | Power vs. TAS | Power req. vs. TAS | Drag vs. TAS |
|--|:--:|:--:|:--:|
| Climb | Down + Right | Up + Right | Right |
| Descent | Up + Left | Down + Left | Left |

- Mnemonic: Cl**i**mb = R**i**ght / D**e**scend = L**e**ft
- Left/Right shift comes due to TAS and does not exist for IAS (up to 0.4 M)

#### Runway distances

- TORA: Ground roll
- ASDA: TORA + Stopway
- TODA: Lesser of:
  - TORA + Clearway
  - 1,5 * TORA
- LDA: From screen height to full stop

### 01-03 Level flight, range and endurance

#### Best speeds

| Speed | Symbol | Jet | Prop |
|--|:--:|:--:|:--:|
| Best Endurance (longest time) | v_x | v_MD | v_MP |
| Best Range (longest air distance) | v_y | 1.32 * v_MD | v_MD |

#### Effects on SR and SFC

| Change | SR | SFC |
|--|--|--|
| Temp ↑ | ↓ | ↑ |
| Mass ↑ | ↓ | ↑ |
| Alt ↑ | ↑ | ↓ |

### 01-04 Climbing

#### Speeds with OEI

- v_XSE > v_x
- v_YSE < v_y

#### Climb calculation

- ROC ~ (Pa - Pt) / W 
- Gradient ~ (Ta - Tr) / W

### 01-05 Descending

- Basic equation:
  - Climb: T = D + W * sin(&gamma;)
  - Descent: D = T + W * sin(&gamma;)
- Descent angle &gamma; = arcsin((D-T)/W)
- Rate of Descent: ROD = GS * tan(&gamma;)

## 02 - C2-23/Applicable Operational Requirements Performance Class B - Theory

### 02-01 Airworthiness requirements

#### Speeds

| Type | v_r (rotate) | v_2 (50 ft) | v_REF (app) |
|--|:--:|:--:|:--:|
| SEP | 1 * v_S1 | 1.2 * v_S1 | 1.3 * v_S0 |
| MEP | 1.1 * v_S1 or 1.05 * v_MC |1.2 * v_S1 or 1.1 * v_MC | 1.3 * v_S0 or 1 * v_MC |

#### CAT SEP XC requirements

- No solid cloud below MSA (min safe altitude)
- Glide to 1000 ft agl above suitable landing area

### 02-03 Take-off and landing

#### Horizontal take-off flight path accountability area

In VMC, visual avoidance is sufficient

- Clear of obstacles for ME class B
- Semi-width = Starting semi-width + 0.125 D
  - Starting semi-width = 60m + 1/2*wingspan (max. 90m)
  - D = distance from TODA
- Max value of semi-width, if turns < 15°
  - 300 m with navaids or VMC
  - 600 m otherwise
- Max value of semi-width, if turns > 15°
  - 600 m with navaids or VMC
  - 900 m otherwise
 
#### Obstacle clearance

- OC = AC height - Obs height + screen height

#### Min climb gradients

- No requirements for SE
- ME departure:
  - Standard: 4%
  - OEI 400ft: 0%
  - OEI 1500ft: 0.75%
- ME missed:
   - Standard: 2.5%
   - OEI 1500ft: 0.75%

### 02-04 Climb, cruise and descent

- Net glide gradient is 0.5% higher than gross glide gradient

## 03 - CS-23/Applicable Operational Requirements Performance Class B – Use of Aeroplane Performance Data for Single- and Multi-engine Aeroplanes

## 04 - CS-25/Applicable Operational Requirements Performance Class A – Theory

### 04-01 Take-off

#### Decision Speed v_1

- Must be higher than: v_MCG
- Must be less than: v_MBE // v_R
- Increases with ALT, TEMP, TOM, headwind, upslope
- Decreases with Flaps

#### Take-Off Safety Speed v_2

- Must be higher than v_2MIN, which is: 1.1\*v_MCA // 1.13\*v_SR or 1.08*v_SR (4x prop or jet with provisions)
- Decreases with ALT, TEMP, Flaps
- Increases with TOM

#### Final Take-Off Speed v_FTO

- > 1.18*v_SR
- Must provide at least minimum climb gradient

#### Non-standard take-off procedures

- T/O with reduced thrust (saves engine life)
  - Derating (by fixed value) -> Derated Thrust is op. limit, allowed on cont. RWY
  - Assumed temperature (flexible temp / FLEX) -> TOGA remains available, prohibited on cont. RWY
- T/O on wet/contaminated RWY (TODR/ASDR increase, TOM/v_1 decrease)
- T/O on wet/contaminated RWY with reduced Thrust (v_MCG reduce)
- T/O with increased v_2 (increases OLTOM, higher v_1)

#### Field balance

- Balanced (No Stopway, no Clearway): TOD(n-1) = ASD(n-1)
- Unbalanced (with Clearway): TOD > ASD -> v_1 needs to be reduced
- Unbalanced (with Stopway): TOD < ASD -> v_1 needs to be increased

#### TOM limitations

- Regulated TOM (RTOM), lesser of:
  - Performance-limited TOM (PLTOM)
  - Max. structural TOM (MSTOM)
- Field-length limitedd TOM (FLLTOM)
- Climb-limited TOM (CLTOM)
- Obstacle-limited TOM (OLTOM)

#### Max. bank angle during T/O

| Altitude | Normal | Special Approval |
|--|--|--|
| < 50ft | 0° | same |
| 50 - 200ft | 15° | same |
| 200 - 400ft | 15° | 20° |
| > 400ft | 25° | 30° |

#### Runway conditions

- Surface conditions (need to be > 25%)
  - Dry
  - Damp: Moisture, but no shiny appearance
  - Wet: Moisture appears reflective
  - Contaminated: Ice, Water/slush/snow > 3 mm, Compacted snow (all are falling from cloud)
- Hydroplaning types:
  - Dynamic: On standing water
  - Viscous: On water + dirt or rubber
  - Reverted rubber: blocked tyre, heating up, forming steam bubble
- Max. speed for dynamic hydroplaning:
  - Rotating tyres: v > 9 * sqrt(tyre press in psi)
  - Non-rotating tyres: v > 7.7 * sqrt(tyre press in psi)
 
#### Net T/O flight path (NTOFP)

- Segment 1: End of TODR to "Gear up" (v_2, T/O Thrust)
  - 2-eng gradient: 0 %
- Segment 2: "Gear up" to 400ft (v_2, T/O Thrust)
  - 2-eng gradient: 2.4 %
- Segment 3: 400ft to "clean" (v_2, MCT Thrust)
  - 2-eng gradient: 1.2 %
- Segment 4: "clean" to 1500ft (at v_FTO or v_x)
  - 2-eng gradient: 1.2 %
 
For 3-eng add 0.3%, for 4-eng add another 0.2% (2. segment 0.3%)

#### Special drag types relevant to the T/O roll

- Displacement drag: Resisting forward movement of the wheels or floats
- Impingement drag: Spray that hits the landing gear or airframe

They act negatively on the TOD, positively on the RTO distance and varying on the ASD

#### Gross climb gradient

- 2-engine: GCG = NCG + 0.8%
- 3-engine: GCG = NCG + 0.9%
- 4-engine: GCG = NCG + 1.0%

### 04-02 Climb

#### Climb phases

- Phase 1: GND to FL100 (max 250kts IAS)
- Phase 2: FL100 to crossover ALT (const IAS)
- Phase 3: crossover ALT to en-route ALT (const M)

#### Cost Index

- CI = Cost of Time / Cost of fuel
- Higher CI = faster flight

### 04-03 Cruise

#### Speeds

- Max. Range Cruise Speed v_MRC: Best fuel economy
- Long Range Cruise Speed v_LRC: ~1.04*v_MRC, but only ~1% of higher fuel consumption

#### Step climb

- Limited by the 1.3g buffet onset
- When flying 2000ft below optimum ALT a step should be performed

#### High-ALT buffets

- Low-speed vuffet is a fixed CAS number
- High-speed buffet is a fixed Mach number

#### Ceilings

- Aerodynamic Ceiling (1.0g)
- Manoeuvre ceiling (1.3g)

### 04-04 En-route one-engine-inoperative

#### Procecure

- MCT on good engine
- Maintain ALT and decellerate to v_MD (drift-down speed)
- Maintain v_MD and descend

#### Min. ALT clearance

- Stabilized: 1000 ft
- Above airport: 1500 ft
- Driftdown proc.: 2000 ft

### 04-05 Descent

#### Continoous descent arrivals

- Stay higher longer
- Avoid level-off
- fly with minimum thrust

#### Influence of wind

- Headwind: Later TOD
- Tailwind: Earlier TOD

1 NM per 10 kts

### 04-06 Approach and landing

#### Speeds

- v_REF = 1.23 * v_SR0

#### Balked landing (AEO)

- Min. climb gradient: 3.2%
- Speed > 1.23*v_SR and v_MCL
- Power lever moving from flight idle to TOGA: Thrust must be available within 8 secs

#### Discontinued approach (OEI)

- OEI, approach flap & gear up
- Speed < 1.4 * v_SR
- Min. climb gradient 2-eng: 2.1% (+0.3% per 3/4 engine)
- Bank angle to live engine is limited to 2-3°

#### Landing distances

- Jet: 60% RWY (factor 1.66)
- Prop: 70% RWY (factor 1.43)

Factor 1.15 for wet RWY

#### Quick turnaround factors

- Altitude & Temp
- Flap setting
- RWY slope
- Wind

Limiting factor are the fuse plugs melting, not the brake performance!

#### Braking performance

- Autobrake: Increase in LDR due to braking at selected rate
- Antiskid: Decrease in LDR due to braking at maximum rate

## 05 - CS-25/Applicable Operational Requirements Performance Class A – Use of Aeroplane Performance Data

### 05-01 Take-off

### 05-02 Drift-down and stabilising altitude

### 05-03 Landing
