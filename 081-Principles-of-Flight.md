# 081 Principles of Flight

## 01 - Subsonic Aerodynamics

### Definitions

- Mean geometric chord: Wing Area / Wing span
- Aspect ratio = wing span / mean geometric chord
- Taper ratio = Tip chord / root chord
- chord line = straight(!) line drawn from leading to trailing edge
- camber line = line from leading to trailing edge, equidistant from upper and lower surface
- sweep angle = angle of lateral axis and quarter-chord line
- Angle of attack (AoA) = angle of chord line and undisturbed airflow
- Angle of inclination (AoI) = angle between longitudonal axis and wing root chord
- Centre of pressure: Point where all lift forces act on (force vector, no moment). Moves forward with increasing AoA
- Aerodynamic centre: Fixed point about 25% from leading edge. If used as reference, then force & moment acts

### Pressure

Total pressure p_t:

- Static pressure p = F / A
- Dynamic pressure q = 0.5 * rho * v^2

According to Bernoulli, the total pressure is constant p_t = p + q = const.

### Two-dimensional airflow around an aerofoil

- In general, thicker wings have higher c_L and C_D for given AoA
- Stagnation Point travels to lower surface with increasing AoA
- Stagnation point is place where ice builds up first
- Transition point: Point where airflow switches from laminar to turbulent at upper wing surface (moves forward with increasing AoA)
- Seperation point: Boundary layer detaches from surface

### Boundary layer

- Area just above the wing surface, influenced by the fluids viscosity flowing over the wing
- Change from laminar to turbulent happens at the transition point
- Laminar: thin layer, smooth airflow, little friction drag
- Turbulent: thicker layer, unsteady airflow, more friction drag (but: less likely to seperate from wing)

### Coefficients

- Lift L = 0.5 * rho * v^2 * c_L * S
- Drag D = 0.5 * rho * v^2 * c_D * S

### Angle of Attack

- Induced angle of attack
  - Increases with decreased speed
  - Caused by upwash/downwash
  - Produces wingtip vortices
- Effective angle of attack
  - Increases with increased speed
  - Produces uplift

### Lift augmentation devices

| Device | c_L for given AoA | c_LMax | Max. AoA |
|--|:--:|:--:|:--:|
| Trailing edge flaps | ↑↑ | ↑↑ | ← |
| Leading edge flaps / slats | ↑ | ↑ | → |
| Spoilers | ↓ | ↓ | → | 

### Three-dimensional airflow around an aeroplane

- Wing-tip vortices are higher with high AoA = slow speed

### Total drag

- Induced drag (caused by lift generation)
  - c_DI = c_L^2 / (pi  * AR)
  - Increases at low speeds & high mass
  - Causes wingtip vortices
- Parasite drag (caused by aircraft moving through the air)
  - Increases at high speeds
  - Subtypes of parasite drag:
    - Pressure/Form drag: pressure diff. between leading and trailing part of aircraft, due to shape
    - Interference drag: caused by connection points of the surfaces
    - Skin friction drag: Caused by the air fluid in the boundary layer
- Tip tanks reduce induced drag but increase parasite drag

### Alteration of the TAS-drag-curve

- Increased Mass: Curve moves up and right (more induced drag, higher v_MD)
- Increased altitude: Curve moves left (higher TAS of v_MD)
- Dirty aircraft: Curve moves up (parasite & induced drag increase)

### Stable and unstable drag regions

- Minimum power speed v_MP: minimum sink rate = longest time to ground (opposite of v_y)
- Minimum drag speed v_MD: minimum descend angle = max range (opposite of v_x)
- Below v_MD, total drag increases with reduced airspeed (unstable region)
- Above v_MD, total drag increases with increased airspeed (stable region)

### Ground effect

- c_L increaes
- c_D decreases (due to less induced drag)
- Downwash decreases
- AoA: Induced AoA decreases, effective AoA increases

### The relationship between lift coefficient and speed in steady, straight, and level flight

c_L ~ v^2

### CLMAX augmentation

- Leading edge flaps:
  - Krueger flaps
  - Variable camber flaps
  - Slats (increase in max AoA and c_D, but c_I will stay the same)
- Trailing edge flaps: (in increasing c_L/c_D ratio)
  - Split flaps
  - Plain flaps
  - Slotted flaps
  - Fowler flaps
- Spoilers / Speed brakes

### Means to reduce the CL–CD ratio

- Spoilers (slight reduce of c_L, high increase of c_D)
- Speed brakes (only increase of c_D)
- Flaps (but due to higher c_L, airplane can fly slower)

### Aerodynamic degradation

- Icing causes an increasing stall speed and reduction of c_LMAX and max. AoA

