# Arduino-Based-Rodin-Coil-Winding-Machine

![image](https://user-images.githubusercontent.com/19898602/145055250-797a65b8-e0bc-43c4-9549-a4c74f060982.png)


If you need some copper wire Rodin-coiled, you could always spend hours doing it by hand. Alternatively, you could use some basic components, and an Arduino Nano to have a machine do it for you.

What is there not to like? But first, you will need some parts and equipment before you get stuck in. 

# parts needed

> Arduino Nano

> NEMA 17 stepper motor

> A4988-stepper motor driver module

> Nextion 2.8" HMI LCD screen

> 6mm acrylic sheet (clear)

> 1/2 inch (12 mm) thick plywood or MDF board

> 23/32 x 23/32 inch (20 x 20 mm) Aluminum Extrusion bar

> 23/32 by 1 and 37/64 inch (20 x 40 mm) Aluminum Extrusion bar

> 23/32 inch (20mm) steel rod

> Custom PCB board (or just use a sandwich board and connector wiring). 

> 5/16 inch (8mm) flange bearing

> 13/64 inch (5mm) threaded rods

> Various 3D parts (models here)

> Custom PCB board


# Make the basic frame

The first step is to make the basic frame for the Rodin coil winding machine. To do this, grab your extrusion roads, measure, and cut down to size. Measure 4 equal lengths of 20 cm (7 and 7/8 inches) and cut using a table saw or hack saw.


![image](https://user-images.githubusercontent.com/19898602/145055711-e3fe404e-1bb9-4bf9-920e-6aa4b2691a92.png)


Using your brackets, build the basic frame as shown below. 

![image](https://user-images.githubusercontent.com/19898602/145055742-6873075f-3afe-4a39-b720-6e76aee459d5.png)


Now, grab the two double thickness extrusion bars, and secure these to the frame also using brackets. 

![image](https://user-images.githubusercontent.com/19898602/145055768-23f6238d-c866-4cbe-93aa-443c561808f7.png)


# Create the Rodin winder mounting wheel

Now grab your plywood, or MDF, and cut out a suitably sized square piece large enough for the diameter of the Rodin winder wheel. Mark out the center, and draw a circle using a pair of compasses. 

![image](https://user-images.githubusercontent.com/19898602/145055832-54c71d59-a44f-4bca-9b84-65159ed12d83.png)


Using a protractor, mark out intervals every 4 cm (1.5 inch) along its circumference for the positions of the Rodin winder. You will want 16 points in total. 

![image](https://user-images.githubusercontent.com/19898602/145055856-df53b786-4803-41a2-bd9b-f5ed1c1b349b.png)


Cut out the wheel using a jigsaw, and clean up the cut edges as needed. Drill a hole through the very center, and also drill holes through each of the points around the wheel's perimeter. 

If needed, mount the wheel in a lathe, and trim down the edges to the required dimensions. 

![image](https://user-images.githubusercontent.com/19898602/145055894-9a142956-91f8-4d12-b035-642a630f4265.png)

# Make the mounting for the wheel

Take your steel rod, and mark out a length of about 2 and 6 cm (23/64 inches). Cut the length off using a Dremel or hacksaw. Secure the length into your mini lathe and machine an axle to hold the Rodin coiling wheel.

Drill a hole through the center of the axle as well the same diameter as the NEMA stepper motor's axle. Next, turn the length of the axle around, and cut off the rest of the full diameter section of the rod to leave a flange roughly 5 mm (13/64 inches) deep. 

Machine the cut end flat, and then drill two holes across the full diameter, as shown. 
![image](https://user-images.githubusercontent.com/19898602/145055963-9148dc7e-943c-4cb2-9a6e-66a816af8971.png)


Insert your mounting axle into the center of the wheel and then secure both to the axle of the stepper motor. 
 
![image](https://user-images.githubusercontent.com/19898602/145056026-deacbf94-22aa-45d0-9562-124f0c5e500a.png)

Next, extend the holes from the wheel mounting axle into the wheel and bolt them firmly together. 

# Make the perspex stepper motor mounting plate

Next, grab your clear perspex, and measure out a length of 5 and 14 cm (33/64 inches) by 1 and 5 cm (31/32 inches). Cut out using your jigsaw.

Find the center of the piece, and mark out the mounting screw points for the NEMA stepper motor mounting points, as well as, four corner screw holes. Drill the holes, and cut another larger hole in the middle.

![image](https://user-images.githubusercontent.com/19898602/145056131-d622e554-c347-4e8d-b8c8-6576d4eaf0ea.png)

Mount the piece of fashioned perspex to the top of the double-width extruded rods on your previously completed frame. 


![image](https://user-images.githubusercontent.com/19898602/145056166-17a47589-9087-405d-96c4-b5e03795da76.png)

Next, mount the stepper motor to the perspex plate using suitably sized nuts and bolts. 


# Complete the wheel

Now, grab 12 number, 1 and 4 cm (37/64 inch) long bolts the same diameter as the perimeter holes on your Rodin winding wheel. Secure them into the holes using washers and bolts. 

![image](https://user-images.githubusercontent.com/19898602/145056233-6dceb9b0-8dfb-449a-b6a9-b99f3be1a71c.png)

Next, add a length of shrink-wrapping to each of the bolt teeth on the wheel. Use a hairdryer to heat shrink them into place, if needed.

Secure the wheel to the stepper motor mounting on the mainframe. 

![image](https://user-images.githubusercontent.com/19898602/145056286-e88a6e09-ebbf-4540-987e-473305d33af8.png)

# Make the main winding mechanism

Now, take two lengths of 8 mm (5/16 inch) steel rods and 4 flange mounts. Secure the mounts to the frame as shown below. 

![image](https://user-images.githubusercontent.com/19898602/145056349-810f6ab6-4ee2-4289-9c75-8568d49e52c8.png)


Next, grab another piece of perspex and CNC machine two end plates to mount the second stepper motor and hold the threaded rod that will be controlled by the stepper motor in place on the frame. 

Mount the stepper motor to its perspex mounting. Now, feed the threaded rod through the perspex endplate, and secure it in place to the second stepper motor. 



![image](https://user-images.githubusercontent.com/19898602/145056408-8b413ce9-9645-474d-83d4-1a7a558f6730.png)


Next, grab more perspex, nuts and bolts, steel rods, flanges, and your third stepper motor, and build the main winding head. No dimensions are given for any of the elements, so you will need to play it by ear when building the below. 

# Build the wire feeder and guiding stylus

Next grab an old ballpoint pen, a length of a narrow hollow cylinder, plastic tubing, and acrylic block, and make the main Rodin wire feeding nozzle as shown below. This will be used to feed and guide the wire around the pegs on the main wheel. 

![image](https://user-images.githubusercontent.com/19898602/145056533-42051ea8-107c-48b8-8060-c30dcd9c784a.png)


Next, secure the acrylic block to the top plate of the winding head, and also fashion a cushioned wire feeder using some washers and felt pads. 

With that, the main mechanical parts are now complete. 


# Build the PCB

![FTQFHXZKLBNXU2X](https://user-images.githubusercontent.com/19898602/123725479-bd305280-d8ab-11eb-8709-c680e91e1300.jpg)
![MVI_0001_2 mp4 00_06_55_14 Still001](https://user-images.githubusercontent.com/19898602/123725534-d5a06d00-d8ab-11eb-9645-d2a05880e79a.jpg)
![MVI_0001_2 mp4 00_07_11_00 Still002](https://user-images.githubusercontent.com/19898602/123725542-d933f400-d8ab-11eb-9a7f-d88351d6a952.jpg)

I designe this multipurpose PCB Those who ever worked with arduino they know the pain of connecting multiple components to the arduino for there projects. so here is the answer for you all.

Not only 2 or 3 you can connect 11 components at same time & on board 5V & 9V regulator,

cross polarity protection, power indication LED,

motor power selection provision (5V or 9V or 12V) manual provision for stepper motor microstepping setting.

Wide range of input supply (9V to 24V). This is my multipurpose PCB works with Arduino Nano, I have designed it in a way that you can run 2 Stepper motors, 2 DC motors, 2 Servo motors at same time and this is not it you can even connect BT module, rotary encoder, I2C device, potentiometer at same time.

This PCB is very much helpful in building any project and no need to worry about messy wire connections.

![image](https://user-images.githubusercontent.com/19898602/123725769-50698800-d8ac-11eb-83b0-fbdab6a23ec1.png)
![image](https://user-images.githubusercontent.com/19898602/123725784-5a8b8680-d8ac-11eb-9a51-bb9042d974ec.png)


He we first see the overview of PCB means what is this PCB capable of and which components you can connect to the PCB.

# List of the Components you can connect to the PCB

> 2 DC motor ( 9V to 24V DC)

> 2 Potentiometer

> 2 Servo motors ( 5V to 9V DC)

> 1 Serial device (BT module, HMI, Communication module, RX, TX)

> 1 Encoder (2 interrupt pin & 1 PB pin)

> 1 I2C device (SCL/SDA Device, display, MPU6050 etc)

> 2 Stepper motors


# Special features of PCB

> Wide range of power input 9V to 24V DC

> Cross polarity protection

> DC motor voltage selection 9V or 12 V DC

> Servo motor voltage selection 5V or 9V DC

> Manual microstepping setting for stepper motor

> Power indication LED

> L298N IC for heavier DC motor

> ON board 5V and 9V regulator no need to arrange different power sources

> Header pins and screw terminals for easy connections




I have designe this PCB and order it from [JLCPCB.com](https://jlcpcb.com/IAT)

I always prefer [JLCPCB.com](https://jlcpcb.com/IAT) for my PCB needs, [JLCPCB.com](https://jlcpcb.com/IAT) have best deals for their customers
$2 for 1-4 Layer PCBs, free SMT assembly monthly.


If new user signup today from this link [JLCPCB](https://jlcpcb.com/IAT ) you will get 27$ coupon from [JLCPCB](https://jlcpcb.com/IAT ).


[Click here to visit JLCPCB.com](https://jlcpcb.com/IAT)




Next, grab the LCD screen, and mount it within its 3D printed housing. Feed the wires through the back, and wire to the main PCB as needed. 

Mount the PCB to the rear of the double-width extruder rod section of the frame. Mount the LCD screen to the frame using a regular metal bracket. 


![image](https://user-images.githubusercontent.com/19898602/145056886-0933bf0a-c203-49db-a8d1-2c289bb80e34.png)
![image](https://user-images.githubusercontent.com/19898602/145056908-93bb9ad0-9ea9-485a-8bba-4978e0d6bdd8.png)


Secure the free end of the wire to one of the pegs on the winding wheel in preparation for the winding process. 

![image](https://user-images.githubusercontent.com/19898602/145056982-249acfc4-949a-4699-b044-6608c9e3412d.png)


Lastly, power up the electronics, enter the settings required and let the winding machine do its thing. Now all that is left to do, is sit back and enjoy the rewards of your labor.







