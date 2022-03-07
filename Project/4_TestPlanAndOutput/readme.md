# TEST PLAN AND OUTPUT
Test plan is created and verified on both manually as well as Automative.

## High level Test Plan
|Test ID|Description|Input|Expected output|Actual Output|
|:------:|:-----:|:------:|:----------:|:------------:|
|01|Arduino|Data from MCFS|operate at 5V and have a maximum current draw of 40mA.|✓|
|02|resistor|flowing of current|to control current|✓|
|03|Ultrasonic Sensor|Data from Microcontroller|Detect Obstacle upto 4m|✓|
|04|Level Sesnor|Data from Microcontroller|Give signal when Tanks gets full|✓|
|05|LED|giving power|To glow|✓|
_____________________________________________________________________
## Low level Test Plan
| Test ID (for LED)| Description | Input | Expected output | Actual Output | passed/not |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for LED_Char() | N  | N |  N | ✓ |
| 02 | Check for LED_String() | automation | automation |  automation | ✓ |
| 03 | Check for LED_String() | Home | Home | Home | ✓ |
