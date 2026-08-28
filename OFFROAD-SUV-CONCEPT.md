# Classic Off-Road SUV Concept

Status: active concept / iterative build.

## Core idea

A custom classic off-road SUV inspired by a blend of:

- Jeep Cherokee XJ
- Toyota Land Cruiser 70
- Toyota Land Cruiser 80

The goal is not an exact scale replica of any single vehicle. The vehicle should look and behave like a moderately prepared 1980s–1990s off-road SUV, while remaining a custom engineering project.

The general repository philosophy in `PHILOSOPHY.md` applies: LEGO Technic is the primary construction system and interface standard, while custom 3D-printed parts, adapted third-party mechanisms, purchased non-LEGO components, custom ESP32 electronics and modified parts are allowed where they improve the engineering result.

## Fixed constants

At the current stage only two dimensional parameters are frozen. Other vehicle dimensions must be developed around them.

### 1. Wheels

- Wheel/tire set currently selected for the project
- Tire outer diameter: **approximately 62 mm**
- Equivalent diameter in LEGO Technic pitch: **approximately 7.75 pins**
- The wheels are intentionally relatively large for the vehicle, representing an off-road-prepared rather than stock SUV
- These wheels are a project constant and the body is to be proportioned around them

### 2. Track width

- Front track width: **17 pins**
- Metric equivalent: **136 mm**
- Track is measured **between the center planes of the left and right wheels**
- Half-track from the longitudinal vehicle centerline to each wheel center plane: **68 mm / 8.5 pins**
- This value is a project constant for the front suspension geometry

The suspension and hub geometry must be designed to achieve this wheel-center track, rather than defining the track from the outer faces of hubs or other individual parts.

## Current proportion direction — not fixed

The following dimensions are current working targets only. They are useful for proportioning and physical mock-ups, but are explicitly not constants yet:

- Overall length: roughly **45–47 pins**
- Body width: roughly **19 pins**
- Body height: roughly **18–19 pins**
- Wheelbase: roughly **27–28 pins**

A convenient current visual target is approximately **46 × 19 × 18 pins** with a wheelbase around **28 pins**.

These values may change after suspension, chassis and body mock-ups. Only the 62 mm wheel diameter and 17-pin front track are frozen at this stage.

## Suspension architecture

The suspension layout is already chosen at concept level.

### Front

- **Independent front suspension (IFS)**
- Front wheel-center track: **17 pins / 136 mm**
- Exact control-arm geometry, hub/knuckle design, steering geometry, suspension travel, driveshaft solution and spring/damper arrangement will be developed during the build
- The standard LEGO-compatible wheel hub interface may be used where useful, but custom or adapted hub components are allowed under the repository philosophy

### Rear

- **Solid/live rear axle**
- Exact axle housing, differential, locating links, springs, dampers and driveshaft arrangement will be developed later
- Rear track is not yet frozen; it should visually and mechanically match the vehicle once the rear axle is designed

The mixed layout — independent front suspension and a live rear axle — is intentional.

## Design character

The intended visual and mechanical character is:

- classic boxy SUV proportions from the late 1980s/1990s
- stylistic middle ground between Cherokee XJ, Land Cruiser 70 and Land Cruiser 80
- moderate off-road preparation rather than an extreme trophy/trial vehicle
- slightly oversized off-road tires relative to a stock vehicle
- practical ground clearance and visible suspension travel
- engineering function takes priority over strict LEGO purity

## Open design decisions

The following are deliberately left open and should be decided iteratively during prototyping:

- exact body dimensions and final wheelbase
- rear track width
- chassis/frame architecture
- suspension arm dimensions and travel
- steering geometry
- wheel hubs, bearings and knuckles
- drivetrain layout
- RWD / 4WD implementation
- motor type and gearing
- differential design
- transfer case
- rear axle construction
- spring and damper choice
- body construction method
- ESP32 control architecture
- motor drivers
- battery system
- sensors, lighting and telemetry
- which individual parts are LEGO, purchased, modified, adapted from RC mechanisms or custom 3D-printed

The project is intentionally iterative: physical prototypes and CAD experiments should determine the remaining geometry and mechanisms.
