# March 19, 2024
## Ladybug
### Components
#### Ultrasonic sensors and camera
Last session, I ended up with this for the chassis of the Ladybug :

<div align="center">
    <img src="src/session_13/chassis5.png" width="500px">

    Chassis of the Ladybug
</div>

Today, I will continue to work on how the sensors will be placed on the chassis. I will start with the ultrasonic sensors and the camera. Because I want the robot to be as compact and as light as possible, I had the idea to use the servo motor as a support for the sensors. This way, I can use a small piece to attach the sensor to the servo. The bracket clips onto the servo motor. Here is the result :

<div align="center">
    <img src="src/session_13/support.png" width="500px">

    The support for the sensors (Front view)
</div>
<div align="center">
    <img src="src/session_13/support2.png" width="500px">

    The support for the sensors (Back view)
</div>
<div align="center">
    <img src="src/session_13/support3.png" width="500px">

    The support for the sensors (Bottom view)
</div>
<div align="center">
    <img src="src/session_13/support4.png" width="500px">

    The support for the sensors mounted on the servo motor
</div>

Now, I can screw the ultrasonic sensor and the camera on the support.

<div align="center">
    <img src="src/session_13/sensors.png" width="500px">

    The ultrasonic sensors and the camera mounted on the support
</div>

#### Battery, Raspberry Pi pico W and BMS
The rest of the components are directly placed on the chassis.

<div align="center">
    <img src="src/session_13/components.png" width="500px">

    The battery, the Raspberry Pi pico W, the BMS (Battery Management System) on the chassis (Front view)
</div>
<div align="center">
    <img src="src/session_13/components2.png" width="500px">

    The battery, the Raspberry Pi pico W, the BMS (Battery Management System) on the chassis (Back view)
</div>

#### DWM1001-DEV module
The DWM1001-DEV module is a bit particular because it has to be placed on the top of the robot, in the center, **vertically**. I had to design a specific support for it which is screwed on the chassis. The support is very simple, it is just an extruded T shape, held by to screws to the chassis. Here is the result :

<div align="center">
    <img src="src/session_13/T shape.png" width="500px">

    The support for the DWM1001-DEV module
</div>
<div align="center">
    <img src="src/session_13/T shape2.png" width="500px">

    The support for the DWM1001-DEV module mounted on the chassis
</div>
<div align="center">
    <img src="src/session_13/T shape3.png" width="500px">

    The DWM1001-DEV module mounted on the support
</div>

### Actuator
The goal of the ladybug is to pollinate the plants we placed with the main robot. According to the rules of the competition, a plant is pollinated when the ladybug touches it. To do so, I will use a small servo motor to move a kind of arm. The arm will be placed on the front of the robot. Here is the result :

<div align="center">
    <img src="src/session_13/actuator.png" width="500px">

    The servo motor placed under the ladybug in the chassis
</div>
<div align="center">
    <img src="src/session_13/actuator2.png" width="500px">

    The arm of the actuator mounted on the servo motor
</div>
<div align="center">
    <img src="src/session_13/actuator3.png" width="500px">

    The actuator (Front view)
</div>

### Emergency stop button
The last component I had to place on the chassis is the emergency stop button. I placed it on the top of the robot, between the ultrasonic sensors so it is very accessible by the referee in case of emergency. Here is the result :

<div align="center">
    <img src="src/session_13/button.png" width="500px">

    The emergency stop button mounted on the chassis
</div>

### Fabrication
Now that the ladybug is fully designed, I can start the fabrication. All the grey parts on the pictures above will be 3D printed because this process is quick and easy. 3D printing also has the advantage of being quite precise, afordable compared to CNC machining and it allows to create complex shapes (like the chassis). Because my design is experimental, 3D printing is the best option to test and iterate quickly.

## Next session
- Print the parts
- Adjust some parts of the main robot