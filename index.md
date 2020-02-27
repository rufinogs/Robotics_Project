## Welcome to my R0b0tic BLOG

I will post my homeworks of Robotic.

### Work Practices

These are my work practices: 

### 1. Follow Line 
The goal is to complete a lap following the line painted on the racing circuit.
We will use the plataform created by <a href="https://jderobot.github.io/RoboticsAcademy/ " >JDeRobot</a> with the lenaguage of programming called Phyton.

### INTRODUCTION TO THE PRACTICE FOLLOW LINE: 

<img src="Captura de pantalla 2020-02-26 a las 23.28.01.png" alt="hi" class="inline"/>

<h1>The first implement: <b>The case-based program</b></h1>
It is a conditional control structure that appears in most modern programming languages and allows a selection to be made   between several sets of program statements; the choice is dependent on the value of some expression. The case statement is a  more general structure than the <b> if then else statement,</b> which allows a choice between only two sets of statements.

<h2> The second implement: The PID controller</h2>
The name of PID stands for Proportional-Integral-Derivative. These three controllers are combined in such a way that it produces a control signal. As a feedback controller, it delivers the control output at desired levels. I have to admit that with that alteration in my code including the PID controller the Formula one has improve a lot the circulation in the race circuit. For more information you car learn about more of the PID controler in this video I linked:
<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
  <iframe src="https://www.youtube.com/watch?v=v27xYKdZUzI" frameborder="0" allowfullscreen="true"> </iframe>

### The Image Processing
In this practice i have used an important robotic sensir. This sensor is <b>the camera sensor</b> who gives a lot of information. The camera is a cheap sensor and i think it is the best price quality sensor in the market.
In this practice i do an image processing. Firts i get the <b> RSV image</b> and <b> I convert into a HSV image</b>. Then i create a mask for this imagen and filetered to get a <b> Binary Image</b> to get more information from the image and use it to create the code to redirect the car following the red line in the race circuit.

<figure class="align-center">
<img src="rgb.png" alt="hi" class="incline"/> 
RGB IMAGE

<img src="hsv.png" alt="hi" class="incline"/> 
<figcaption> HSV IMAGE </figcaption>

<img src="binary.png" alt="hi" class="incline"/> 
<figcaption> BINARY IMAGE </figcaption>
</figure>

### The case-based program:

This type is very easy i only count the error between pixels from right to left and i write in the angular velocity this error.This is a video of my case-based program with the Formula One in the practice:
  <iframe src="https://youtu.be/KFF2EVhh_rk" frameborder="0" allowfullscreen="true"> </iframe>

### The PID controller:
In this part of the program i calcuate the error in another form. I think this way to calculate the error its more efficient. i calculate the center of the image of the simulator and then i calculate i all moments the exact middle of the image that the camera provides me. With this "desviation" ussing a loop in the code saving the last 10 errors. I can compare to get the derivate part from the PID and I can sum all the errors to get the Integral part to get all the components fo the PID.This is a vdieo of my PID program with the Formula One in the practice: 
  <iframe src="https://youtu.be/PWc_PTr9I_M" frameborder="0" allowfullscreen="true"> </iframe>



### Comments


### Support or Contact

r.garciasa.2017@alumnos.urjc.es
Department of R0b0tics. URJC.
