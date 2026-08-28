# Classic Off-Road SUV Concept

Status: concept / parameters may evolve during the build.

## Core idea

A custom classic off-road SUV inspired by a blend of:

- Jeep Cherokee XJ
- Toyota Land Cruiser 70
- Toyota Land Cruiser 80

The goal is not to build an exact scale replica of any single vehicle. The project should keep the proportions and character of a classic 1980s–1990s off-road SUV while remaining a custom engineering build.

The general repository philosophy from `PHILOSOPHY.md` applies: LEGO Technic is the primary construction system and interface standard, but custom 3D-printed parts, adapted third-party mechanisms, purchased non-LEGO components, custom electronics, and modified parts are allowed where they improve the engineering result.

## Fixed wheel basis

The wheel size is the main dimensional constant for the project.

- Wheel diameter: **62 mm**
- LEGO Technic equivalent: **7.75 pins** in diameter
- Target visual interpretation: approximately **33-inch off-road tires** on a real vehicle
- Approximate resulting scale: **1:13.5**

All body dimensions should be derived from this wheel size rather than choosing the body first and fitting the wheels afterward.

## Preliminary vehicle dimensions

Target dimensions for the custom SUV:

- Overall length: **about 42 pins** (~336 mm)
- Body width: **about 17 pins** (~136 mm)
- Body height: **about 17 pins** (~136 mm), subject to body development
- Wheelbase: **about 25 pins** (~200 mm)
- Track width: **about 14–15 pins** measured approximately between wheel centers; exact value remains to be determined by suspension and hub geometry
- Main-frame ground clearance target: **about 3 pins**
- Clearance below the rear differential housing will naturally be lower, approximately **1.5–2 pins**, depending on the final axle design

These numbers are a starting geometry, not immutable final dimensions. The wheel diameter is the important constant; the remaining dimensions may be adjusted during prototyping.

## Suspension architecture

The suspension layout is already chosen at the concept level.

### Front

- **Independent front suspension (IFS)**
- Exact geometry, control-arm layout, hubs, steering and driveshaft solution will be developed during the build

### Rear

- **Solid/live rear axle**
- Exact locating links, springs, shocks, differential and axle housing design will be developed later

This mixed layout is intentional: independent suspension at the front and a live axle at the rear.

## Open design decisions

The following are deliberately not fixed yet and should be developed iteratively during the project:

- drivetrain layout
- RWD / 4WD implementation
- motor type and gearing
- differential design
- transfer case
- steering mechanism
- suspension travel
- spring and damper choice
- wheel hubs and bearings
- chassis architecture
- body construction method
- ESP32 control architecture
- motor drivers
- battery system
- sensors, lighting and telemetry
- use of LEGO, printed, modified or purchased parts for each individual subsystem

The project should remain flexible: decisions are to be made as physical prototypes reveal what works best.
