# Car Parking Reverse Safety Alarm

## Overview

This project creates a simple parking safety alarm that warns the driver when a car gets too close to a wall while reversing.

An Obstacle Sensor detects the wall and activates a buzzer when the car reaches the set safety distance.

## Objective

Create an alarm that rings when a car comes too close to the wall while parking.

## Materials

- Power / Battery
- Sensor Base with Threshold
- Obstacle Sensor
- Buzzer
- 5 mm Sunboard / Cardboard
- Double-sided tape

## Key Concepts

- Obstacle detection
- Distance-based sensing
- Threshold adjustment
- Automatic warning systems
- Safe parking

**Basic idea:** Detect → Compare → Alert

## How It Works

The Obstacle Sensor is fixed to the rear side of the parking space and detects the wall.

The Sensor Base with Threshold is adjusted so that the buzzer only activates when the car gets too close to the wall.

**Safe distance → No alarm**

**Too close to wall → Obstacle detected → Buzzer ON**

This gives the driver a warning while reversing and helps prevent the car from getting too close to the wall.

## Testing & Results

The actual observations from testing are recorded in [`results/testing-results.md`](results/testing-results.md).

## Problems & Fixes

- The sensor position may need adjustment to detect the wall correctly.
- The threshold needs to be adjusted to make the alarm activate at the desired distance.
- Check the connections if the buzzer does not respond correctly.

## What I Learned

- How an Obstacle Sensor can be used for parking assistance.
- How a threshold can be adjusted to set a warning point.
- How sensors can provide automatic safety alerts.
- How a simple sensor system can be applied to a real-world problem.

## Possible Applications

The same concept can be used for garage parking, reverse parking systems, automatic gates, or other situations where detecting a nearby obstacle is useful.

## Future Improvements

- Use multiple sensors to detect obstacles from different directions.
- Use Arduino to measure and display distance.
- Add LEDs for different warning levels.
- Add a display showing the approximate distance from the obstacle.

## Files

- `images/` → Photos of the project
- `results/` → Testing observations
- `README.md` → Project documentation
