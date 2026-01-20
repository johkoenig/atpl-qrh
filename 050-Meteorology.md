# 050 Meteorology

## 01 - The Atmosphere

### 01-01 Composition, extent, vertical division

#### Troposphere

- Lowest layer, where weather forms
- Upper limit and temperature: 
  - Polar: 8 km (FL250 - FL300), -52 °C
  - Mid: 11 km, 56.5 °C
  - Equatorial: 16 km (FL500 - FL 600), -74 °C
  - Higher in tropical areas
  - Higher in summer (+3000 ft), lower in winter (-3000 ft)
  - Tropopause height ~ 16 * cos(Lat) x 

#### Tropopause

- Seperates Troposphere and Stratosphere
- Change in lapse rate of temperature (to zero, stays at -56.5 °C)
- Ozone heats up by UV radiation from sun
- Ozone is harmful to humans

#### Air

- 78% Nitrogen, 21% Oxygen, 1% Argon, Rest other
- Water vapour is the main reason for weather

### 01-02 Air temperature

#### Heating and cooling of air

- Solar radiation: short-wavelength UV radiation from sun (mostly heating earth)
- Earth radiation: Long-wave IR radiation, picked up the greenhouse gases
- Conduction: Air is warmed by ground during day, Air is cooled by ground during night
- Convection: Vertical movement of air into the atmosphere (upwards)
- Subsidience: Vertical movement of air to the ground (downwards)
- Condensation: Forming of clouds releases heat

Most significant:

- Lower layers: Conduction and Turbulence (and some IR radiation)
- Medium layers: Convection and IR radiation from earth
- High layers: Absorption by the ozone layer

#### Inversion

- Radiation inversion: Ground cools via infrared
- Advection inversion: Warm air moves over cold ground
- Subsidience inversion: Air descending and warming up, staying on top of cold air (seen often in northern continents)
- Frontal inversion: Cold front moving, lifting warm air
- Valley inversion: Cold air moving down the hill

#### Influence of clouds

- Lowest temperature usually about 30 mins after sunrise on a clear calm day
- Clouds reflect UV radiation from sun
- Clouds absorb infrared radiation from earth and re-radiate parts back (lower & thicker = more)

### 01-03 - Atmospheric pressure

#### Pressure designations

- QNH: Atmospehric pressure adjusted to sea level
- QFE: Pressure on altimeter when set to 0 on ground
- QNE: 1013,25 hPa
- QFF: Mean sea level pressure incl. temeprature correction. Printed on surface pressure charts
  - QFF is higher than QNH if temperature is above ISA

#### Ridge and Trough

Refers to the surface

- Rigde: Line of high pressure (usually fair weather, air diverges at it)
- Trough: Line of low pressure (often cloudy and precipitation, air converges to it)

Special: Col is the area in the middle between 2 high and 2 low pressure systems

### 01-04 - Air density

#### Density with altitude

- Sea level: 1,225 kg/m^3
- Half at FL 220
- Quarter at FL 400

### 01-05 - International Standard Atmosphere (ISA)

#### Temperature

- 15 °C on sea level
- 2°C/1000 ft until FL 360 (-56.5°C), then stable until FL 650 (~20 km)

#### Flight level pressure

- Sequence 7-5-3-2-1 for FL100/180/300/390/500 (almost 100 each)
- Half (500 hPa) at 5500 m / FL 180
- Quarter (250 hPa) at 11000 m / FL 360

#### 01-06 - Altimetry

#### Correction of altitude

- Use PIT rule
- 4% per 10°C ISA deviation (height only!)
- 27ft or 30ft per hPa on the QNH

### Rules of thumb

- In winter (cold), the mountains are higher (FL is less than true alt)
- From high to low, no-no! (Low system, FL is less than true alt)

## 02 - Wind

### 02-01 - Definition and measurement of wind

#### Wind reports

- ATIS/TWR: Magnetic, average of 2-minute period
- METAR/VOLMET: True, average of 10-minute period

#### Directions

- Veering: Turning clockwise
- Backing: Turning Anti-clockwise

### 02-02 - Primary cause of wind

#### Geostrophic wind

- Combination of:
  - Pressure Gradient Force (PGF): The higher the pressure gradient, the stronger the wind
  - Coriolis force (CF): Makes wind go parallel to isobars (Veering in N, Backing in S)
- Almost perpendicular to PCF
- Actually this wind is very rare, because it requires straight isobar lines
- Wind speed: V = PGF / (2 * omega * rho * sin(lat))

#### Gradient wind

