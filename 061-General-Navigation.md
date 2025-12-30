# 061 General Navigation

## 01 - Basics of Navigation

### Earth shape

- Actually a geodid (irregular shape)
- Approximated as ellipsoid in WGS84
- In navigation further simplified to a sphere

### Coordinates on earth

- Longitude: angle between the plane of the prime meridian and line to a certain point
- Geocentric latitude: angle between the equator plane and the line from the centre of earth to a certain point
- Geodetic latitude: angle between equator plane and the normal (90°) to the meridian of a certain point

### Earth and sun

- Earth is farthest from the sun in July, closest in January
- Inclination of earths rotational axis is 23.44°
- Equinox (same length days) is about 21st September and 21st March

### Distances along lat/long

- N/S: 1° = 60 NM
- E/W: 1° = 60 NM x cos(lat)

### Directions

- TKE (Track error angle) is between planned track (C) and actual track (T)
- Drift is between heading (H) and actual track (T)
- WCA (Wind correction angle) is between planned track (C) and heading (H)

Pattern:

| TKE = | WCA + | Drift |
|:--:|:--:|:--:|
| C  | H | C |
| T |  T | H |

### Wind triangle on Aviat

Input:
- Heading on black number
- Airspeed on center dot
- Wind direction on red number
- Wind speed on triangle scale

Output:
- Course is Heading + drift
- Groundspeed is at wind speed point

### Rhumb line track

## 02 - Visual Flight Rule (VFR) Navigation

### Suitable ground features

Linear features (parallel for following, perpendicular for time check):

- Railways
- Motorways (but not small roads)
- Large Rivers
- Coastline
- Powerlines (esp. in winter when snow is covering ground features)

Individual ground features (unique and distinguishable):

- Airports with paved runways
- Special buildings (e.g. power plant)
- High masts (good for flying low)
- Large lakes (good for flying high)
- Towns with unique features (e.g. a special building)

### Getting lost procedure

- Fuel not critical: Note time, ask ATC for help
- Ful critical: PAN PAN 121.5
  
## 03 - Great Circles and Rhumb Lines

### Features of the lines

- Rhumb line has a fixed angle, i.e. it cuts all meridians at the same angle
- Great 

### Formulas

- Convergency = Diff. in Long x sin (mean Lat)
  - Northern Hem.: East is negative, West is positive
  - Southern Hem.: West is negative, East is positive
- Conversion angle at start/End = 1/2 of Convergency

### Convergency on lambert chart

- With given constant of cone: Convergency = Diff. in Long x Constant of cone
- With given standard parallels A and B: Convergency = Diff. in Long x sin(mean(A,B))

## 04 - Charts

### Projections

| Chart | Description | Parallel of origin | Shape of great circles |
|--|--|--|
| Mercator | Wrapped around the equator | 0° | Concave towards equator |
| Azimuth (e.g. Polar) | Piece of paper placed somewhere | varying / 90° for Polar | Concave towards the centre point |
| Lambert (conical) | One parallel of origin (sometimes between 2 standard parallels) | Mean of parallels | Concave towards the parallel of origin |

### Scaling

Small scale = large area

- A world map (1:100.000.000) is considered a small scale
- A city map (1:50.000) is considered a large scale

Think of scales as fractures, i.e. 1/100 is larger than 1/1000

## 05 - Time
