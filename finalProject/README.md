# One Part of a Big Clock #

This project consists of one large clock, to which each student adds a mechanism.

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

The climber figure has been almost entirely finalized. It has been scaled to 10cm from the original design. It's torso is kept stable by an M3 bolt (all materials listed and linked below)into a stabilizer afixed to the hanging frame, something I realized I needed only after building everything else and trying to move it. The joints are now snap-fit joints based on the resources provided by my classmate Vince. The figure attaches to the linkages via M2 bolts.

![3D Modeled Frame](https://github.com/bassmonkey620/Machine-Lab/blob/master/finalProject/referenceMedia/200503_climberFigure.JPG)

### Movement Mechanism ###

The movement mechanism starts with a worm gear motor. This is attached via  a shaft coupling to an 8mm shift. On the shaft are 5 thrust bearings and four custom cams, kept at the proper angles my M4 set screws. The box is held together with L-brackets and M3 nuts and bolts. The worm gear is afixed with M4 nuts and bolts. The cam followers are intended to be made from 8mm by 8mm key stock (though they can also be made from 8x8 sheets) and have machined screwd-holes in their ends. They are connected via M3 bolts. A cam guide is afixed to the top of the box with M4 nuts and bolts. All cam holes provide .3mm tolerance. There is an additional guide on the frame.

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
