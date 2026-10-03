
# Door Alarm Using Obstacle Sensor

## Overview

This project uses an Obstacle Sensor to detect whether a door is open or closed and activates a buzzer when the door is left open.

The project demonstrates how sensors and logic modules can be combined to create a simple automatic alarm system.

## Objective

Create an alarm that alerts us when a door is left open.
## Materials

* Battery
* Sensor Base
* Obstacle Sensor
* NOT Module
* Buzzer

## Key Concepts

* Obstacle detection
* ON/OFF sensor output
* NOT logic
* Automatic alarms
* Sensor-based security systems

**Basic idea:** Detect → Invert → Alert

## How It Works

The Obstacle Sensor is mounted on the Sensor Base.

When the door is **closed**, the sensor detects the door as an obstacle:

**Obstacle detected → ON → NOT → OFF → Buzzer OFF**

When the door is **open**, the obstacle is no longer detected:

**No obstacle → OFF → NOT → ON → Buzzer ON**

The buzzer therefore alerts us when the door is open.

## Testing & Results

The actual observations from testing are recorded in [`results/testing-results.md`](results/testing-results.md).

## Problems & Fixes

* Check whether the Obstacle Sensor is correctly aligned with the door.
* Check all Cretile connections if the buzzer does not respond correctly.

## What I Learned

* How an Obstacle Sensor detects objects.
* How a Sensor Base produces ON/OFF output.
* How a NOT Module reverses a signal.
* How sensors can be used to create automatic alarm systems.

## Possible Applications

The same idea can be used for cupboard doors, refrigerator doors, cabinets, drawers, gates, or other situations where knowing whether something is open or closed is useful.

## Future Improvements

* Add a timer to trigger the alarm only after a set period.
* Use a microcontroller such as Arduino for more control.
* Add an indicator LED.
* Record door-open events and their duration.

## Files

* `images/` → Photos of the project
* `circuits/` → Circuits of the project
* `results/` → Testing observations
* `README.md` → Project documentation
