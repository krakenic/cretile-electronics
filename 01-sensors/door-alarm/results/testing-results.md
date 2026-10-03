# Testing Results

## Door Closed

**Condition:** The door was closed and the Obstacle Sensor detected it.

**Observed Result:** The Sensor Base gave an ON output. The NOT Module inverted it to OFF, so the buzzer did not ring.

## Door Open

**Condition:** The door was opened and the Obstacle Sensor no longer detected the door.

**Observed Result:** The Sensor Base gave an OFF output. The NOT Module inverted it to ON, so the buzzer started ringing.

## Alarm Timing

**Condition:** The door was left open for more than 2 minutes.

**Observed Result:** The buzzer remained ON while the door was open, alerting us that the door had been left open.

## Problems Encountered

* To be honest,
* The Obstacle Sensor needed to be positioned correctly to detect the door.

## Fixes

* Adjusted the position of the Obstacle Sensor.

## Final Result

The Obstacle Sensor successfully detected whether the door was open or closed. The NOT Module inverted the sensor output, allowing the buzzer to remain OFF when the door was closed and turn ON when the door was open.