## 02 - High Speed Aerodynamics

### Relation between speeds

- ECITM on climb: left decreases, right increases
- ECITM on descend: right increases, left decreases

### Compressibility effects

- Compression of air primarily increases its density
- Secondary effects are an increase in temperature and pressure

### Shock waves

Supercritical wing profiles have a weaker shock wave than conventional airfoils

- Bow wave in front of leading edge of wing
- Perpendicular or normal shock wave on upper wing surface

In general, before the shockwave airflow is supersonic, behind its subsonic.

### Forming on shock waves on the wing

- Shockwave builds up on the thickest part of the upper wing, at first.
- On the lower wing, it build later, but stays behind the upper shockwave.
- With increasing Mach, the shockwave moves back.
- Increasing AoA leads to an increase of the shockwave

### Effects of a normal/perpendicular shockwave

- Air temperature increases
- Static pressure increases
- Air density increases
- LSS increases
- Total pressure decreases
- Speed of airflow decreases (to less than Mach 1 for normal shockwave, still above Mach 1 for oblique shockwave)

Mnemonic: DSSS increase (**D**ensity, **S**tatic temp., **S**tatic pressure, Loc. Speed of **S**ound)

### Change in lift and drag above M_crit

- Drag increases up to 0.98 M, then decreases again to normal (subsonic) level
  - The additional drag is called wave drag an a combination of energy drag and boundary layer seperation
- Lift increases from 0.4 M to 0.81 M, then decreases towards 0.89 M then increases (to a lower level) to 0.98 M, then decerases again

Note:
- Drag divergence mach number M_DD is just above M_crit
- For conventional wings, the L/D-ratio is reduced above M_crit, for supercritical wings, it is increased

### Influence on stall speed and c_LMAX

- Above 0.4 M, c_LMAX start to decrease until 1.0 M, then increases again
- Consequently, the stall speed increases 

### Influence of airfoil on M_crit

M_crit can be increased by:

- Smaller leading edge radius
- Smaller thickness to chord ratio
- Smaller camber
- Smaller AoA (due to less acceleration on the top surface)
- Less load and more aft CG on aircraft (due to lesser AoA)
- More swept back wing (due to increase of effective chord)

Think of wings of a fighter jet: Flat, thin, swept, flying at low AoA

## 03 - Stall, Mach Tuck and Upset Prevention and Recovery

### Mach tuck / Tuck-under

- CP moves backward -> Nose-down moment
- Downwash behind the shockwave on wing is reduced -> Reduced AoA on elevator -> Reduced elevator downforce
- AC also moves, from 25 % to 50 %

### Low speed buffeting

- Stages
  - Buffet initiation
  - Buffet onset
  - Deterrent (limiting) buffet

### High speed buffetting

- Should be avoided by all means
- Safety margin of 0.3g is added -> Use 1.3g in graphs

### Anti-Icing Holdover time (HOT)

- Starts at begin of de-icing
- Humidity reduces the HOT

### CP movement during stall

- Straight wing: CP moves back (wing root stalls first)
- Swept-back wing: CP moves forward (wing tip stalls first)

### Stall recovery (acc. EASA)

- Pitch 
- Bank
- Power
- Stabilize (but not to forcefully to avoid entering a secondary stall)

Real life: Pitch Power Bank

### Max. Altitudes

- Aerodynamic ceiling: max. altitude with 1g (coffin corner)
- Service ceiling: 100 ft/min (prop) / 500 ft/min (jet) remaining
- Absolute ceiling: 0 ft/min climb rate

### Limitation of span-wise air movement on wing

- Wing fences on the upper surface
- Vortilons on the lower surface, which cause a vortex to the upper surface only at high AoA 

## 04 - Stability

### Stability in general

- Static: reaction to unintentional pilot action (the "ball in the bowl")
- Dynamic: reaction to oscillation over time

Dynamic stability requires static stability

### Directions

- Longitudonal stability: Pitch
- Lateral stability: Roll
- Directional stability: Yaw

### Dutch roll

- High static lateral (roll) stability
- Low static directional (yaw) stability
- Periodic motion, short-period
- Can be counteracted by Yaw Damper (YD)
- If YD fails, reduce speed and altitude

### Spiral dive

- Low static lateral (roll) stability
- High static directional (yaw) stability
- Aperiodic motion

### Phuygoid

- Long-period oscillations (20 - 100 seconds) in pitch
- Think of a typical paper plane flying

### Sideslip

- Direction defined by bank (and where to look out of the window)
  - Right/positive sideslip: bank right, roll left, airflow from right side
  - Left/negative sideslip: bank left, roll right, airflow from left side

### Static longitudonal stability (pitch)

