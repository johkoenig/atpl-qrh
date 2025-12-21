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

### Primary and secondary flight controls

- Primary: Rudder, Elevator, Aileron, Roll control (REAR)
- Secondary: Flaps, Slats, Stabilizer, Speed Brake, Trim Tabs (FSSST)

### Flight control systems

- Manual: Mechanical by cable or bar
- Partially powered: Mechanical, assisted by hydraulics
- Fully powered: Only hydraulic
- Fly-by-Wire: Electric sensing, processing via computer

Last two are irriversible, requiring artifical feel, but no gust locks

### FBW control modes

- Normal Law / Normal Mode: All protections available
- Alternate Law / Secondary Mode: Some protections available
- Direct Law / Direct Mode: No protections available, but warnings are still present

### Trimming

- Reversible: Trim Tab
- Irriversible: Zero-force point (but no control movement on elevator axis)

### Fly-By-Wire Stall Protection

- Alpha prot = pitch control
- Alpha floor = power control (TOGA thrust, if necessary)
- Alpha max = max. allowed pitch

### Rudder deflection protection

- Rudder ratio changer
- Blow-back (constant force)
- Variable Stops

## 06 - Pneumatics – Pressurisation and Air Conditioning Systems

### Pressurization concept

- Air taken from HP compressor stage of engine (bleed air)
  - On ground: Pack cooling fans provide airflow for air-con
- Constant inflow into cabin (for ventilation)
- Regulated outflow via outflow valve
- Emergency valves
  - Positive pressure relief valve (if max. diff. pressure + 0.25 psi)
  - Negative pressure relief value (if outside > 0.5 - 1 psi of inside)

### Gauges

- Cabin altitude
- Cabin rate of change
- Diff. pressure (usually max. 7-9 psi)
- Warning if cab. alt. > 10.000ft

### Malfunction of bleed air

- Bleed duct leak warning appears in cockpit
- Reduced airflow into cabin

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

### Magnetos

- When turned OFF, both primary and secondary circuit are grounded
- If engines still operates, one of the grounding wires (usually the primary) is broken

### Turbochargers

- Ground-boosted: More power is given at all altitudes, causing more stress on the engine
- Altitute-boosted: Ground power is kept until high altitutde (excess power is avoided by wastegate)

### Critical Engine (ME)

- The one with the downgoing blade on the inside is critical (for clockwise, thats left)
- Everything left is critical: left engine, skid left, yaw left, left crosswind (but NO slip indication)

## 11 - Turbine Engines

### Compression ratios

- Axial flow compressor: ~1.3:1 per stage (totalling in 35:1 to 50:1)
- Centrifugal compressor: 4:1

### Basic gas turbine

- Air intake
- Compressor (increase of pressure, at slightly decreasing velocity)
- Combustion chamber (constant pressure)
- Turbine (decrease of pressure, slight increase in velocity)
- Exhaust (decrease in velocity, for noise abatement)

### Air intake

- Generally slightly divergent
- Optional inlet guide vanes for ideal air flow at first compressor stage
- Velocity decreases, pressure and temperature increase

### Axial Compressor parts

- Rotor: Increase velocity & pressure (converts mech. energy from shaft into kinetic & pressure energy)
- Stator: Increase (static) pressure, reduce velocity & dynamic pressure (converts kinetic energy into pressure energy)

In short: Rotor increases both p & v, stator only p. v is roughly constant after each stator + rotor stage.

### Compressor stall

- Occurs when AoA at compressor rotor is too high (= high RPM, low airflow speed)
- Stall happens in front, air stagnation happens in rear

### Combustion chamber

- Diffuser (divergent) reduces velocity & increases static pressure, for optimal combustion
- Combustion process happens at (theoretically) constant pressure, thus increasing temperature

### Axial turbine types

| Type | Nozzle (fixed part) | Turbine (rotating part) | Principle |
|--|--|--|
| Impulse | v↑ p↓ | v↓ p=const. | U-shaped rotor blades, actio=reactio |
| Reaction | v=const. p=const. | v↑ p↓ (T↓) | wing-shaped rotor blades, aerodynamic forces |

Pressure-related Mnemonics: IDC and RCD (Also note that pressure never rises in the turbine)

### Turboprop and Turbofan/jet turbine

- Turboprop: Kinetic energy (velocity) is converted into mechanical energy (shaft)
- Turbofan/jet: Potential energy (pressure) is converted into kinetic energy (velocity)

- Mnemonics: EPK and EKM

### Active clearance control

- Try to keep minimum distance between blades and outer case
- Distance controlled by cooling air to outer case(!)

### Exhaust system

- Primary purpose: Increasing speed of exhaust gas, for extra thrust
- Secondary purpose: Reduce speed of gas (with divergent section), to reduce noise

Speed increase requires convergent nozzle for subsonic, divergent nozzle for supoersonic gas speeds

### Turboprop power setting ranges

- Alpha: Flight idle to max. power
- Beta: Just below flight idle to max. reverse

### FADEC

- Includes the engine controls and the sensors
- Redundant, to cover failure of a single sensor channel
- In piston engines: Can also control ignition time

### Gearboxes

- Accessory/Auxiliary gearbox: Connected to the HP shaft, lubricated by turbine oil
- Supplemental gearbox: Connected to the LP shaft, own lubrication

## 12 - Protection and Detection Systems

### Rain protection on windscreens

- Chemical or Wipers
- Can be used simultaneously

### Smoke detectors

- Used where only slow airflow is happening (cargo, lavatory, avionics bay, ...)
- Based on ions or light refraction (labyrinth detector)

### Fire detectors

- Usually double-loop systems, as they are more reliable
- Flying with 1 inoperative loop can be considered, if AFM permits
- Gas-filled detectors:
  - Temperature-based, with increase in T the pressure increases, causing the fire warning
  - If broken, outside pressure decreases, causing a fault alert
 - Continous loop fire detectors:
   - With heat, resistance decreases and capacitance increases

### Fire extinguishers per engine

- 1 bottle per engine, with
- 2 discharges per designated fire zone

## 13 - Oxygen Systems

### Hazards

- Can spontaneously catch fire with oil or grease

### Oxygen mask modes

- Normal: O2-concentration same as altitude, on demand
- 100%: 100% O2, on demand
- Emergency: 100% o2, constant delivery

### Oxygen generators/sources

- Gaseous: Can be regulated
- Chemical: Once started, will run until out of fuel. Produces heat during operation

### Important cabin altitudes

- 8000 ft: Warning
- 10000 ft: Alert
- 15000 ft (before): Automatic deployment of masks
