See [[Centripetal Acceleration]], [[Center of Mass]]

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