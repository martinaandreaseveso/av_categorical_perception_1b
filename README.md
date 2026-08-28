# av_categorical_perception_1b

**Contributors**
Martina Andrea Seveso,
Rebecca Hirst,
Alan O'Dowd,
Fiona N. Newell

**Research aims**

To investigate the perceptual similarity of 3D familiar objects continua.

**Method and Procedure**

The study is develop in PsychoPy (version 2022.2.5; Peirce et al., 2019) and it is conduct online via Pavlovia and Prolific.

[Peirce, J. W., Gray, J. R., Simpson, S., MacAskill, M. R., Höchenberger, R., Sogo, H., Kastman, E., Lindeløv, J. (2019). PsychoPy2: experiments in behavior made easy. Behavior Research Methods. 10.3758/s13428-018-01193-y]

The study is a similarity judgments task. Participants are before exposed to a training phase (to familiarise with the procedure) and a testing phase. Both phases were structured as followed:

1. _Instructions_: to examine pair of objects presented and to rate them according to how similar the objects are to each other on a rating scale (7 points Likert scale) ranging from 1 - “very dissimilar” to 7 – “very similar”.
2. Pair of objects appears on the left and right of the fixation cross, the objects stays on the screen until participants responded. If the reaction time is longer than 3 seconds, the feedback ‘Too slow! Respond faster in the next trial’ is provided to participants.
3. _Target stimuli_: 4 Within-object Category Continua (Church-Hand Bell, Wine-Coke Bottle, Wine-Beer Glass, Urn-Single Stem Vase), 3 Between- object Category Continua (CokeBottle – SingleStemVase, UrnVase – WineBottle, MetalBox – BedLamp).

The images from each object pairings are presented in block with a 500ms inter-trial interval, and the order of trials within each block is randomized across participants.The presentation order of objects continua is randomised across participants.

The total duration of the experiment was around 25-30 minutes.

**Stimuli**

The experiment presents 3D objects shapes of familiar objects paired either with semantically congruent, incongruent, irrelevant sounds or presented only visually.

_3D Visual stimuli_ : The 3D objects shapes are created though the software SketchUp Pro (www.sketchup.com).

1. Development of 2D shapes for each object, with a maximum height of 100 mm and width of 70 mm.
From 2D to 3D: The 2D shapes are then rotated along the vertical axes to create the 3D object. All the objects have been created to fill a cylinder of 100x70mm to maintain the same physical proportions.
2. The list of object categories (including the two exemplars) developed: Bell (Hand, Church), Bottle (Wine, Coke), Glass (Wine, Beer), Vases (Urn, Single Stem), Lamp (Bedside, Desk), Stationary (Pen, Highlighter), Phone (Smart, Home), Clock (Wall, Wrist). See Image 2 for an example of 3D object developed.

_Morphing procedure: morphed continua_ :  Identification of step number for each continuum (11 steps). For each object pair is developed a morphed continua of 11 stimuli, including the 2 poles and the 9 morphed objects within the two poles.

The morphing procedure is accomplished with the software Blender 3.5.0 (2023) (www.blender.org).

1. Each object pair is located the same 3D space. The Shrink wrap Modifier is applied on one of the two objects and the Shape Key is assigned to the other object, with minimum range of 0 to maximum of 1.
2. Every object in each object pair is created keeping constant the difference of 0.1 step from each other.
3. The stimuli are extracted form Blender 3.3.0 by keeping constant the camera viewpoint and the lighting condition. The render engine Workebench is applied to all objects, with specs Studio Lighting, Colour Material (0132, light grey) and Specular Lighting applied. All the images are extracted with a resolution of 1080 x 1080 px, %100, and presented in a canonical view, on a transparent background.

**Design**

The experiment is a fully within-subejcts design, with step distance (4 levels: 1,2,3,4 steps distance) and objects class (2 levels: within and between) as factors.

**Dependent variables**

Similarity ratings and RTs.

**Independent variables**

Steps distance between A & B, stimulus and their interaction.

**Covariates**

Age, sex, and object type.

Ethics

Full ethical approval was obtained from the School of Psychology Ethics Committee, Trinity College Dublin.

**License**
a. Code (analysis scripts, stimuli generation): MIT License
b. All other materials (data, stimuli, experimental design): CC BY 4.0

All stimuli were created by the author (Seveso, M., A.). Data has been anonymised and contains no personal information.
