# One Part of a Big Clock #

The project consists of one large clock, to which each student adds a mechanism. This is the documentation for my contribution.

## April 2, 2020 ##

### Theme ###

#### My Theme Ideas ####

##### The Traveller #####
Mechanisms depict what we do when travelling, such as walking with a backpack on, sitting on a train/plane, sipping something in a cafe, taking a photograph of some monument, etc. This would be one clock, perhaps deconstructed (numbers spread out and light up around different form than traditional clock) with twelve mechanisms. Here is one potential mechanism:

![The Traveller Sketch](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/finalProject_travellerTheme_sketch.jpg)

This wilderness backpacker hikes up a hill. Their leggs move left and right and their forearms arms move up and down to simulate walking. This mechanism might work two ways. In one version, the backpacker hikes up the mountain over the entire hour, and when the reach the top a celebratory sound plays. In another version, the backpacker hikes up the mountain, reaches it at the half hour mark, and then hikes down the other side over the second half of the hour.

##### Apocoalypse #####
Mechanisms depict different versions of the end of the world, such as nuclear war, famine, overpopulation, sun flare, etc. This could a similar clock to idea 1, but it could also be a build up at 15 minute intervals to a different cataclysm event every hour.

##### The Orchestra #####
Mechanisms depict different instruments come to life, Beauty-in-the-Beast style.

#### Chosen Theme ####
Self representaiton through hobbies: each student depicts themself through a mechanism depicting a hobby they enjoy.

## April 6, 2020 ##

### Brainstorm ###

To ideate for the chosen theme, I started with a simple word association exercise for each of my current hobbies. From there, I started to imagine different scenes or representations. I decided to try and create a mechanism that that would allow a climber to climb a wall.

![Picture of Word Association](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/hobbyWordAssociation.jpg)

### Movement of the Climber ###
I started with the movement of the climber, independent of the wall. The most basic way to climb is to have the opposite leg move with the the opposite arm, as if one is climbing a ladder.

#### Not-to-scale (NTS) Sketches of Climber Movement ####

![Climber Move 0](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_person_01.jpg)

![Climber Move 1](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_person_02.jpg)

![Climber Move 2](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_person_03.jpg)

The vertical movement of the climber will be driven by a drive shift with four cams, transferring the vertical motion through the wall to the hands and feet of the climber. The drive shaft will be driven by a stepper motor and timing pulley system.

#### NTS Sketch of Climber Movement Mechanism

![Climber Movement Mechanism](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_earlyCamIdea_01.jpg)

(The following sketch clarifies what the figure will actually look like from the side.)

![Climber Side View](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_figure_sideView.jpg)

### Lifting the Climber ###

Version 00 of the mechanism that would lift the climber up the wall included a massive cam, driven by a stepper motor and timing belt system. After some math, however, I realized the dimensions and forces would quickly cause problems. The base would have to be over twice as tall as the height of the wall itself. 

#### NTS Sketch of Cam Lift Mechanism ####
![Climber Lift Cam Mechanism](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_earlyCamIdea_02.jpg)

After yelling at the numbers for longer than I'll ever admit, I realized I could use a pulley. Here is version 01 of the lift mechanism. 

#### NTS Sketches of Pulley Lift Mechanism ####

##### Side View ##### 

(The side view was the last sketch chronologically, and contains the most well-thought-through design.)

![Climber Lift Pulley Mechanism 00 ](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/finalMechanism_sideView.jpg)

##### Front View #####

![Climber Lift Pulley Mechanism 01](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/finalMechanism_frontView.jpg)

##### Back View #####

![Climber Lift Pulley Mechanism 02](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_backView.jpg)

![Climber Lift Pulley Mechanism 03](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/mechanismSketch_details.jpg)

### Fabrication Details ###

Please note these will updated more precisely when dimensions are more finalized.

#### Materials ####
This should be made out of steel, aluminum, and paracord 95.

#### Parts for Each Climber Unit ####

