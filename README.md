# Ultra-Budget-Brushless-FPV-Drone-Build


A fully documented ultra-budget 1S brushless micro FPV drone build focused on learning UAV electronics, embedded systems, soldering, flight-controller configuration, and troubleshooting. The build uses inexpensive and readily available components so that it can be recreated by others.

## Overview

This project involves building a lightweight 1S brushless micro drone from individual components. The goal was to create an affordable platform for learning about brushless motors, electronic speed controllers, flight controllers, radio communication, soldering, and flight-control software.

The drone was designed around the **BETAFPV Matrix 1S 5-in-1 II AIO**, which combines the flight controller, ESC, receiver, and other electronics into a single board. This keeps the build compact and reduces the number of individual components required.

The entire build and configuration process was self-taught, including soldering, hardware assembly, Betaflight configuration, and troubleshooting.

The drone itself cost **$88.93**, excluding the radio, charger, batteries, and optional equipment.

---

## Components Used

The components were intentionally selected to be simple, affordable, and easy to source so that the build could be recreated by others. The primary drone components were purchased through AliExpress.

### Drone Components

- **Flight Controller & ESC:** BETAFPV Matrix 1S 5-in-1 II AIO — **$54.74**
- **Frame:** Meteor 75 Pro Frame — **$5.56**
- **Motors:** 1103 15,000KV Motors ×4 — **$11.40**
- **Propellers:** 45mm Gemfan Propellers — **$2.99**
- **Canopy:** YSIDO Micro Canopy — **$3.24**
- **Camera:** BETAFPV C03 Camera — **$11.00**

### Additional Equipment

- **Radio Controller:** RadioMaster Pocket — **$78.00**
- **Battery:** Ovonic 1S 450mAh LiPo — **$20.00**
- **Charger:** ISDT 1S LiPo Charger — **$22.00**
- **Soldering Iron:** **$11.00**
- **FPV Goggles:** Eachine EV800D — **$114.00**

### Optional / Recommended Tools

- **Screw Assortment Pack:** $3.81
- **Solder Cleaning Ball:** $1.73
- **Heat Shrink Tubing:** $2.00
- **NC559ASM Solder Paste:** $4.51
- **Desoldering Wire:** $1.51
- **Third Hands:** $1.39
- **Cutting Mat:** $1.39

The optional tools were not all required for the build, but several were highly recommended for making assembly and soldering easier.

---

## Cost

### Drone Cost

The cost of the drone itself was **$88.93**.

| Component | Cost |
|---|---:|
| Matrix 1S 5-in-1 II AIO | $54.74 |
| Meteor 75 Pro Frame | $5.56 |
| 1103 15,000KV Motors ×4 | $11.40 |
| 45mm Gemfan Props | $2.99 |
| YSIDO Micro Canopy | $3.24 |
| BETAFPV C03 Camera | $11.00 |
| **Total** | **$88.93** |

### Complete Setup

Including the radio, battery, charger, soldering iron, optional tools, and FPV goggles, the total cost of the listed equipment is approximately **$350.27**.

The **$88.93 figure represents the drone itself**, while the additional equipment can be reused for future builds.

---

## Build Process

### 1. Frame Assembly

The Meteor 75 Pro frame was used as the foundation of the build.

The frame was assembled first to provide a lightweight structure for mounting the motors, AIO flight controller, camera, and canopy.

The compact frame was selected to keep the overall weight low while providing enough space for the electronics required for the build.

### 2. Motor Installation

Four 1103 15,000KV brushless motors were installed onto the frame.

The motors were positioned on each arm and secured before connecting them to the AIO flight controller.

Motor leads were soldered directly to the appropriate motor pads on the Matrix 1S 5-in-1 II AIO.

Because the motor connections are small, careful soldering was required to avoid creating solder bridges or damaging nearby components.

### 3. Soldering

Soldering was one of the main hands-on parts of the build.

The primary soldering work consisted of:

- Soldering the four motor leads
- Connecting the battery leads
- Inspecting solder joints for shorts and weak connections
- Cleaning and checking the soldered connections before powering the drone

The small size of the AIO and motor pads required precision and careful heat control.

### 4. AIO Installation

The BETAFPV Matrix 1S 5-in-1 II AIO was installed into the frame.

The AIO combines several components into a single board, including the flight controller, ESCs, and integrated ELRS receiver. This significantly reduces wiring and saves space compared with using separate components.

After installation, the board was checked to make sure there were no obvious shorts or damaged connections before applying power.

