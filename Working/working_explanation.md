# Working Explanation

The automated vehicle control system continuously monitors the environment and driver input.

## Step-by-Step Operation

1. The system initializes all sensors and actuators.
2. The ultrasonic sensor measures the distance of nearby objects.
3. If an obstacle is detected within 10 cm:
   - The servo motor adjusts steering direction.
4. When an eye blink is detected:
   - LED blinks as a visual alert.
   - Buzzer sounds as a warning.
   - Relay toggles to control the motor/load.
5. If the eye sensor detects a LOW signal:
   - The system resets immediately for safety.
6. Servo returns to neutral position after reset.

This ensures safe and controlled vehicle operation.
