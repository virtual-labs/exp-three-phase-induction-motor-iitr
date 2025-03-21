
# Torque speed characterstics of three phase Induction Motor 

### Introduction

<div align="justify" style="font-size:18px;">

An induction motor has several major advantages over a DC motor such as the absence of brushes and commutator segments, rugged construction, lower cost, reduced maintenance requirements, and smaller size for the same power output. Due to these advantages, induction machines have become more popular in industrial applications. For any motor load application, it is essential to understand the torque-speed characteristic of the motor.

<center>

<img src="images/torque1.png" width="45%">

Figure 1: Three-phase Induction motor

</center>

Consider a three-phase squirrel cage induction motor whose stator has three windings displaced in space by 120°. When these windings are energised with currents that are displaced in time by 120°, a rotating magnetic field is produced, rotating at a speed called synchronous speed Ns. The synchronous speed $N_s$ is given by 

<div style="text-align:center">

$N_s = \frac{120f}{P} \quad \dots(1)$
</div>

where, f is the frequency and P is the number of poles. If the rotor of the induction motor rotates at a speed, N<sub>r</sub>, then the slip, s is defined by

<div style="text-align:center">

$s = \frac{N_s - N_r}{N_s} \quad \dots(2)$</div>

The torque developed by the induction motor is given by

<div style="text-align:center">

$\displaystyle T = \frac{3 (I_2)^2 R_2}{W_s \cdot S}$
</div>

<div style="text-align:center">

$T = \frac{3}{W_s} \frac{\left(V_s\right)^2 \frac{R_2}{S}}{\left(R_1 + \frac{R_2}{S}\right)^2 + \left(X_1 + X_2\right)^2} \quad \text{.......(3)}$

</div>

where, W<sub>s</sub> is the synchronous speed in rpm, V<sub>s</sub> is the voltage applied to the stator, I~2~, R~2~, X~2~ are the rotor current, resistance and reactance referred to stator respectively. R~1~, X~1~ are the stator resistance and reactance respectively. If equation (3) is plotted, we get the T-N<sub>r</sub> characteristics as shown in Fig. 2. The maximum torque developed, Tm and the slip, S<sub>m</sub> at which T<sub>m</sub> occurs is given by.

<div style="text-align:center">

$T_m = \frac{3}{2 W_s} \frac{\left(V_s\right)^2}{R_1 \pm \sqrt{R_1^2 \pm \left(X_1 + X_2\right)^2}}$</div>

<div style="text-align:center">

$S_m = \frac{R_2}{\sqrt{R_2^2 + (X_1 + X_2)^2}}$</div>

<center>

<img src="images/torque2.png" width="42%">

<!-- ![torque2](images/torque2.png) -->
Figure 2: T-N<sub>r</sub> characteristics of a three phase induction motor </center>

If the voltage applied to the stator of an induction motor is varied, the developed torque will vary according to the following relation:

<div style="text-align:center">

$S_m \propto R_2$

$T \propto \left(V_s\right)^2 \quad ........(4)$  </div>

The maximum torque developed, T<sub>m</sub> is proportional to the square of the applied voltage as in eq.(5), but S<sub>m</sub> is independent of applied voltage. Therefore, if the T-N<sub>r</sub> characteristics are plotted for different voltages, the resulting curves appear as shown in Fig. 3

<center>
 
<img src="images/torque3.png" width="35%">

Figure 3: T-N<sub>r</sub> characteristics of a three phase induction motor
with different voltages</center>

If the weight of the load on the rotating pully in the induction motor is W1 & W2, then the torque of the induction motor is given by

<div style="text-align:center">

$T = (W_1 - W_2) \cdot 9.81 \cdot r \quad ..........(5)$ 
</div>

<center> Where, r = radius of brake drum (r=0.15m) </center>

### Advantages of Three phase Induction motor

* The absence of brushes eliminates sparking, allowing the motor to operate safely in hazardous environments.

* The motor's operation is independent of environmental conditions due to its robust and mechanically strong design.

* Induction motors are highly efficient, with full-load efficiency ranging from 85% to 97%.

### Disadvantages of Three phase Induction motor

 * Speed control is difficult because a three-phase induction motor operates at an almost constant speed, with minimal variation over the entire loading range. 

 * High input surge currents, known as magnetizing inrush currents, occur at startup, leading to temporary voltage drops.
 
</div>