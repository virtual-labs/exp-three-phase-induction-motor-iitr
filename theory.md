<head>
<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> </script>
</head>

### Introduction
<div align="justify" style="font-size:18px;">
An induction motor compared to a DC motor has some major advantages such as the absence of brushes, commutator segments, rugged construction, being cheap, lesser maintenance requirements, and smaller size for the same power output. Due to these advantages, induction machines have become more popular in industrial applications. For any motor load application, it is imperative to know the torque-speed characteristic of the motor.

<br><center> <img src="images/torque1.png" width="45%"><br>
Figure 1: 3-phase Induction motor

</center>
Consider a three-phase squirrel cage induction motor whose stator has three windings displaced in space by 120°. When they are excited with currents that are displaced in time by 120°, a rotating magnetic field rotating at a speed called synchronous speed N<sub>s</sub> is set up. The synchronous speed N<sub>s</sub> is given by equation (1).

  <center> $$N_s = \frac{(120)f}{P}.............. (1)$$  </center>

where f is the frequency and P is the number of poles. If the rotor of the induction motor rotates at a speed N<sub>r</sub>, then the slip S is defined by equation (2).

 <center> $$S = \frac{N_s - N_r}{N_s}.........(2)$$ </center>

The torque developed by the induction motor is given by equation (3).

 <center> $$T = \frac{3 I_2^2 R_2}{W_s.s}$$ </center>

 <center> $$T = \frac{3}{W_s}.\frac{V_s^2.\frac{R_2}{s}}{\left(R_1 + \frac{R_2}{s}\right)^2 + \left(X_1 + X_2\right)^2}............(3)$$ <br> </center>

where W<sub>s</sub> is the synchronous speed in rpm, V<sub>s</sub> is the voltage applied to the stator, I<sub>2</sub>, R<sub>2</sub>, X<sub>2</sub> are the rotor current, resistance, and reactance referred to the stator respectively, and R<sub>1</sub>, X<sub>1</sub> are the stator resistance and reactance respectively. If equation (3) is plotted, we get the T−N<sub>r</sub> characteristics as shown in Fig. 1. The maximum torque developed T<sub>m</sub> and the slip S<sub>m</sub> at which T<sub>m</sub> occurs is given by equation (4).

 <center> $$T_m = \frac{3}{2W_s}.\frac{V_s^2}{R_1 \pm \sqrt{R_1^2 \pm \left(X_1 + X_2\right)^2}} ...........(4)$$ </center>

 <center> $$S_m = \frac{R_2}{\sqrt{R_2^2 + \left(X_1 + X_2\right)^2}}$$ </center>

 <center> $$S_m \propto R_2$$ <br> </center>

If the voltage applied to the stator of the induction motor is varied, the developed torque will vary according to the relation:

<center> $$T \propto V_s^2 ..........(5)$$ </center>

The maximum torque developed T<sub>m</sub> is also proportional to the square of the applied voltage as in equation (5), but 
S<sub>m</sub> is independent of the applied voltage. So, if the T−N<sub>r</sub> characteristics are plotted for different voltages, we get the characteristics as shown in Fig. 2.

<center> <img src="images/torque2.png" width="42%"><br>
Figure 2: T−N<sub>r</sub> characteristics of a three-phase induction motor</center><br> 

<center> <img src="images/torque3.png" width="35%"><br>
Figure 3: T−N<sub>r</sub> characteristics of a three-phase induction motor with variable voltage control
</center><br>

The torque-speed characteristics of a three-phase induction motor are a straight line between the no-load and full-load operating points. The slope of the curve depends upon the resistance of the rotor circuit i.e., the higher the rotor circuit resistance, the sharper the slope of the curve.

If the weight of the load on the rotating pulley in the induction motor is W1 & W2, then the torque of the induction motor is given by equation (6).

<center>$$T = (W_1 - W_2)\cdot 9.81\cdot r ........(6)$$ </center>

 Where (r) = radius of brake drum (r = 0.15m)<br> <center> <img src="images/torque4.png" width="50%"><br>
Figure 4: Plot between Torque and Load current</center>

### <b>Advantages of Three-phase Induction Motor: </b>

1. The most important advantage of an induction motor is its simple construction.

2. The working of the motor is independent of environmental conditions because the induction motor is robust and mechanically strong.

3. Due to the absence of brushes, there are no sparks in the motor. It can also be operated in hazardous conditions.

4. An induction motor is a highly efficient machine with full-load efficiency varying from 85 to 97 percent.

### <b>Disadvantages of Three-phase Induction Motor: </b>

1. Speed control of an induction motor is very difficult to attain. This is because a three-phase induction motor is a constant-speed motor, and for the entire loading range, the change in speed of the motor is very low.

2. Induction motors have high input surge currents, referred to as magnetizing inrush currents, which cause a reduction in voltage at the time of starting the motor.

3. Due to poor starting torque, the motor cannot be used for applications requiring high starting torque.

</div>
