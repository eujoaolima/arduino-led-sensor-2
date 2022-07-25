# arduino-led-sensor-2

Is another way to create the "arduino-led-sensor".

Here, I made the proximity sensor count from 1 to 1 (same as the other project), but while the counter is between the numbers X and Y it will keep only one led on and, after leaving this condition, it will turn off and turn on another led.

Upon reaching the limit count I selected, the counter will reset.

Exemple:

The led 1 will turn on while the counter is between 1 and 10. When the counter to arrive in 11, he will turn on the led 2 and turn off the led 1 and so on.
When arriving to 30, the counter will reset.
