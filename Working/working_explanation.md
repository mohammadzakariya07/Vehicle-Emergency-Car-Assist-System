# ⚙️ Working of Vehicle Emergency Car Assist System

## Normal Condition
- The system continuously monitors the driver’s eye status using an eye blink sensor.
- Ultrasonic sensor measures the distance from obstacles or roadside.
- Vehicle operates normally when eyes are open.

## Emergency Condition (Eyes Not Open)
1. Eye blink sensor detects eyes closed.
2. Left indicator LED turns ON to warn nearby vehicles.
3. Servo motor automatically steers the vehicle toward the left side.
4. Ultrasonic sensor ensures safe movement to the roadside.
5. Once roadside is reached:
   - Motor is stopped using relay
6. GSM module sends an emergency SMS alert to a registered phone number.

## Safety Reset
- System resets all outputs (motor, indicators, buzzer).
- Servo returns to neutral position.
- Vehicle remains in safe state.

This logic ensures accident prevention and timely emergency notification.