### 5. Camera and Canopy Installation

The BETAFPV C03 camera was installed at the front of the drone.

The YSIDO Micro Canopy was then installed to protect and hold the camera in place.

The camera connects directly into the AIO, making the video system relatively simple to install. The system is also compatible with analog FPV goggles.

The drone is currently being tested in **line-of-sight (LOS)** flight, with FPV goggles available for future FPV flying.

### 6. Final Assembly

After the electronics were installed, the remaining hardware was checked and the drone was assembled into its final configuration.

The 1S 450mAh battery provides power to the completed system.

A final inspection was performed before moving on to software configuration and testing.

---

## Configuration

### 1. Betaflight Setup

Betaflight was used to configure the flight controller and prepare the drone for flight.

The configuration process involved setting up the flight controller, receiver, motors, flight modes, and other parameters required for safe operation.

A significant portion of the project involved learning how the different Betaflight settings affected the behavior of the drone.

### 2. ELRS Receiver Setup

The Matrix 1S 5-in-1 II AIO includes an integrated ELRS receiver.

The receiver was configured to communicate with the RadioMaster Pocket.

The radio system provides the control link between the pilot and the flight controller while keeping the electronics compact.

### 3. Motor Configuration

The four motors were configured through Betaflight.

Motor order and direction were checked to ensure that each motor corresponded to the correct position on the flight controller.

Motor testing was performed without propellers installed to reduce the risk of accidental movement during configuration.

### 4. Flight Modes

Flight modes were configured in Betaflight according to the desired control setup.

The configuration allows the drone to be tested and flown while providing the appropriate flight-control behavior for the build.

### 5. Failsafe and Safety Configuration

Failsafe settings were configured to help prevent the drone from continuing to operate if the radio connection is lost.

Safety checks were also performed during configuration and testing.

---

## Testing

### 1. Initial Hardware Testing

Initial testing was performed after completing the soldering and assembly.

The electronics were checked to verify that the AIO, motors, receiver, and other connected components were functioning correctly.

Motor testing was performed without propellers installed before attempting flight.

### 2. LOS Testing

The first stage of flight testing is being performed using **line-of-sight (LOS)** flight.

This provides a way to verify the drone's basic flight characteristics before transitioning to FPV.

LOS testing also provides an opportunity to identify configuration or hardware problems without relying on the FPV video system.

### 3. FPV Testing

The BETAFPV C03 camera and analog video system are ready for FPV operation.

The Eachine EV800D goggles can be connected to the drone's analog video system when transitioning from LOS to FPV flight.

FPV testing will be documented separately after it has been completed.

---

## Troubleshooting & Optimization

This section documents the problems encountered during the build and the solutions used to resolve them.

### Problems Encountered

*To be documented as the build is tested.*

### Solutions

*To be documented alongside each problem.*

### Optimization

*Betaflight configuration, flight performance changes, and other optimizations will be documented here.*

---

## Key Takeaways

This build provided hands-on experience with several areas of UAV and electrical engineering.

- **Soldering:** Working with small electronics pads and motor connections required precision and careful soldering technique.
- **Brushless Motors:** Installing and configuring four high-KV brushless motors provided practical experience with small-scale brushless propulsion systems.
- **Flight Controllers:** The AIO introduced the process of configuring a flight controller and integrated ESC system.
- **Embedded Systems:** Betaflight provided practical experience configuring an embedded flight-control system.
- **Radio Communication:** Setting up the integrated ELRS receiver and RadioMaster Pocket provided experience with modern RC communication systems.
- **Troubleshooting:** Diagnosing hardware and configuration problems was an important part of the project.
- **System Integration:** The project required multiple independent components to work together as one functioning system.

---

## Future Improvements

Possible future improvements to the project include:

- Transitioning from LOS to FPV flight
- Further tuning the Betaflight configuration
- Optimizing flight characteristics
- Testing different propeller configurations
- Experimenting with different 1S batteries
- Improving the documentation with flight data and test results
- Building a larger and more advanced FPV drone

---

## Final Build

The completed project is an **$88.93 1S brushless micro drone** built around the BETAFPV Matrix 1S 5-in-1 II AIO.

The project demonstrates how a functional brushless drone can be built at relatively low cost while providing hands-on experience with soldering, electronics, embedded systems, radio communication, flight controllers, and software configuration.

The build is designed to be reproducible, with inexpensive components and a straightforward architecture that makes it suitable as an introduction to FPV drone electronics and UAV engineering.
