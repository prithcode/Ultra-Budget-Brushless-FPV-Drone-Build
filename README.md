# Ultra-Budget-Brushless-FPV-Drone-Build

A fully documented ultra-budget 1S brushless micro FPV drone build. I focused on keeping the build cheap and simple while learning how to solder, set up a flight controller, configure Betaflight, and troubleshoot problems. The parts are inexpensive and easy to find, so someone else can recreate the build.

## Overview

I built this lightweight 1S brushless micro drone from individual components. My goal was to make an affordable tiny whoop that I could build and learn from without spending a lot of money.

I used the **BETAFPV Matrix 1S 5-in-1 II AIO**. AIO means "all-in-one," since the flight controller, ESCs, receiver, 5.8GHz analog VTX, and OSD are built into one board. This keeps the build small and cuts down on wiring.

I used the **solder-required version** of the AIO, so I had to solder the motor and battery connections myself.

The build and configuration were self-taught. I learned the soldering, assembly, Betaflight setup, and troubleshooting as I went.

The drone itself cost **$88.93**, excluding the radio, charger, batteries, and optional equipment.

---

## Components Used

I chose parts that were simple, affordable, and easy to find so that the build could be recreated by others. The primary drone components were purchased through AliExpress.

### Drone Components

- **Flight Controller & ESC:** BETAFPV Matrix 1S 5-in-1 II AIO, solder-required version, with built-in 5.8GHz analog VTX and OSD, **$54.74**
- **Frame:** Meteor 75 Pro Frame, **$5.56**
- **Motors:** 1103 15,000KV Motors ×4, **$11.40**
- **Propellers:** 45mm Gemfan Propellers, **$2.99**
- **Canopy:** YSIDO Micro Canopy, **$3.24**
- **Camera:** BETAFPV C03 Camera, **$11.00**

### Additional Equipment

- **Radio Controller:** RadioMaster Pocket, **$78.00**
- **Battery:** Ovonic 1S 450mAh LiPo, **$20.00**
- **Charger:** ISDT 1S LiPo Charger, **$22.00**
- **Soldering Iron:** **$11.00**
- **FPV Goggles:** Eachine EV800D, **$114.00**

### Optional / Recommended Tools

- **Screw Assortment Pack:** $3.81
- **Solder Cleaning Ball:** $1.73
- **Heat Shrink Tubing:** $2.00
- **NC559ASM Flux:** $4.51
- **Desoldering Wire:** $1.51
- **Third Hands:** $1.39
- **Cutting Mat:** $1.39

The optional tools were not all required for my build, but several were highly recommended for making assembly and soldering easier.

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

### Minimum to Fly

**$88.93 drone + $78 radio + $20 battery + $22 charger = $208.93**

### Complete Setup

Including the radio, battery, charger, soldering iron, optional tools, and FPV goggles, the total cost of the listed equipment is approximately **$350.27**.

The **$88.93 figure represents the drone itself**, while the additional equipment can be reused for future builds.

---

## Build Process

### 1. Frame Assembly

I assembled the Meteor 75 Pro frame first.

This gave me a base for mounting the motors, AIO, camera, and canopy.

### 2. Motor Installation

I positioned the motors on each arm and secured them before connecting them to the AIO flight controller.

I soldered the motor leads directly to the appropriate motor pads on the Matrix 1S 5-in-1 II AIO.

The motor pads are small, so I had to be careful while soldering to avoid solder bridges or damaging nearby components.

### 3. Soldering

Soldering was one of the main parts of the build.

The primary soldering work consisted of:

- Soldering the four motor leads
- Connecting the battery leads
- Cleaning and checking the soldered connections before powering the drone

The small AIO pads required careful soldering and heat control. After soldering, I used **91% isopropyl alcohol (IPA)** to clean the solder joints and remove flux residue.

### 4. AIO Installation

I installed the BETAFPV Matrix 1S 5-in-1 II AIO into the frame.

The AIO combines the flight controller, ESCs, integrated ELRS receiver, 5.8GHz analog VTX, and OSD into one board. ELRS is the radio receiver system, VTX means "video transmitter," and OSD means "on-screen display."

A **smoke stopper is recommended** when powering the AIO for the first time. It can help detect a short or wiring problem before it causes damage. It is not required, though. I was fine without using one.