- Geostrophic wind around curved isobars
- Around depression / low / cyclone: Lesser than geostrophic wind
- Around anticyclone / high: Larger than geostrophic wind

#### Surface wind / Friction layer

- Measured in 10 m /33 ft
- Up to 2000 (night) or 3000 ft (day) AGL
- Compared to upper wind (30° over land, 10° over water)
  - Backing in N hemisphere
  - Veering in S hemisphere
- Speed 50% reduction over land, 30% reduction over water
- Backing (N) and veering (S) is more pronounced at night (night time effect)
- Friction layer influenced by: terrain/surface, wind speed, stability

#### GND Convergence and Divergence

- Convergence: Low at GND, High at ALT -> Ascending wind, clouds, precipitation
- Divergence: High at GND, Low at ALT -> Fair weather

### 02-03 - General global circulation

#### Buy's Ballots Law

- Rotation around high: Clockwise (N) / Counter-Clockwise (S)
- Rotation around low: Counter-Clockwise (S) / Clockwise (N)

#### Circulary cells

- Polar
- Ferrel
- Hadley (GND Convergence at 0°)

### 02-04 - Local winds

Local winds require flat pressure gradients (otherwise, global winds are dominant)

- Sea breeze (stronger, day) / Land breeze (night)
- Anabatic (up the hill, day) / Katabatic (Stronger, down the hill, night)
- Valley wind
- Nocturnal low-level jet (during night, above inversion)

### 02-05 - Mountain waves (standing waves, lee waves)

#### Conditions

- Wind speed > 15 - 20 kts
- Wind direction perpendicular (max. 30°)
- Layer of stable air forced up the hill

#### Effects (leeward side)

- Lenticularis clouds (above summit altitude)
- Breaking waves (up to tropopause/FL600)
- Rotors (at/below ridge height)

Note: If turbulence is caused by jet stream, it is called CAT (even if near mountains)

### 02-06 - Turbulence

Irregular and instantaneous movement of air

#### Types

- Mechanical: By objects
- Thermal: By Convection
- Cloud: near Cb
- Orographic: Mountain waves, rotors
- High-level CAT: Above/Below Jet stream and on cold side
  - Can cause aircraft damage
  - Best source are reports from other aircraft
- Low-level CAT: Squall line near cold front
- Frontal

### 02-07 - Jet streams

#### Basics

- 4 Jet streams at 60N 30N 30S 60S (between cells)
- All blowing from west at 60 - 220 kts (up to 300 kts in Japan)
- Identified by streaked cirrus clouds
- CAT on cold/low/cyclonic side & above/below of core

#### Polar Jet Stream

- Core is in tropical air, below tropopause
- North polar jet stream has most curves
- Core height: FL300
- Stronger in winter

#### Equatorial/Tropical jet stream

- The only one blowing from east
- Only during summer at 15 N (in ITCZ)
- Core height: FL500

## 03 - Thermodynamics

### 03-01 - Humidity

#### Basics

- Absolute amount of humidity is greatly influenced by temperature
- At poles, almost no absolute humidity, at equator, up to 25 g/m^3
- Air saturation (= 100% RH)
  - Saturated: T = T_DP
  - Unsaturated T > T_DP
- saturated air is less dense than dry air (1.225 g/m^3)

#### Equations

- RH = (mass of water vapor) / (max mass of water vapor) [%]
- RH = 100 - 5*(T - T_DP) [%]
- Mixing ratio: MR = (mass of wator vapor) / (mass of dry air)

### 03-02 - Change of state of water

#### State changes & Latent heat

- Solid -> Melting -> Liquid -> Evaporation -> Gas (or Sublimation if no liquid)
  - Latent heat absorbed
- Gas -> Consensation -> Liquid -> Freezing -> Solid (or Deposition if no liquid)
  - Latent heat released
 
#### Condensation nuclei

- Fixed particles that act as an enabler for condenstaion or deposition
- e.g. Dust, Air pollution
- Without nuclei, larger supercooled water droplets persist (they freeze to ice upon contact with nuclei)

### 03-03 - Adiabatic processes

#### Stability

- ELR: Environmental lapse rate (variable)
- DALR: Dry adiabatic lapse rate (3°C/1000ft or 1°/100m)
- SALR: Saturated adiabatic lapse rate (1.8°/1000ft or 0.6°/100m)

| Stability | Requirement |
|--|--|
| Absolute instability |   ELR > DALR |
| Conditional instability | DALR > ELR > SALR |
| Neutral stability | ELR = SALR or ELR = DALR |
| Stability | SALR > ELR |

