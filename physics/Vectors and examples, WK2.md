*Expanded upon from:[[Defs and notation WK1]]*


An airplane flies straight for 640 km/hr. Then changes to 700 km /hr for 50 min. If the average speed is 680 km /hr. What is the duration of the entire trip? 

Treat as two seperate equations. The only useful equations in
$$ \Delta x = 0.5 at^2 + v_it $$
With a = 0
$$ \Delta_1 = v_1t_1 $$
$$ \Delta_2 = v_2t_2 $$
Unknowns: d1, t1, d2:
Average vel = dx / dt
$$
 \bar v = \frac {\Delta_1 + \Delta_2} {t_1 + t_2} $$
 THE PHYSICS IS DONE!
 $$\bar v = \frac {v_1t_1 + v_2t_2} {t_1 + t_2} $$
 Mult by denominator:
 $$\bar v(t_1 + t_2) - v_1t_1 - = v_2t_2 $$
 ETC
_______________________________________________________
L starts at rest. Accel is 3.4 m/s^2
S starts from rest 140m ahead of L and accel 2.9 m/s^2
1. Write an equation for L's pos as a func of time
$$ x_f - x_i = \Delta x = 0.5 at^2 $$
$$ x_f  = 0.5 at^2 + x_i  $$
$$ x_f  = 0.5 at^2  $$
2. Write eq for S as a function of time
$$ x_f  = 0.5 at^2 + x_i  $$
3. Combine
$$  0.5a_st^2 + x_{is} = 0.5 a_Lt^2 $$
____________________________________________
A cubic foot of osmium is the densest metal, is 1410 pounds. Calculate the maxx of a cubic inch in kilograms (1 pound = 0.454 kg, 1ft = 12 in)
$$ p = (\frac {1410 lb} {1ft^3}) (\frac {1 ft} {12in}) ^3 \frac {.454kg} {1 lb} = .37 kg $$
_______________________________________________________
## Vectors
ordered pairs
Components = Components
$$ magnitude = \sqrt {x^2 + y^2} $$
(in 2d)
$$ \frac {a_y}{a_x} = tan \Theta $$
*you do **not** need a coord system for angles and to normalize*
A vector is an array of numbers. With component-wise addition and scalar multiplication (multi one number with each element)

$$ a_x = a cos\Theta $$
$$ a_y = a sin\Theta $$
$$ a = \sqrt {a_x^2 + a_y^2} $$
Rectangular to polar coordinates; (a, theta) **ARE NOT COMPONENTS**
$$ a = \sqrt {a_x^2 + a_y^2 + a_z^2} $$
3d TRIG is messy and too complicated for this course.
______________________________________________________________
A **unit vector** is a vector of magnitude 1; aka normalized vectors. 

$$ \hat V  = Unit\ Vector$$
$$ \hat I = (1, 0),\ \hat J = (0, 1) $$
$$ \hat I = (1, 0),\ \hat J = (0, 1) $$
k for 3d as well


Mult-ing vecs
$$ (2, 3) = 2\hat I = 3\hat J $$
This becomes a collection of terms... great
can apparently be used to convert coord systems.
________________________________________
adding vectors = tip-to-tail  addition
__________________________________________________
## Unit circle
The length S of the ARC s tje amg;e
theta = s
______________________________
## Vector arithmatic
Eqs:
$$ \Delta \bar r = 0.5\bar at^2+\bar v_it $$
$$ \bar v_f^2 = \bar v_i^2 + 2\bar a\Delta \bar r $$
$$ \bar v_f = \bar v_i + \bar at $$
Defs:
$$ \bar r = x \hat i + y \hat j $$
$$ \bar v = \frac {\Delta \bar r} {\Delta t} $$
$$ \Delta \bar r = \bar r_2 - \bar r_1 $$
Instantaneous :
$$ \bar v = \frac {d (\Delta \bar r)} {dt} = \frac {d\bar r} {dt} $$
Accel average
$$ \bar a = \frac {\Delta \bar v} {\Delta t} $$

$$ \bar a = \frac {d\bar v} {dt} $$
Subing vectors is the same adding the inverse
## Eq for projectile
$$ \Delta x = 0.5 a_x t^2 + v_{ix}t$$
BUT KNOWING THINGS
$$ \Delta x = v_{ix}t\ \ \ ;\ \ \ \Delta y = -0.5 gt^2 + v_{iy}t$$
BUT delta y is **KNOWN**, it is zero!
Since y is zero., factoring is simple:
$$ t (-0.5gt + v_{iy}) = 0 $$
$$ -0.5gt + v_{iy} = 0 $$
$$ t = \frac {2v_{iy}} {g} $$
$$ \Delta x = v_{ix} t = v_{ix}(\frac {2v_y} {g})=\frac {2v_{ix} v_{iy}}{g}$$

$$ \Delta x = \frac {2v_{ix}v_{iy}} {g} = \frac {2v_i^2 sin \Theta cons \Theta} {g} $$
WITH DOUBLE ANGLE THEOREM:
$$ 2sin\Theta cos\Theta = sin2\Theta $$
$$ \Delta x = \frac  {v_i^2 sin 2 \Theta} {g} $$
\
## Circular motion
There is a component of acceleration directed **toward the center** of the circle. This is the **centripetal** acceleration. The magnitude of the component is **v^2 / R**, where R is the radius.

If you accelerate during the curve it is known as the **tangential component** of acceleration. 
$$ a_T = \frac {d|v|} {dt} $$
Which implies a coordinate system...  one which rotates with the object... 
Acceleration parallel to motion changes speed, perpendicular changes direction. 
_______________________
Ex:
A satalight is 250 km above earth at 7.82 km/s. What is the centeripetal acceleration?
$$ \frac{\left(7.83\cdot1000\right)^{2}}{\left(250+6370\right)\cdot1000} = 9.26116314199\ m/s^2 $$
about 9.28

Ex 2:
A firefighter as d needs to aim the hose such that water enters at a windows a height h above the ground.
a. Given theta and v_i where will it hit the building
$$ \Delta x = 0.5 a_x t^2 + v_{iy}t $$
$$ \Delta y = 0.5 a_y t^2 + v_{iy}t $$
Step 1, simplify with known vars
$$ d = \Delta x = (v_icos \Theta)t $$
$$ h = -0.5 g t^2 = (v_i sin \Theta)t $$
Unknowns h, t
$$ t = \frac {d}{v_i cos \Theta} $$
$$ h = (\frac {-0.5gd}{v_i cos \Theta})^2 + \frac {v_{iy}d}{v_i cos \Theta} $$
$$ h = (\frac {-0.5gd}{v_i cos \Theta})^2 + \frac {d}{cos \Theta} $$
SImplify: $$ h = dtan\Theta - \frac {gd^2sec^2\Theta} {2 v_i^2} $$
Using Pythagorean:
$$ \frac {cos^2 \Theta + sin^2 \Theta} {cos^2 \Theta} = \frac 1{cos^2\Theta} $$
$$ 1 + tan^2\Theta = sec^2\Theta $$
$$ h = d than\Theta- \frac {gd^2}{2v_i^2}(tan^2\Theta + 1) $$
$$ \frac {gd^2}{2v_i^2}tan^2\Theta - dtan^2 \Theta  + (\frac{gd}{2v^2}) $$
_______________________