- Defined by pitching moment coefficient (c_M) over IAS or c_L
- Stable means negative c_M at high IAS/c_L
- Wing is unstable part, Horiz. stabilizer is stable part (as name says)
- Stability is defined by static margin (diff. of CG and neutral point (average of ACs of main wing and stabilizer))
  - CG before NP -> stable
  - CG aft NP -> unstable

### Static directional stability (yaw)

- sewpt-back wings increase static directional stability
- During sideslip, increased by:
  - dorsal fin (upper side of fuselage, before tail fin)
  - ventral fins (lower side of fuselage, below tail fin)
 
### Static lateral stability (roll)

- Increased by larger rudder size
- Increased by dorsal fin
- Reduced by ventral fin

## 05 - Control

### Adverse (aileron) yaw

- Caused by different induced drag of left and right aileron
- Yaw is induced contrary to the desired roll
- Can be counteracted by frise ailerons and asymetrical (low-wing) spoiler movement

### Tab types

| Type | Description | Movement | Stick force | Control effectiveness | 
|--|:--:|:--:|:--:|
| Balance | Directly linked | opposite | less | less |
| Anti-balance | Directly linked | same | more | more |
| Servo | | opposite | less | less |
| Spring | Spring-augmented | opposite | less | less |

### Frise ailerons

- Avoid adverse yaw
- leading-edge of the up-going aileron produces extra drag

### Differential aileron system

- Up-going aileron (on the inner wing) is deflected more
- Can be supported by asymetrical (low-wing) spoiler movement

### Elevator trim vs. horizontal trimmable stabilizer

- HTS allows larger CG range
- HTS has less drag
- HTS requires less force

### Hydroplaning

- Dynamic: Like normal aquaplaning, due to standing water or slush
- Viscous: Water combines with rubber on runway
- Reverted rubber: Blocked tyre heats up, forming a steam pillow between tyre and runway

## 06 - Limitations

### CS-23 load limits

| Category | G- | G+ |
|--|:--:|:--:|
| Normal | -1.9 | 3.8 |
| Utility | -2.2 | 4.4 |
| Aerobatic | -3 | 6.0 |
| Commuter | -1 | 2.5 |
| CS-25 | -1 | 2.5 |

### Design speeds

- v_S or v_S1G: Stall speed for 1g
- v_A: Maneuvering speed (first time reaching max g-load)
- v_B: Max. Gust Intensity Speed / Speed for 66 ft/s gusts
- v_C: Design cruising speed / Speed for 50 ft/s gusts
- v_D: Design diving speed (flight tested) / Speed for 25 ft/s gusts

v_A becomes less relevant for large jet aircraft at high altitudes due to:

- buffet onset limitations
- high stall speeds and low control surfaces make it easier to provide high load factors

### Operational speeds

- v_MO/M_MO: Max. operating speed (less or equal v_C)
- v_RA/M_RA: Max. speed in rough air
- v_NO: Normal operation (not greater than v_C)
- v_NE: Never exceed (0.9 v_D)

v_NE only applies to CS-23 aircraft. v_MO applies to all CS-25 aircraft and a few larger CS-23.

### Flutter 

- Is a self-excited structural oscillation at high speeds
- My be damped by adding weight in front of the hinge

### Gust load factor

- Decreases with increasing altitude
- Decreases with increasing mass
- Decreases with increasing wing loading

## 07 - Propellers

### Terminology

- Contra-rotating: 2 props on one shaft
- Counter-rotating: ME aircraft with propellers in opposite direction

### Left-turning tendencies

- Spiraling slipstream (at start/ground roll)
- Gyroscopic precession (during rotation)
- Asymetric blade effect/P-Factor (for tail-wheel)
- Propeller drag (during flight)

### Propeller angles

- Blade angle: Angle between rotation plane and blade chord
- Angle of attack: Same as for wing
- Angle of advance (helix angle): Like angle of induced AoA for the wing

### Propeller icing

- Main issue is reduced efficiency

### Thrust distribution

- Low at root
- Higher towards the tip
- Falls back to almost zero at the tip

## 08 - Flight Mechanics

### Equations

- Turn radius R = TAS^2 / (g * tan(bank angle))
- Required Thrust: T = D + W * sin(pitch angle)
- Centripetal force F = L * sin(bank angle) = W * tan(bank angle)
- Lift in turn L = W / cos(bank angle)
- Load factor n = L / W
- Rate of turn [rad] = TAS / R = g * tan(bank angle) / TAS

### OEI handing

- High weigth is better for handling due to higher momentum (but worse for performance)
- Critical engine is the one with the down-going blade next to the fuselage
- Wind from the dead engine side is critical for handling