### 5. Camera and Canopy Installation

I installed the BETAFPV C03 camera at the front of the drone.

I then installed the YSIDO Micro Canopy to protect and hold the camera in place.

### 6. Final Assembly

After installing the electronics, I checked the remaining hardware and assembled the drone into its final configuration.

The 1S 450mAh battery provides power to the completed system.

I did a final inspection before moving on to software configuration and testing.

---

## Configuration

### 1. Betaflight Setup

I used Betaflight to configure the flight controller and prepare the drone for flight.

I configured the flight controller, receiver, motors, flight modes, and other settings needed for the build.

I also spent a lot of time messing around with different Beta flight settings like PID tuning(would not recomend if ur a beginner !!!!)

### 2. ELRS Receiver Setup

The Matrix 1S 5-in-1 II AIO has a built-in ELRS receiver.

I configured the receiver to communicate with the RadioMaster Pocket.  Use this video: https://www.youtube.com/watch?v=zuUDaiM3TKg

### 3. Motor Configuration

I configured the four motors through Betaflight.

I checked the motor order and direction to make sure each motor matched its correct position on the flight controller.

I tested the motors without propellers installed during configuration.

### 4. Flight Modes

I configured the flight modes in Betaflight for the way I wanted to fly the drone.

### 5. Failsafe and Safety Configuration

I also performed safety checks during configuration and testing like removing props and checking for a burning smell just incase something had been bridged. 

---

## Testing

### 1. Initial Hardware Testing

After finishing the soldering and assembly, I tested the electronics.

I checked the AIO, motors, receiver, and other connected components to make sure everything was working.

I tested the motors without propellers installed before attempting to fly.

### 2. LOS Testing

I am currently testing the drone using **line-of-sight (LOS)** flight. LOS means flying the drone while directly watching it instead of using FPV goggles.

This lets me test the basic flight characteristics before moving to FPV.

### 3. FPV Testing

The BETAFPV C03 camera connects to the AIO's built-in **5.8GHz analog VTX**. The VTX sends the camera's video signal to the Eachine EV800D goggles.

The AIO also has a built-in **OSD**, which can display flight information over the camera feed.

I have the FPV equipment available, but I am currently flying LOS.

---

## Troubleshooting & Optimization

### Problem / What I Did

Make sure you buy the right props and look at their direction...

I spent 2 hours messing around with PID tuning, throttle limits, and motor direction. Just to find out I had a left and a right prop....

I started messing around with the PID settings in Betaflight to see if I could make the drone feel more responsive. I changed a few values without fully understanding how they affected the flight.

After testing the changes, the drone started oscillating and felt unstable in the air. It was clear that my settings weren't working well with the build.

Next time, I would save a backup of my working configuration and change one setting at a time. 

Use this playlist if you want to get into advanced PID tuning: https://www.youtube.com/watch?v=4sjXJ5HoU_c&list=PLwoDb7WF6c8ldO8tz0IUi9FNcJdvE2Mhe
---

## Key Takeaways

This build taught me a lot about building and setting up a small brushless drone.

- **Soldering:** I learned how to solder small motor and battery connections.
- **Brushless Motors:** I learned how the four motors connect to and are controlled by the AIO.
- **Flight Controller:** I learned how to set up and configure the flight controller in Betaflight.
- **ELRS:** I learned how to set up the built-in receiver and connect it to my RadioMaster Pocket.
- **FPV Video:** I learned how the camera, analog VTX, OSD, and goggles work together.
- **Troubleshooting:** I had to diagnose and fix several problems during the build and configuration.

---

## Future Improvements

Possible future improvements include:

- Transitioning from LOS to FPV flight
- Further tuning the Betaflight configuration
- Optimizing flight characteristics
- Testing different propeller configurations
- Experimenting with different 1S batteries
- Adding flight data and test results to the documentation
- Building a larger and more advanced FPV drone

---

## Final Build

The completed project is an **$88.93 1S brushless micro drone** built around the BETAFPV Matrix 1S 5-in-1 II AIO.

I kept the build focused on using inexpensive parts and a simple layout. The result is a small brushless drone that I can use to learn more about soldering, flight controllers, radio systems, FPV video, and Betaflight.