- Stability is called neutral if ELR = SALR or ELR = DALR
- The lesser the lapse rate, the more stable
- Inversion is ELR < 0, so very stable
- Isothermal = Lapse rate 0° = very stable

## 04 - Clouds and Fog

### 04-01 - Cloud formation and description

#### Form

- Cumuliform: Towered, like "sheep"
- Stratiform: flat, widespread, minimal vertical size
- Cirriform: High alt, hair-like

#### Cloud features

- Ci: Ice crystals, but little risk of icing. VIS > 1000 m
- Cb: Ice crystals at top of anvil
- TCu: MOD-SEV TURB and MOD-SEV icing

#### Cloud altitudes

Level is defined by the base!

- Low: up to 6500 ft (contain water droplets)
- Middle/Alto: 6500 - 23000 ft (contain both water droplets and ice crystals)
- High: 23000 ft and higher (contain ice crystals)

#### Special cumulus types

- Cumulus fractus: Looks more like low-level cirrus (ripped parts of Cu clouds)
- Cumulus congestus: Towered cumulus
- Cumulus capilatus: With anvil developing, almost a Cb

However, for AC clouds the range is 7000 - 15000 ft

### 04-02 - Fog, mist, haze

#### Types

- Fog: VIS < 1000 m, RH ~ 100%
- Mist: VIS 1000 - 5000 m, RH > 95%
- Haze: VIS < 5000 m due to solid particles (i.e. dust)

#### For types

- Advection fog
- Radiation fog
- Orographic fog
- Steaming fog / Arctic smoke / Sea smoke
- Frontal fog (warm front touching the ground, rain falls into cold air)
- Freezing fog (supercooled water droplets, which will freeze when they hit the cold aircraft)
- Ice fog (below -40°C)

## 05 - Precipitation

#### 05-01 - Development of precipitation

#### Theories

- Wegener-Bergeron-Findeisen (WBF) process:
  - Ice crystals grow from liquid droplets in the cloud
  - Happens in Cbs, below 0°C
  - Can form rain, snow, hail
- Coalescence process: Falling and rising water droplets collide
  - Happens in stratiform and Cb clouds
  - Supported by convection
  - Can form light rain or drizzle

#### Formation

- Hail: Cb with ice crystals and water
- Snow: From supercooled water droplets and ice crystals
- Snow grains: from stratus or supercooled fog

### 05-02 - Types of precipitation

- Drizzle: 0.2 - 0.5 mm
- Ice pellets (PL): Small pellets < 5mm
  - Transparent
- Hail (GR): > 5 mm
- Small Hail (GS): < 5 mm (a.k.a. Soft Hail / Graupel)
  - White

## 06 - Air Masses and Fronts

### 06-01 - Air masses

#### Basics

- Air masses are generated at areas of high pressure -> stable at source
- Warming/cooling by heat transfer due to radiation, conduction and convection

#### Classification by temperature

- Arctic (A)
- Polar (P)
- Tropical (T)
- Equatorial (E)

#### Classification by humidity

- Continental (dry, over land)
- Maritime (Humid, over water)

#### Movement characteristics

- Warm air moves over cold surface -> stability, inversion (advection fog)
- Cold air moves over warm surface -> instability, showers

#### Designation

- First letter is humidity (c or m)
- Second letter is temperature (A, P, T or E)
- Second letter is cold or warm (c or w)

### 06-02 - Fronts

#### Global fronts

- Arctic front: Between arctic and polar air
- Polar front: Between cold polar and warm tropical air
- Mediterranean front: Between polar air from europe and tropical air from north africa (winter only)

#### Fronts

| Property | Warm front | Cold front |
|--|:--:|:--:|
| Air masses | warm moves over cold | cold moves below warm |
| Slope | 1:150 | 1:50 or 1:80 |
| Clouds | Ci, stratiform | stratiform, Cb |
| Clouds behind | None | Cu/Cb |
| Precipitation | stable, widespread | unstable, gusts, GR, TS |
| Air after pass | T↑ p↓ | T↓ p↑ |
| Geostrophic Wind Speed | 1x | 0.66x |

#### Frontal depression

- Warm front ahead of cold front
- Turning around a low
- Will develop an occlusion
- Polar front depressions move east (from atlantic ocean to europe)
- Depression exists for 4-7 days in mid-latitudes, sometimes a little bit longer

#### Stationary front

- A warm and a cold front moving against each other, staying stationary
- Weather is a mix of both fronts

#### Occlusion

| Property | Warm front occ. | Cold front occ. |
|--|:--:|:--:|
| Coldest ahead | ahead | behind |
| Chart line continue | warm front | cold front |
| More occurence | winter | summer |

