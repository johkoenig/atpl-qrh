# 021 Airframe, Systems, Electrics, Power Plant

## 01 - System Design, Loads, Stresses, Maintenance

### Design concepts

- safe life: One load path, no catastrophic failure for a given amount of time or cycles
- fail safe: Alternate load path, if one path fails, the other can take all load for a limited amount of time

### Signs of over-stress

 - Missing rivet heads
 - Wrinkles (wavy patterns) or strecthed skin, cracks, buckles
 - Screws are loose, damaged or destroyed
 - Physical restriction of control surfaces

### Possible limits

- Calendar time
- Operating hours
- Landings

### Corrosion

- Mostly a problem near the sea, when flying low and with hot temperatures
- Aluminium shows grey/white powder, steel shows red/brown
- Corrosive fluids: Mercury, battery acid, water, toilet waste

## 02 - Airframe

### Stability of the fuselage

- Longitudonal: By longerons and stringers
- Radial: By frames and bulkheads
- Around openings in the skin: Through doublers

### Cockpit windows

- Made of layers of glass and vinyl (with vinyl being more important)
- Heated to assure strength, impact resistance (bird strike) and flexibility of material
- Side windows are usually not heated, just defogged

## 03 - Hydraulics

### Basics

- System pressure in large aeropplanes ~ 3000 psi
- Nitrogen is used as inert gas
- Used by control surfaces (namely horizontal stabilizer) and undercarriage
- Failure of one of the two systems will cause a "Master Caution" (Amber)

### Hydraulic accumulator

- Stores a limited amount of hydraulic fluid under pressure
- Allows a limited amount of brakings, in case of normal system failure
- Further dampens fluctuations and allows thermal expansion of the pressurized fluid

### Hydraulic pumps

- Constant delivery pump: Constant amount, variable pressure
- Demand or Swashplate or axial piston pump: Variable amount, constant pressure
- Power-transfer unit (PTU): Basically 2 pumps connected, to transfer power from one hydraulic system to other

### Valves

- Check or Non-return valve: Only allowing flow in one direction
- Restrictor value: Allow flow in one direction, limiting in the other
- Automatic cut-out valve (ACOV): Returns fluid to reservior if pressure is above a predefined value

## 04 - Landing Gear, Wheels, Tyres, Brakes

### Nose wheel steering

- Via rudder: up to 7° (deactivated in the air by squat switch)
- Via tiller: up to 78°

### Tyre damages

- Sidewall damages (bulges, cuts) are not OK
- Limited cuts on the tread itself are acceptable

###  Brake materials and wear

- Metal: Need low temperature, therefore braking with large number of small pulses. Wear depends on usage time and temperature
- Carbon: Need high temperature, therefore use a single firm braking pulse. Wear depends on number of applications

### Autobrake / RTO

- Will try to breake at a constant rate (G-force)
- Any support (i.e. reverse thrust) will reduce the brake pressure
- Autobrake value must be selected proper to the surface friction

## 05 - Flight Controls

## 06 - Pneumatics – Pressurisation and Air Conditioning Systems

## 07 - Anti-icing and De-icing Systems

### Ice Detection Systems

- Pressure-Differential (Smith) Detector:
  - Tube with small holes in front and larger holes in back
  - Ice will block small holes, causing a drop in dynamic pressure, which leads to an indication
  - Small holes can be freed by heating
- Rosemount (Piezoelectric) Detector:
  - Vibrating rod
  - With ice aggregation, the frequency of vibration changes, which leads to an indication
 - Hot Rod Detector:
   - Ice build up on a standing rod, can be inspected visually
   - Heater will free the rod from ice upon activation

### Ice Detection System Classification

- Primary automatic: Ice protection is automatically enabled from ice detection
- Primary manual: Ice protection is enabled by the crew based on ice detection indication
- Advisory: Ice detection serves as a backup for other signs of ice aggregation.

### Anti-Ice Systems

- Fluid: Used for leading edges of wings
- Hot bleed air: Used for turbine engine intakes
- Electric: For small parts like pitot tubes, static ports and windshields (3-phase AC there)

### De-Ice Systems

- Boots: Used on leading edges, need a certain amount of ice to work

## 08 - Fuel System

### Tank types

- Integral: Directly in the structure, mostly in wings of large aeroplanes
- Drum/Rigid tanks: Most common for small aeroplanes
- Bladder/Flexible: Very seldom for primary tank, often used for range extension

### Details of airliner fuel system

- Check values (non-return valves) in baffles assure that fuel is concentrated at the wing root, where the pump is.
- LP pump takes fuel from tank to line
- HP pump takes fuel from line to engine

Failure of LP pump can lead to cavitation in HP pump at high altitudes

## 09 - Electrics

### Circuit breakers

- Magnetic: Quick response, due to magnetic field
- Thermal: Slowed response, as bimetallic strip takes time to heat up during overcurrent

### Conversion of DC and AC

- Inverter: DC to AC
- Rectifier: AC to DC
- Transformer Rectifier (TRU): 115/200V AC to 24V DC

## 10 - Piston Engines

## 11 - Turbine Engines

## 12 - Protection and Detection Systems

## 13 - Oxygen Systems
