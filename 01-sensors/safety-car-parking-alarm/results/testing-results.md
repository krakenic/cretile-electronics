# Testing Results

## Safe Distance

**Condition:** The car was kept at a safe distance from the wall.

**Observed Result:** The Obstacle Sensor did not detect the car as being too close, so the buzzer remained OFF.

## Warning Distance

**Condition:** The car was moved backwards towards the wall until it reached the adjusted threshold.

**Observed Result:** The Obstacle Sensor detected the nearby wall and the buzzer started ringing.

## Very Close to Wall

**Condition:** The car was moved even closer to the wall.

**Observed Result:** The buzzer continued ringing, warning that the car was too close to the wall.

## Threshold Adjustment

**Condition:** The threshold was adjusted while moving the car backwards.

**Observed Result:** The threshold was set so that the buzzer started ringing at the desired safe parking distance.

## Problems Encountered

- The sensor position needed to be adjusted to detect the wall correctly.
- The threshold needed to be adjusted to get the desired warning distance.

## Fixes

- Adjusted the position of the Obstacle Sensor.
- Adjusted the Sensor Base threshold while testing different distances.

## Final Result

The system successfully warned when the car came too close to the wall. At a safe distance the buzzer remained OFF, and when the car reached the set threshold the buzzer started ringing.
