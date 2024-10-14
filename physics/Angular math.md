See [[Centripetal Acceleration]], [[Center of Mass]]


TLDR:
$$ v = R \omega $$
$$ \tau = rFsin\phi $$
$$ d \omega = \bar \tau \cdot d\bar\theta$$
![[Pasted image 20241014102932.jpg]]
![[Pasted image 20241014103610.jpg]]
![[Pasted image 20241014104345.jpg]]

Direction defined with right hand rule: Take your right hand, curl your fingers, thumb = direction facing
## Torque
![[torque.png]]
Action of force in a rotational context
$$ \tau = r F_t = rFsin\Theta$$
$$ \bar \tau = \bar r * \bar F$$
**NOTE THE BAR!**
two vectors into one vector - "Cross product". 
$$ \bar A * \bar B = ABsin\phi$$
$$ (\bar B * \bar A) \ne (\bar A * \bar B) $$
$$ (\bar B * \bar A) = -(\bar A * \bar B) $$



Morse distance = more torque

## All kinematic equations apply!

Angular position = theta
Angular velocity:
$$ \omega = \frac {d\theta}{dt}$$
Angular acceleration:
$$ \alpha = \frac {d\omega}{dt}$$
SO:
$$ \Delta\Theta = 1/2\alpha t^2 + \omega_it$$
$$ \omega_t = \omega_i + \alpha t$$
$$ \omega_f^2=\omega_i^2 + 2\alpha\Delta\Theta$$

| Translational (linear) kinematics | Angular (rotational) kinematics |
| --------------------------------- | ------------------------------- |
| One point to another              | One rotation to another         |







_________________________
Ex: A grinding wheel accelerates from rest to 390 s<sup>-1</sup> at a constant rate of 125 s<sup>-2</sup>. How many revolutions does it take during this process?

Given:
omega<sub>i</sub> =V<sub>i</sub> = 0
omega<sub>f</sub> =V<sub>f</sub> = 390
alpha = 125
Unknown:  delta theta
$$ \Delta\theta = \frac{\omega_f^2}{2\alpha} = 208 $$
208 RAD
So the amount of revelations =  208 / 2pi = 96.7662053999
_______________________
Ex: The applied force F is 18N, the torque about point P is 8.5N, and the angle phi is 67*, the distance from point P to point Q is about?

$$ \tau = rFsin\phi $$
$$ r = \frac \tau {Fsin\phi} = \frac {8.5}{18sin67} = .51m$$

______________________
A firce of (7i-k)N is applied at position (9i + 3k) m.  Considering the origin to the the axis of rotation, determine the torque corresponding to this force.
![[ext.png]]
$$ \bar \tau = \bar r * \bar F = (9\hat i + 3 \hat k) * (7 \hat i - \hat k) $$
FOIL THIS BITCH

$$  \bar \tau = 9\hat i * 7\hat i + 9\hat i * (-\hat h) + 3\hat k *7 \hat i  +3 \hat k * (-\hat k)    $$
$$ = -9(\hat i * \hat k) + 21 (\hat k * \hat i) $$
$$ = 9\hat J + 21 \hat J = 30 \hat J $$

_______________
## Cross product ext
Recall work:
$$ w = \bar F\Delta\bar R$$
### Dot product:
$$ \bar A \bar B = ABcos\phi = A_xB_x + A_yB_y + ...$$
$$ \hat i \cdot \hat i = (1)(1)cos0 = 1 = 1*1 $$
$$ \hat i \cdot \hat J = (1)(1)cos\frac \pi2 = 0 = \hat J \cdot \hat k$$
Torque:
$$ \bar\tau = \bar r * \bar F = rFsin\phi$$ 
 RH-Rule
### Cross product (VECTOR!!!!): 
$$ \bar A * \bar B = ABsin\theta $$


$$ \hat i * \hat i = (1)(1)sin0 = 0 $$
$$ \hat i * \hat J = (1)(1)sin\frac \pi2 = 1$$
$$ \hat i * \hat J = \hat k $$
$$ \hat k * \hat i = \hat j $$


