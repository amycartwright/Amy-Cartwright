# Creative Process

### Timeline

March
Experimentation, discovery and research. I want to use this month to explore my options. To see what tools are available to me and discover what works and what doesn't work. I will make small prototypes of different types of robotic motion and play with different methods of data input. I will try to find which of these small experiments interest me the most and which invite further exploration.

April
Building and coding. This month will be dedicated to solving technical solutions in both the physical build of the robot and the coded program. Ideally at the end of this month I will have a good second or third iteration of both of these. Something that I can continue to work with going forward into the final month.

May
Choreography and fine tuning. My final month of the residency will be dedicated to creating the dance work. Choreographing both the non-human and the human dancer. Using the program that has been created I will take the robotic dancer into the rehearsal space and begin to explore different movement relationships that can exist within the duet.

## Experimentation, Discovery and Research

### Early Experiments

#### Build

Cardboard prototype of a very simple <a href="https://www.mbtmag.com/article/2012/05/hydraulic-vs-electromechanical-actuators" target="_blank"> Electromechanical Actuator </a> 


<iframe width="560" height="315" src="https://www.youtube.com/embed/E1WnEYtShpk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


I am attracted to the motion of <a href="https://en.wikipedia.org/wiki/Linear_actuator" target="_blank"> linear actuators </a> , as the motion of extension they have is not something that we see when observing movement in the human body. When we talk about movement and choreography we often refer to expanding the body into the space around us. A linear actuator physically expands into the space. Making a simple prototype of this type of movement will allow me to explore the possibilities around using this type of mechanical  movement in performance. Is it too abstract? Is there still allowance for the audience to look at it as a performer or is a familiarity of movement essential? Do we need to be able to relate to the motion of the mechanical performer in order for us to view it as a performer.

These questions are difficult to answer at this stage but I think are worth further exploration. Next steps for this prototype will include constructing a more solid physical form using plastic tubing and 3D printing. I will then work on the software. Introducing CV and running a series of tests to see how the movement of the human can effect the movement of this very simple 'part'. And even more important what the effect is on the onlooker when watching this 'part' moving alongside a human body in a shared space.

First Prototype of Electromechanical Actuator using Computer Vision.

<iframe width="560" height="315" src="https://www.youtube.com/embed/NdsvM5-pilE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

This video shows a quick motion test using color tracking. The movement of the part is mapped to the movement of the hand along the x axis. When my hand extends through the space the piston physically extends into the space.

Following on from this initial build I felt that the range of motion of the part could be increased with some minor adaptations to the physical structure. Instead of connecting the moving lever to the outermost edge of the tube that moves I have connected it to the bottom edge. This allows th tube to extend much further into space. Problems with this build include an increased sense of instability as the tubes disconnect much easier. I think to solve this problem the tubes need to be longer.

![Notes](img/Prototype 2.jpg)
![Notes](img/Prototype2.1.jpg)
![Notes](img/Prototype2.2.jpg)

I would also like to work on the aesthetic. Rather than a solid tube I would like to try 3D printing a mesh tubing design.  The design shown below has been created using a Voronoi diagram. I like the delicacy of this design which is influenced by the design of some modern day protethics. 

![Notes](img/VoroniTube.jpg)


#### Software

Color Tracking
Will allow me to track motion of one/several specific points on the body. Issues with this are that I do not want the tracking to be obvious. I dont want to pull the audience out of the state of watching the performance by highlighting how the robots are working. I feel very strongly that this will minimise overall perceptive agency.

Kinect
As I am working with abstract robotic forms I don't think using the Kinect skeleton tracking is necessary. There is no need to track the motion of the specific points of the human body. 

Optical flow
Will allow the robot to look at the movement almost as if looking with blurry gaze. It will get a general sense of the movenent but not 

Machine Learning







Does a non-human dancer need to be limited to the senses of a human dancer? Whoa big question!

### Feedback sessions

_10/01/18_
First session rough notes following discussion with tutor and peers

![Notes](img/100118Notes.jpg)
![Notes](img/100118Notes1.jpg)

_17/01/18_
Preliminary thoughts - notes in image below taken by tutor

![Notes](img/170118Notes.jpg)

_24/02/18_
How to use blogging and writing to accompany your artistic practice

[Writing Task](writingTask.md)

_07/02/18_
Brief notes detailing discussions

![Notes](img/070218Notes.jpg)

_21/02/18_
Specific details - notes in image below taken by tutor

![Notes](img/210218Notes.jpg)

Why is it so important to me to use computer vision to control my prototypes? Explore the gap between using something like a potentiometer and computer vision. There is a difference. What is it? How can you show this? How can you demonstrate this? Open the crack wider. Exploring agency, when i use cv there is another person in the room with me. I can experiment and find out what works what doesn't, what is surprising. the agency coming from the physical can be faked. Fine line - sit just below it. The software can fill any gaps in agency - So how the robot respond to the human.

