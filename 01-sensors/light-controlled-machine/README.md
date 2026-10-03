# Light Controlled Machine

## Overview

My first Cretile electronics project. This project demonstrates how a machine can sense changes in light intensity and use that information to control a motor.

The project contains three activities:

1. Change the direction of a machine using a light sensor
2. Start a machine using a light sensor
3. Stop a machine using a light sensor

## Objective

* Change motor direction using a light sensor
* Start a motor using a light sensor
* Stop a motor using a light sensor
* Understand how machines can sense their environment and respond automatically

## Materials

* Battery
* Wheel
* Motor
* Threshold with Sensor Base
* Light Sensor
* NOT Module

## Key Concepts

* Environmental sensing
* Light intensity
* Thresholds
* Motor control
* Direction control
* Automatic response
* NOT logic

Basic idea:

**Sense → Process → Act**

---

# Activity 1: Change Direction

### Setup

1. Attach the printed machine/gear to the Wheel.
2. Fix the Motor to the Wheel.
3. Connect the Battery module to the Motor's Speed pin.
4. Connect the Threshold with Sensor Base to the Direction pin.
5. Mount the Light Sensor.
6. Set the threshold to **10**.

### Working

* Below the threshold, the machine rotates in one direction.
* When light raises the sensor reading above the threshold, the motor rotates in the opposite direction.

---

# Activity 2: Start the Machine

### Setup

1. Attach the printed machine/gear to the Wheel.
2. Fix the Motor to the Wheel.
3. Connect the Battery module to the Direction pin.
4. Connect the Sensor Base to the Speed pin.
5. Mount the Light Sensor.

### Working

* In dim or no light, the motor remains stopped.
* When light falls on the sensor, the machine starts rotating.

---

# Activity 3: Stop the Machine

### Setup

1. Attach the printed machine/gear to the Wheel.
2. Fix the Motor to the Wheel.
3. Connect the Battery module to the Direction pin.
4. Connect the NOT Module to the Speed pin.
5. Attach the Sensor Base to the NOT Module.
6. Mount the Light Sensor.

### Working

* In dim or no light, the machine rotates.
* When light falls on the sensor, the motor stops.
* The NOT Module reverses the control condition.

---

# Testing & Results

I will record my actual observations after building and testing each activity.

### Activity 1

* Threshold: 10
* Condition: Light intensity was below the threshold of 10.
* Observed Result: The machine rotated in one direction.

* Condition: Light intensity was above the threshold of 10.
* Observed Result: The machine changed and rotated in the opposite direction.

### Activity 2

* Condition: The light sensor was exposed to light.
* Observed Result: The motor started rotating.

* Condition: The light sensor was in dim/no light.
* Observed Result: The motor stopped.

### Activity 3

* Condition: The light sensor was in dim/no light.
* Observed Result: The motor rotated.

* Condition: Light was directed at the sensor.
* Observed Result: The motor stopped.

---

# What I Learned

* Importance of asterisks and hashes in github. **
* Sensors allow machines to respond to their environment.
* Light intensity can be used to control motor behavior.
* Thresholds can trigger different actions.
* Different modules can be combined to create automated behavior.
* A NOT Module can reverse a control condition.

## Problems & Fixes

To be honest,
* Problems: No major problems encountered during testing.
* Fixes: Not required

## Future Improvements

I would like to rebuild this concept using Arduino and eventually experiment with direct sensor readings, motor speed control, data logging, and Python analysis.

## Files

* `images/` - Photos of my builds
* `circuit/` - Circuit/connection diagrams
* `results/` - Testing observations and data