## 07 - Pressure Systems

### 07-01 - The principal pressure areas

#### Stable pressure areas

- Azores: Always high
- Iceland: Always low
- Siberia, USA: High in winter, low in summer
- Mediterranean: Low in winter, high in summer
  
### 07-02 - Anticyclone (High)

#### Types of anticyclones

- Cold anticyclone: Weakens with increasing altitude
- Warm anticyclone: Increases with increasing altitude
- Blocking anticyclone: Stationary, limits depression movement (usually warm subtropical highs)

#### Pressure surface chart (isobar chart)

- High: Bulge upwards at the bottom
- Low: Bulge downwards at the bottom
- Warm: Bulge upwards at high altitude
- Cold: Buld downwards it high altitude

### 07-03 - Non-frontal depressions (Lows)

- Orographic low: On leeward side of mountain ridge
- Secondary depression: Forming on a cold front of the primary depression, moving cyclonic around it
- Polar lows are small and form over water
- Thermal lows from over water or land 

### 07-04 - Tropical revolving storms

#### Basics

- Lat. 5° - 25°
- Requires water > 26°C
- Size 200 - 1000 km, size of eye 20 - 50 km
- Travel westwards, then away from equator, then eastwards

#### Types

- Hurricane: Atlantic / E Pacific
  - USA (Late summer, 6-7 p.a.)
- Cyclone: SW pacific
  - Australia (Winter, 7-9 p.a.)
  - India (Summer, ~12 p.a.)
- Typhoon: NW pacific
  - Japan (Summer - Autumn, ~20 p.a.)
 
#### Stages

- Tropical disturbance: SHRA and TS, Wind < 17 kts
- Tropical Depression: Wind 17 - 33 kts
- Tropical Storm: Wind 33 - 63 kts (severe above 47 kts)
- Tropical Cyclone/Hurricane/Typhoon: Wind > 63 kts

TRS do NOT originate from the south atlantic ocean!

## 08 - Climatology

### 08-01 - Climatic zones

#### Zones

| Letter | Name | Latitude | Description |
|:--:|--|:--:|--|
| E | Polar/Artic | > 70° | no warm summers |
| D | Continental Sub-Arctic | 50°-70° | short summers, long winters |
| C | Temperate | 40°-60° | Distinct seasons |
| B | Sub-tropical dry | 20°-35° | Deserts |
| A | Tropical wet | < 10° | Rainforest |

#### Stabilizing factors

- Earth's rotation rate
- Wind from high to low
- Unequal heating of land and sea

08-02 - Tropical climatology

#### Trade winds

- Strong easterly winds, GND to FL100
- From subtropical high (a.k.a. horse latitudes) to ITCZ (= thermal equator = doldrums)
- Change direction when passing the geographic equator (NE backs to NW, SE veers to SW)
- Dry and weaker over land, humid and stronger over water (but still fair weather)

#### Intertropical convergence zone (ITCZ)

- Trade winds from north and south collide, causing little wind overall (doldrum)
- Intense solar radiation, lots of convection
- Frequent Cb/TS at noon, up to FL500
- Zero Degree Isotherm at FL160 / Icing risk FL160 - FL260

#### South-Asian & West-African Monsoon

- Winter: NE wind (land to ocean), dry (cold air from Siberian high)
- Summer: SW wind (ocean to land), Cb/TS (redirected trade wind, 80% of rain in India)

#### Polar air outbreaks

- Impact central & northen China in winter
- Cold fronts for arctic/polar area bring cold air

#### Sandstorm

- Particle size 0.08 to 0.3 mm
- Wind speed > 20 kts

### 08-03 - Typical weather situations in the mid-latitudes

#### Cold-air drop

- Can be released as polar jet stream weakens in winter
- Cold-air/Low-pressure surrounded by warm air
- Moving southward from poles, but hard to predict exactly
- FL160 - FL300 (seen on 500 hPa chart)
- Unstable, TS, Rain, Icing

#### Flat pressure pattern

- Low pressure diff -> Low winds
- Warm air is lifted in summer, leading to TS in the afternoon

#### Westerlies

- Common in middle-latitudes
- Interconnected warm and cold front bands (from a polar frontal depression)
- Moving west, with varying weather

### 08-04 - Local winds and associated weather

- Foehn (Alps)
- Mistral (Valley wind between alps central massiv in France / Cold, dry, N/S)
- Bora (East Europe and Adria in Winter / Strong, cold, dry)
- Harmattan (North Africa in winter / Dry, with Sand, NE)

## 09 - Flight Hazards

### 09-01 - Icing

#### Types of icing

