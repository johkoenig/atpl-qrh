# 032 Performance

## 01 - General

### 01-01 Performance legislation

#### Performance definition

- Measured: On new aircraft
- Gross: Average performance in the fleet (= Measured, reduced by operating conditions)
- Net: Individual performance (= Gross, reduced by a safety margin)

#### Flight phases

- Take-Off: Brake release point to Screen height (35ft/A; 50ft/B)
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



### 04-02 Climb

### 04-03 Cruise

### 04-04 En-route one-engine-inoperative

### 04-05 Descent

### 04-06 Approach and landing

## 05 - CS-25/Applicable Operational Requirements Performance Class A – Use of Aeroplane Performance Data

### 05-01 Take-off

### 05-02 Drift-down and stabilising altitude

### 05-03 Landing