- L-brackets x 28 (and associated nuts and bolts)
- steel cylindrical shafts x 2 (Should I custom make thses so they have built-in washers on one end?)
- stepper motors x 2
- Arduino motor shield x 1
- [paracord 95](https://www.paracordplanet.com/black-95-paracord/) x 10'
- timing pulleys x 4

#### Method ####

5-axis CNC Mill 

### Levels of Activity ###

The system is modular. Ideally, I would like for there to be four climbers. One starts climbing at 00:00. The next starts climing at 00:15, and the next at 00:30, and the last one at 00:45. Each climb would take 15 minutes, and the next climber would start as soon as the last one ends. On the hour, they all fall make to the bottom. However, if only three can be made, than it turns to 20 minutes. With two, the interval would be 30 minutes. If only one, it would take 60 minutes to make the climb.

### Notes/Things to Figure Out ###

- DIMENSIONS!!!!!
- Timing pullleys will have to be used, similar to the setup for the midterm. The width of the mechanism depends upon this.
- The top may be unnecessary, or more supports may be needed to keep the wall/cliff and back panel from falling over.
- The lifting mechanism ahs to be even. This will depend on the way the paracord is attached and the weight of the climber movement mechanism.

## April 19, 2020 ##

### Frame ###
After receiving feedback to use 80/20 aluminum framing (also called t-slotted framing), I modeled the basic structure with 80/20 aluminum framing components. The front and back panel will be modeled to onto the frame with the specialized connectors.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200419_3Dmodel_climbingFrame.JPG)

#### Materials ####