| Type | Shape | From |
|--|--|--|
| Clear ice | Transparent, heavy, strong | Large SCT in Cu, Cb, Ns |
| Rime ice | Opaque, white, light, weak | Small SCT in St, Sc, As, Ac, Ns |
| Mixed ice | Combination of both | Small & large SCTs in Cu, Cb, Ns |
| Hoar frost | Frost | Cold airframe in warm air |

#### Ice crystal icing

- Needs < -40°C and high ice water content (g/m^3)
- Happens in or downwind to upper levels of convective cloud (Cb anvil)
- Connected to tropical TS
- Issue to:
  - Jet engine (melting in then freezing in compressor)
  - Windshield
  - Incorrect TAT reading (0°C)

#### Icing contributors

- Thin leading edge
- More speed
- Larger droplets

#### Avoidance by cloud type

- St: Climb
- Cb: Avoid / Re-route
- Ns (with FZRA): Turn back
  
### 09-02 - Turbulence

see 02-06

### 09-03 - Wind shear

- Vertical wind shear can happen along an inversion
  - A sign can be virga
- Delay take-off if wind shear is reported
- Vertical wind shear = wind is different in different heights (in kts/100ft)
- Horizontal wind shear = wind is different at same height (in kts/1000ft)

### 09-04 - Thunderstorms

#### Basics

- Require warm air, humidity and instability (ELR < SALR = lifting action)
- Avoid by 10 NM (20 NM above FL200) and 5000 ft
- Detect by visual cues, stormscope and AWR

#### Types

- Air-mass (weaker/slower, during day in summer)
- Frontal (stronger/faster, more typical in winter day & night)
- Single-cell
- Multi-cell (caused by wind shear, can develop to squall lines)
- Supercell  (breakdown of inversion, wind shear develops to vortex)
- Orographic

#### Stages

- Initial/TCU (15 - 20 mins, updrafts)
- Mature (20 - 30 mins, up- and downdrafts)
- Dissipating (1.5 - 2.5 h, downdrafts)

#### Lightning types

- Intra-cloud
- Cloud-to-air
- Cloud-to-cloud
- Cloud-to-ground
- Ground-to-cloud (a.k.a. upward lightning)

#### Risks

- Turbulence
- Icing
- Water ingestion in the engine
- Static elictricity
- Wind Shear & Microbursts

### 09-05 - Tornadoes

#### Basics

- Vortex in a mesocyclone, causing a column of rotating air
- Up to 100 m in width
- Movement speed 20 - 40 kts
- Wind speed up to 50 - 200 kts

#### Other phenomena

- Dust devil: From dry and hot air (Shorter-lived, smaller, less wind speed)
- West African Tornado (WAT): Easterly wave, squall line perpendicular to ITCZ

### 09-06 - Inversions

- Warm temperature air above cold
- Strongest in deserts

### 09-08 - Hazards in mountainous areas

- Valley inversion (fog and wind shear)
- Rotors and mountain waves
- Icing near mountain ridge (due to lifted cold moist air)

### 09-09 - Visibility-reducing phenomena

- Sandstorm (VIS 200 - 600m)
- Heavy sandstorm (VIS < 200m)
- Heavy drizzle (VIS < 500m)
- Blowing Snow (VIS < 1m)
- Tropical downpour (tens of meters)
- Inversion Mist/Haze: Reflecting sunlight on top

### 09-07 - Stratospheric conditions

- Constant temperature
- Low air density
- Strong wind but no turbulence
- Higher cosmic radiation

## 10 - Meteorological Information

### 10-01 - Observation

#### Cloud detection

- Visual limited to day, Infrared limited to higher alt (due to temperature diff)
- Visible on both: Thick convective cloud
- Visible on Visual only: Low cloud or fog
- Visible on IR only: High & thin, e.g. Ci/Cs

#### Runway condition codes

- 6: Dry
- 5: Wet
- 4: Compacted snow
- 3: Slippery wet
- 2: Slush
- 1: Wet Ice

#### RVR

- If less than 1500m
- In metres (acc. Annex 3) or metres/feet (acc. ICAO & discretion of state)

#### Short-time wind change

Less than 1 minute

- Gust: 10 kts
- Squall: 20 kts

#### AIRREP

- Prefixes:
  - ARP: Air report
  - VA: Volcanic Ash
- Content: ID, Pos, Alt, Time, Observation 


10-02 - Weather charts

10-03 - Information for flight planning

#### 10-04 - Meteorological services

- Meteorological Watch Office (FIR)
- World Area Forecast Centre
- Tropical Cyclone Advisory Centre