### Reading

[Movement Matters: How a Robot Becomes Body](http://delivery.acm.org/10.1145/3080000/3078035/a8-gemeinboeck.pdf?ip=158.223.165.48&id=3078035&acc=ACTIVE%20SERVICE&key=BF07A2EE685417C5%2E18BBEBD7797679F3%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1520335565_d4833361ae449f68b58db8b9cc764783)

[Capturing and Documenting Creative Processes in
 Contemporary Dance](http://delivery.acm.org/10.1145/3080000/3078041/a7-ribeiro.pdf?ip=158.223.165.48&id=3078041&acc=OA&key=BF07A2EE685417C5%2E18BBEBD7797679F3%2E4D4702B0C3E38B35%2E636B648B25476672&__acm__=1520336034_62d61ada870fde8b47518fe244021c82)

[The Delay Mirror: a Technical Innovation Specific to the Dance Studio](http://delivery.acm.org/10.1145/3080000/3078033/a9-molina-tanco.pdf?ip=158.223.165.48&id=3078033&acc=ACTIVE%20SERVICE&key=BF07A2EE685417C5%2E18BBEBD7797679F3%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1520336095_2c86d3a511880a43fbde45cd3c2c0d18)

[Sentimental Soft Robotics as Companion Artefacts](http://moco17.movementcomputing.org/wp-content/uploads/2017/12/ds9-zheng.pdf)

[Kinetic predictors of spectators’ segmentation of a live dance
 performance](http://moco17.movementcomputing.org/wp-content/uploads/2017/12/poster2-Forger.pdf)

[Algorythmic Reflections of Choreography](http://humantechnology.jyu.fi/archive/vol-12/issue-2/algorithmic-reflections-on-choreography/@@display-file/fullPaper/Ventura_Bisig.pdf)

[Leveraging morphological computation for expressive movement
 generation in a soft robotic artwork](http://delivery.acm.org/10.1145/3080000/3078029/a20-jorgensen.pdf?ip=86.172.150.17&id=3078029&acc=ACTIVE%20SERVICE&key=BF07A2EE685417C5%2E18BBEBD7797679F3%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1520368645_adca975fea6ea08a8063c36dfeda5a6e)


### Resources

[Erwin Wurm](http://www.erwinwurm.at/artworks.html)

[Cyrus Kabiru](https://smacgallery.com/artist/cyrus-kabiru-2/)

[Oscar Schlemmers Ballet of Geometry] (https://www.theguardian.com/artanddesign/gallery/2016/nov/24/oskar-schlemmers-ballet-of-geometry-in-pictures)

[Open Ended Group - work with choreography and code] (http://openendedgroup.com/index.html)

[Marc Downie Thesis - Choreographing the Extended Agent: performance graphics for dance theater] (http://openendedgroup.com/writings/downieThesis.html)

[![And all the question marks started to sing](http://img.youtube.com/vi/FYR2HY553y8/0.jpg)](http://www.youtube.com/watch?v=FYR2HY553y8)

[What its like to be a robot - Ted Talk + Written speech](https://www.ted.com/talks/leila_takayama_what_s_it_like_to_be_a_robot/transcript?ref=hvper.com)

[Goodbye Uncanny Valley - Alan Warburton](https://vimeo.com/237568588)

[Undercurrents - Albert Omass](https://omoss.io/work/undercurrents)

[Design Kit - Useful for ideation and planning of a project](http://www.designkit.org/methods/60)

[Gibson and Martelli latest research proposal](http://gtr.rcuk.ac.uk/projects?ref=AH%2FR009368%2F1)

[Zach Liberman talks about his artistic practice](https://vimeo.com/232656895)

[Neural Magazine](http://neural.it/)

[Eric Min Hcuong Castaing](http://shonen.info/)

[Motion House Charge](https://charge.motionhouse.co.uk/)

[Merging Dance, Rootics and AI](http://this.deakin.edu.au/innovation/one-creative-team-merging-dance-robotics-and-ai)

[Pinoke](http://motionlab.deakin.edu.au/portfolio/thepinokeproject/?_ga=2.52499240.1815394856.1520368039-1585838154.1520368039)

[Robot made using linear actuators] (https://www.youtube.com/watch?v=H14O47a2E88)

[How to stick form lab prints together](https://formlabs.com/blog/how-to-create-models-larger-than-your-3d-printers-build-volume/0)

[Formlab tech specs] (https://formlabs.com/3d-printers/form-2/tech-specs/)



### People to talk to

* Guido Orgs
* Toby Beasley
* Eric Min Hcong Castaing
