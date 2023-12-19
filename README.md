
One of the most damaging and significant natural disasters in our nation today
is fire. Fires are intimately tied to human activities and are on the rise each year as a
result of our nation&#39;s economy&#39;s rapid growth and the quick increase in urban
developments. The current fire prevention and control system puts up stricter
requirements begging since the occurrence of fire prevention and control system will
cause material and spiritual harm to people.
There are a number of fire and smoke detection systems are available
nowadays. But all these systems provide a warning signal on the building premises
only. Then the fire detection was done mainly by visual inspection and confirmation
by a human being and the fire station only informed when someone make a call to the
fire station.A real time fire and smoke detection system can solve this issue and
inform nearest fire station. This system is cheaper compared to all currently available
systems in market. This real time fire and smoke detection system is designed to
detect the fire and smoke at the early stage and notify the nearest fire station through a
push notification. The notification contains the fire or smoke warning and the location
information’s.

Circuit Diagram:

![image](https://github.com/VAISHNAVEE24/Project/assets/118464908/cb6f633d-ce98-46bf-962d-d065b9f1bb3e)


Working:

Any fire source can be placed in front of the flame sensor after the code has been
uploaded to the Arduino board.The flame sensor is activated as soon as it notices fire or
flame. Arduino responds to this signal by taking the appropriate action. That could involvethe
buzzer sounding or any other fire-fighting activity.
Here, a buzzer has been connected as a detection tool.This sensing is based on
variables such as temperature, smoke, humidity, etc. These signals may be analogue or digital
in nature. We used the flame sensor&#39;s digital output for this project and connects this output
with Servo motor.Such that when fire is sensed by the flame sensor the servo motor gets
activated and gives a single rotation of 180 degree. Connect the required components, then
upload the programme to the Arduino UNO. Place a lit match or a lit lighter in front of the
flame sensor to check its functionality.
When there is a flame, the LED and Buzzer turn on automatically, and when there is
no flame, the LED and Buzzer turn off automatically.When we place a Flame Near Flame
Sensor, Arduino turns on the LED and Buzzer automatically. When we remove the flame from the flame sensor, Arduino turns off the LED and buzzer.The Flame Sensor produces
HIGH output when things are normal. The sensor&#39;s output turns LOW if it discovers any fire.
The buzzer is turned on by Arduino when it senses this LOW signal on one of its input pins.
This flame sensor has a &quot;logical unit&quot; signal on the digital output when an open flame
appears up to 1 metre away from the IR receiver. Port A1 is used to receive the digital signal
from the flame sensor, but any general-purpose port can be substituted for it in the
sketch.After getting output from flame sensor it is fed to servo motor .If flame is detected by
the sensor,servo motor gets activated and starts rotating at 180 degree .

Experimental Result:

![image](https://github.com/VAISHNAVEE24/Project/assets/118464908/023ecdae-e4d3-44c8-ae68-35e10f6bcbd3)