## Kinetic Energy
$$ I = mR^2 $$
$$ k = \frac 1 2mv^2  $$
Stick them together
$$ m = \frac I {R^2} $$
$$ k = \frac 1 2 (\frac I R) ^2 = \frac 1 2 I w ^2 $$
### Rolling spheres(Solid) are different:
Moments of inertia ARE CONSTANT (\*Asterix):

 $$ K = K_T + K_R $$
 $$ = \frac 1 2 m v^2 + \frac 1 2 I\omega^2 $$
 Subsitute in with:
 $$ I = \frac 2 5 m R^2 $$
  AND:
 $$ \omega = \frac V R $$$$ = \frac 1 2 m v^2 + \frac 1 2 (\frac 2 5 m R^2)\omega^2 $$

 $$ = \frac 1 2 m v^2 + \frac 2 {10} m R^2(\frac V R)^2 $$
 $$ k = \frac 7 {10} m v^2 $$
 <h3>The asterix</h3>
 The axis matters with moment of inertia. And some object that are complex have multiple moments of inertia. 
 ![[rotlolly.png]]
 $$ I = I_{cm} + mD^2$$

 mD^2 is known as the "point mass" term
 D is the axis to center of mas
 One object exists you can easily calc the moment of inertial. A RING
 ![[ring.png]]
 All the points are of r
 $$ I = \int R^2dm = R^2 \int dm =R^2m $$
 _________________
 ## Examples
 
 You have just bought a new bicycle. On your first riding trip, it seems that the bike comes to rest relatively quickly after you stop pedaling and let the bicycle coast on flat ground. You call the bicycle shop from which you purchased the vehicle and describe the problem. The technician says that they will replace the bearings in the wheels or do whatever else is necessary if you can prove that the frictional torque in the axle of the wheels is worse than  −0.02 N · m.At first, you are discouraged by the technical sound of what you have been told and by the absence of any tool to measure torque in your garage. But then you remember that you are taking a physics class! You take your bike into the garage, turn it upside down and start spinning the wheel while you think about how to determine the frictional torque. The driveway outside the garage had a small puddle, so you notice that droplets of water are flying off the edge of one point on the tire tangentially, including drops that are projected straight upward, as shown in the figure below.

Ah-ha! Here is your torque-measuring method! The upward-projected drops leave the rim of the wheel at the same level as the axle. You measure the height to which a drop rises from the level of the axle: h1 = 48.0 cm.
The wet spot on the tire makes one revolution and another drop is projected upward. You measure its highest point:  h2 = 42.0 cm. You measure the radius of the wheel:  r = 0.292 m.
Finally, you take the wheel off the bike and find its mass: m = 0.900 kg.
 Because most of the mass of the wheel is at the tire, you model the wheel as a hoop. What do you tell the technician when you call back? (Enter the frictional torque, in N · m, that you tell to the technician. Assume the positive direction is clockwise. Indicate the direction with the sign of your answer.)

We know $$ v = R\omega $$
AND
$$ v=\sqrt{2gh} $$
AND
$$ \omega_f^2=\omega_i^2 + 2\alpha\Delta\Theta $$
AND
$$ \tau = I\alpha$$

Modeling the wheel as a hoop:
 $$ I = mR^2 $$

Measure the h twice, in between 2 pi rads pass.
![[Pasted image 20241014094623.png]]


SO:
$$  \frac{\omega_f^2- \omega_i^2}{2\Delta\Theta} =  \alpha  $$

_______________________
The figure below shows the drive train of a bicycle that has wheels 67.3 cm in diameter and pedal cranks 17.5 cm long. The cyclist pedals at a steady cadence of 82.0 rev/min. The chain engages with a front sprocket 15.2 cm in diameter and a rear sprocket 6.00 cm in diameter.
![[10-p-016.gif]]
(a) Calculate the speed of a link of the chain relative to the bicycle frame.
$$ v = R_f\omega_f $$
(b) Calculate the angular speed of the bicycle wheels.
$$ v = R_r\omega_r$$
Since the rear sprocket is on the wheel 
$$ \omega_R = \omega_W $$
$$ \omega_R = \frac {R_f}{R_R}{\omega_F} = \omega_W$$

(c) Calculate the speed of the bicycle relative to the road.
Wheels are rolling objects SO:
$$ v_B = R_w \omega $$
____________________________
A weed trimmer for landscaping has a rotating head which consists of a spool of monofilament line, with a strand of line that extends out from the edge. The spool has an inner diameter of 3.00 cm and an outer diameter of 18.0 cm, and a mass of 100 g. The strand has a length of 16.0 cm. The monofilament line has a linear density of 10.0 g/m.
![[10-p-054.gif]]
(a) When switched on, the trimmer speeds up from 0 to 2,250 rev/min in 0.175 s. What average power (in W) is delivered to the head by the trimmer motor while it is accelerating? (Round your answer to at least one decimal place.)

Power is the rate of work (work per time)
$$ P = \frac W {\Delta t} $$
$$ W = \Delta K = \frac 1 2 I \omega ^2 $$
Objective: Moment of inertia 
$$ I = I_{SPOOL} + I_{STRAND} $$
LOOK UP THE SPOOL
$$ I_{SPOOL} = \frac 1 2 M(R_{tot}^2 + M_{HOLE}^2) $$
$$ I_{STRAND} = I_{CM} + MD^2 $$
[[Intertia#Parallel Axis theorem]]