1. [T-slotted Framing Rail](https://www.mcmaster.com/5537t913)
   - 60cm x 4
   - 25cm x 9
2. [T-slotted Framing Corner Bracket](https://www.mcmaster.com/5537t937) x 2
   - Fasteners included with purchase, but no model. I used [these](https://www.mcmaster.com/5537t162) x 4
3. [T-slotted Framing 3-say Outside Corner Bracket](https://www.mcmaster.com/5537t291) x 8
   - Bolts included with purchase, but not model. I used [these](https://www.mcmaster.com/90258a316) x 24

### Climber Figure ###

I also modeled the climber. The overall height is about 3.4cm. The next steps are to create the mechanism which attaches to and moves this one.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200419_3Dmodel_climber.JPG)

#### Concerns ####

1. Material thickness is 8mm arbitrarily. I do not know what is available yet.
2. It is really small. I do not know if the 3D printers are precise enough to print .45 diameter capped pins with .025 tolerance holes.
3. The figure is not an assembly; all the joints are built-in-place.

### Next Steps ###

1. Model the mechanism that moves the climber.
2. Finalize climber size and material thickness.
3. Model the pulley system that lifts the climber and climber-movement mechanism.

## May 3, 2020 ##

### Climber Figure ###

The climber figure has been almost entirely finalized. It has been scaled to 10cm from the original design. It's torso is kept stable by an M3 bolt (all materials listed and linked below)into a stabilizer afixed to the hanging frame, something I realized I needed only after building everything else and trying to move it. After consulting with the ERB workshop, an joint which allowed for assembly after manufacture, rather than manufacture-in-place, seemed to be a better idea. Based on that recommendation, the joints are now snap-fit joints based on the resources provided by my classmate Vince. The figure attaches to the linkages via M2 bolts.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberFigure.JPG)

### Movement Mechanism ###

The movement mechanism starts with a worm gear motor. This is attached via  a shaft coupling to an 8mm shift. On the shaft are 5 thrust bearings and four custom cams, kept at the proper angles my M4 set screws. The box is held together with L-brackets and M3 nuts and bolts. The worm gear is afixed with M4 nuts and bolts. The cam followers are intended to be made from 8mm by 8mm key stock (though they can also be made from 8x8 sheets) and have machined screwd-holes in their ends. They are connected via M3 bolts. A cam guide is afixed to the top of the box with M4 nuts and bolts. All cam holes provide .3mm tolerance. There is an additional guide on the frame that doubles as a stabilizer for the torso of the climber.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climber_movementMechanism.JPG)

### Hanging Frame ###

I started building the frame which the whole mechanism will hang from. On it I added an additional cam guide which doubles as the stabilizer for the climber's torso. It uses the same L-brackets and M3 nuts and bolts. There is a custom plate which is 3mm thick sheet metal, and is afixed with round-headed M3 bolts rather than the flat head, flush fit ones used in the rest of the design.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/climber_hangingFrame.JPG)

### Movement ###

Using movement links, I was able to demo the movement. I don't have screen-recording software.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_0.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_30.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_60.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_90.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_120.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_150.JPG)
![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberMoving_180.JPG)

### Materials ###

Please download the zip file to see the exact dimensions. It is approximately. 11cm x 9.1cm x 28.5cm

- 96686A222 : m3Bolts_flat_flatHead x 45 
- 92095A119 : m3Bolts_round_hex x 3
- 90592A085 : m3Nuts_standard x 40
- 90592A090 : m4Nuts_standard x 8
- 91287A116 : m4Bolts_standard x 4
- 91390A110 : m4setScrew x4
- 92005A236 : m4Bolt_round_philipsHead x 4
- 91800A062 : m2Bolt_flat_flatHead x4
- 92288A230 : key stock x 30.5cm x 3
- 5395T211 : shaftCoupling_8mmsShaft x 1
- 6655K54 : thrustBearings_8mmShaft x 5
- 19155A34 : L-Bracket x 12

## May 4, 2020 ##

### Hanging Frame ###

I finished the hanging frame today, adding L-brackets and eyebolts for the top. These will have wire rope threaded through them. Three eyebolts reduces the risk of tipping the climber-movement mechanism.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200504_hangingFrame.JPG)

### Materials ###

In addition to the May 3 post:

- 3107T41 : m4Eyebolt_12mmShaft x 3
- 91287A116 : m4Nuts_standard x 3
- 19155A38 : L-bracket x 3
- 96686A222 : m3Bolts_flat_flatHead x 8
- 90592A085 : m3Nuts_standard x 8

## May 11 (update through May 14), 2020 ##

### Hanging Frame ###

After building out the larger a frame a bit further and learning how to make loops in wire rope, I realized 3 eyebolts was cumbersome design. With vertical tracts that double as mounts for the limit switches, I shouldn't have to worry about tipping too much. The positioning the eyebolts to not contact that the cam followers also felt cumbersome, so I did a bit of looking around for some sort of center-of-mass tool in Fusion 360. When I found it, I used it to find the center of mass of the entire climber-movement mechanism and positioned a single eyebolt over that point. 
PICTURE OF FRAME WITH SINGLE EYEBOLT

### Movement Mechanisms Plates ###
At some point, I also realized that flush-fitting nuts and bolts into the plates meant that I probably would not be able to get a wrench around them to tighten them. I adjusted the dimensions and holes so everything sits on top now and then double checked that all fasteners can be accessed by an appropriate tool.

PICTURE OF FLUSH-FIT DESIGN

PICTURE OF OUTSIDE DESIGN

### Lifting Mechanism ###
After I had the hanging frame, I built the lifting mechanism based on the same worm-gear design used on the bottom mechanism.An 8mm shaft coupling holds an 8mm shaft to the worm gear. The same botls and nuts are used to afix the worm gear to the side plates. Two shaft collars form the bookends for the wire rope, which will be tied on the outside of the axle and wrap around it between the bookends.

PICTURE SHOWING AXLE + WORM GEAR

In my initial design (see the April 6 sketch), I had the axle running from front to back. However, as I beginning to sketch out and extrude the vertical lifiting guides, I once again realized that I needed to think about how the mechanism might tip. If the wire rope was wrapped between the bookends on an axis running from front-to-back, it would be constantly, if perhaps slightly, pulling the climber-movement mechanisms from front-to-back, with no guides to stop the movement. Luckily I had not pushed too far into the frame, so I took note of this and built the hanging plates for the worm gear and axle on the left and right sides of the frame.

PICTURE OF AXLE LEFT-TO-RIGHT

### The Big Frame ###
Modeling the frame was difficult. Aluminum t-framing might be user-friendly in real life, but its lack of 90-degree corners makes it cumbersome to create assemblies with Fusion 360's joints. I made liberal use of joint origins which were the point of intersection between two edges. The frame consists of four 60cm t-frame rails connected from left-to-right with four 25.1cm t-frame rails and from front-to-back with four 15cm t-frame rails. (Resulting in internal dimesnions of 15 x 25.1 x 60.) These are connected at corners with external, 3-way t-frame corners. A shelf extends out from the front, with a 13cm gap between its supporting rail (another 25.1 t-frame rail) and the lowest front rail. This provides an aesthetic sense of scale that might be otherwise dissonant due to the figure being driven by a mechanism underneath it. The vertical stabilizers are made from four 15cm t-frame rails and two 60cm t-frame rails. When assembled, these will be adjusted from the position pictured to optimize their support of the climber-movement mechanisms's vertical motion. The shelf and vertical stabilizers are connected through t-framing brackets and fasteners.

PICTURE OF BASIC FRAME WITHOUT PANELS

There are five panels, all of 8mm thickness, all attached via t-framing panel hangers. The front two panels serve to aesthetically establish the idea that the climber is ascending *something* rather than nothing. The two side panels provide a base for the worm gear and axle, as well as some space for battery packs. The back panels provides space for the arduino and battery packs. None of the holes for the arduino or battery packs are modeled because I wanted to leave their positioning flexible until final assembly.

PICTURES OF FRAME WITH PANELS FROM MULTIPLE ANGLES

### All Together Now ###

I imported the climber-movement mechanism into the framing/lifting mechanism file to use for reference. Unfortunately, 


### Materials ###

#### Raw ####

I've designed this whole thing assuming I could use 8mm steel, but after looking at my design and talking with my professor and the people who work in the ERB, as well as two of my mentors about what materials are available for manufacturing on campus, I realize that acrylic makes more sense. If I had not assumed 8mm, I might have been able to have the aesthetic I wanted without changing the design. That is a design mistake, and one I will try my best to avoid in the future. Laser cutting acrylic will allow for a shorter production process and will enable me to do precise etchings. The following parts with be laser cut from 8mm acrylic

- flat panels which connect into the larger frame
- sides of the movement mechanism box and hanging frame
- cam followers and linkages
- cams
- cam follower guides

The figurine itself will be made via high-resolution plastic 3D printer. From discussions with the ERB, it seems that the metal 3D printer and 5-axis CNC are not available for use at the moment, hence the shift to the snap joints.

#### Purchasable ####

This a list of all the components used in the model which would not be cut from acrylic or 3D printed.

##### Fasteners #####
90592A085 M3 NUT X 55
96686A222 M3 BOLT X 61
4843T11 EYEBOLT X 1
9059A016 M6 NUT X 1
91287A116 M4 BOLT X 4
92005A236 M4 BOLT X 8
9059A090 M4 NUT X 12
9139A110 SET SCREW X 4
91800A062 M2 BOLT X 4
5537T162 T-SLOTTED FRAMING FASTENER X 24
92949A335 6-32 SCREWS X 4

##### Brackets #####
19155A34 L-BRACKET X 12
19155A38 L-BACKET X 2
5537T309 T-SLOTTED FRAMING HANGER X 12
5537T291 T-SLOTTED FRAMING EXTERNAL CORNER X 8
5537T937 T-SLOTTED FRAMING CORNER BRACKET X 12

##### Other #####
5395T211 SHAFT COUPLING X 2
6655K54 THRUST BALL BEARING X 5
57445K24 SHAFT COLLAR X 2
7090K37 LIMIT SWITCH X 2
8MM SHAFT X 2 (28.55CM, 7.5CM)
12V DC WORMG GEAR X 2
4561T325 WIRE ROPE
3897T31 WIRE ROPE COMPRESSION SLEEVE

### Assembly Process ###


### Reminders to My Future Self ###

- Inquire about material thicknesses early on in the process. Assuming a default dimension is fine when one dimension change rescales everything, but not when you're ten hours in...
- Don't edit the shapes that form the basis for your sketch dimensions. You can easily choose to not extrude them. It's much harder to retrieve a dimension you've unintentionally deleted.
- Whenever you decide how something will fit, proud, flush fit, tight, loose, consider the entire process of connecting the pieces. Consider hand tools, machines, fastener materials, and accessibility for repair. It doesn't matter if all the ugly joinery is hidden if you can't build it in the real world. Your design should be informed by your ability to fabricate.
- You can sketch in 3 dimensions. You don't need an extrusion to have a plane.
- Make a nuts and bolts component. No, don't start sketching your new, shiny component. Make a nuts and bolts component inside it first. Okay, now is this the smallest unit of this component? No? Then make a subcomponent.
- If you find a method that works (I'm looking at you joints.) than don't spend an hours on a new method that causes problems which take another two hours to fix (I'm looking at you rigid groups.).
- Research a new method before you attempt it. Programs have tutorials and certifications for a reason. Work smarter, not harder.
- Break the link with things you import immediately after you import them.

   Describe the changes that you make to your design and why you make them
    Discuss the various things you learned on the way.
    Discuss the difficulties you ran into, and how you resolved them
    Discuss how you decided which piece to fabricate by 3D printing, which pieces to fabricate by cutting with the laser cutter, and any other tools
    Discuss how your mechanism will be assembled
    Discuss what other components or materials you will need when the project is assembled
    Discuss any remaining problems or concerns
