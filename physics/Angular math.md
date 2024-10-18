See [[Centripetal Acceleration]], [[Center of Mass]]


TLDR:
$$ v = R \omega $$
$$ P = \tau \cdot \omega $$
Power is the rate of work (work per time)
$$ P = \frac W {\Delta t} $$
$$ W = \Delta K = \frac 1 2 I \omega ^2 $$
$$ \tau = r*F $$
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
$$ I_{SPOOL} = \frac 1 2 M(R_{tot}^2 + R_{HOLE}^2) $$
$$ I_{STRAND} = I_{CM} + MD^2 $$

[[Intertia#Parallel Axis theorem]]
________________________
![[Pasted image 20241014194134.png]]
A hollow sphere is attached to the end of a uniform rod. The sphere has a radius of 0.90 m and a mass of 0.60 kg. The rod has a length of 1.52 m and a mass of 0.58 kg. The rod is placed on a fulcrum (pivot) at _X_ = 0.48 m from the left end of the rod.

(a) Calculate the [moment of inertia](http://www.webassign.net/serpse9/10-table-02.gif) (click for graphical table) of the contraption around the fulcrum.
$$ X=0.48 $$
$$ R=0.9 $$
$$ m_{s}=0.6 $$
$$ m_{r}=0.58 $$
$$ L=1.52 $$$$ I_{s}=\frac{2}{3}m_{s}R^{2}+m_{s}d_{s}^{2} $$

$$ I_{R}=\frac{1}{12}m_{r}L^{2}+m_{r}\left(\frac{L}{2}-X\right)^{2} $$
$$ I_{tot}=I_{s}+I_{R} $$
$$ T_{s}=9.8m_{s}d_{s} $$
$$ T_{r}=-9.8m_{r}\left(\frac{L}{2}-X\right) $$
$$ T_{tot}=T_{s}+T_{r} $$
$$ \alpha = \frac{T_{tot}}{I_{tot}} $$
$$ R_{q}=L-X $$
$$ a = R_{q}\frac{T_{tot}}{I_{tot}} $$
__________________
4. A uniform solid disk of mass _m_ = 2.90 kg and radius _r_ = 0.200 m rotates about a fixed axis perpendicular to its face with angular frequency 6.09 rad/s.

(a) Calculate the magnitude of the angular momentum of the disk when the axis of rotation passes through its center of mass.
$$ L = I\omega $$
$$ I = \frac 1 2 mR^2 $$
FIND L
(b) What is the magnitude of the angular momentum when the axis of rotation passes through a point midway between the center and the rim?
$$ I = \frac 1 2 mR^2 + m(R/2)^2 $$
____________________________________
8. A playground merry-go-round of radius R = 2.20 m has a moment of inertia I = 255 kg · m2 and is rotating at 9.0 rev/min about a frictionless vertical axle. Facing the axle, a 24.0-kg child hops onto the merry-go-round and manages to sit down on the edge. What is the new angular speed of the merry-go-round?
INELASTIC COLLISIONS
KE is not conserved
Momentum is not conserved due to the axle being non moving
SO we use angular, as thats conserved

$$ l_i = L_f $$
$$ I_i\omega_i=I_f\omega_f$$
We added the kid at the edge
$$ I_f = I_i + m_{kid}R^2 $$
____________________
9. Two astronauts (figure), each having a mass of 80.0 kg, are connected by a d = 9.0-m rope of negligible mass. They are isolated in space, orbiting their center of mass at speeds of 5.10 m/s.


![[11-p-055.gif]]
NOTE THE m/s, THIS IS NOT ANGULAR VELOCITY

(a) Treating the astronauts as particles, calculate the magnitude of the angular momentum of the two-astronaut system.

Magically as this is a rotor **and** a particle we can do:
$$ \bar L = I\bar\omega$$
$$ L = 2mR^2\omega = 2mRv $$
AND
$$ \bar L = \bar r * \bar p = rpsin\phi $$
$$ L = rp = rp_{tot}  = 2mvr$$
(b) Calculate the rotational energy of the system. 
$$ K_R = \frac 1 2 I\omega^2$$
(c) By pulling on the rope, one astronaut shortens the distance between them to 5.00 m. What is the new angular momentum of the system?
$$ \Sigma \tau = \frac{d\bar L}{dt}$$
Due to the astronauts pulling on the rope, the force points inward, and therefore exerts 0 torque.

**ITS THE SAME!**

(d) What are the astronauts' new speeds?

$$ I_i\omega_i = I_f\omega_f$$
$$ I_i = mR_i^2 $$
$$ I_f = mR_f^2 $$

Recall:
$$ v = R\omega$$**Increase in rotational energy**

(e) What is the new rotational energy of the system?
$$ K_R = \frac 1 2 I_f \omega{p}^2 $$
(f) How much chemical potential energy in the body of the astronaut was converted to mechanical energy in the system when he shortened the rope?

Simply the difference of before and after

$$ \Delta k + \Delta E_{int} = 0 $$
_____________________________________
11. A block of mass _m_1 = 2.30 kg and a block of mass _m_2 = 5.90 kg are connected by a massless string over a pulley in the shape of a solid disk having radius _R_ = 0.250 m and mass _M_ = 10.0 kg. The fixed, wedge-shaped ramp makes an angle of 𝜃 = 30.0° as shown in the figure. The coefficient of kinetic friction is 0.360 for both blocks. Use _g_=9.8 m/s2.
![[pse6_p10-37.gif]]
SHIT THE PULLY HAS MASS!!!!
It acts like a rotor
Friction acts, so T<sub>1</sub> != T<sub>2</sub>
$$ \Sigma \tau = I \bar \alpha  $$
$$ -RT_1 + RT_2 = Ia $$
$$ a = R\alpha$$
Luckly still 90 deg
_____________________
12. A uniform beam of length L = 7.00 m and weight 3.80 ✕ 10<sup>2</sup> N is carried by two workers, Sam and Joe, as shown in the figure below. Determine the force that each person exerts on the beam.
![[12-p-011-alt.gif]]
Make a force diagram, do the math
_______________
13. A hungry bear weighing 700 N walks out on a beam in an attempt to retrieve a basket of goodies hanging at the end of the beam (see figure below). The beam is uniform, weighs 200 N, and is 6.00 m long, and it is supported by a wire at an angle of 𝜃 = 60.0°. The basket weighs 80.0 N.
![[12-p-043.gif]]![[Pasted image 20241016104522.jpg]]
______________
		
```plaintext
A mixing beater consists of three thin rods, each 11.0 cm long. The rods diverge from a central hub, separated from each other by 120°, and all turn in the same plane. A ball is attached to the end of each rod. Each ball has cross-sectional area 3.80 cm2 and is so shaped that it has a drag coefficient of 0.500. The drag force on each ball is R = 1 2 D 𝜌 A v2 where D is the drag coefficient, 𝜌 the density of the fluid, A the cross-sectional area, and v the speed of the object moving through the fluid. 

(a) Calculate the power input required to spin the beater at 1000 rev/min in water.

b) The beater is taken out of the water and held in air. If the input power remains the same (it wouldn't, but if it did), what would be the new rotation speed?
```
a.
To calculate the power input required to spin the beater at 1000 rev/min in water, we need to find the drag force acting on each ball and the work done to overcome this force.

### Step 1: Given information

- Rod length = \( 11.0 \, \text{cm} = 0.110 \, \text{m} \)
- Cross-sectional area of each ball, \( A = 3.80 \, \text{cm}^2 = 3.80 \times 10^{-4} \, \text{m}^2 \)
- Drag coefficient, \( D = 0.500 \)
- Water density, \( \rho = 1000 \, \text{kg/m}^3 \)
- Rotational speed, \( N = 1000 \, \text{rev/min} \)

### Step 2: Find angular velocity and tangential speed of each ball

Convert the angular speed into rad/s:

$$
\omega = \frac{1000 \, \text{rev/min}}{60 \, \text{s/min}} \times 2\pi \, \text{rad/rev} = \frac{1000 \times 2\pi}{60} = 104.72 \, \text{rad/s}
$$

The tangential speed \( v \) of each ball (at a distance \( r = 0.110 \, \text{m} \)) is:

$$
v = \omega r = 104.72 \times 0.110 = 11.519 \, \text{m/s}
$$

### Step 3: Calculate the drag force on each ball

The drag force is given by the formula:

$$
R = \frac{1}{2} D \rho A v^2
$$

Substitute the known values:

$$
R = \frac{1}{2} \times 0.500 \times 1000 \, \text{kg/m}^3 \times 3.80 \times 10^{-4} \, \text{m}^2 \times (11.519 \, \text{m/s})^2
$$

$$
R = 0.25 \times 1000 \times 3.80 \times 10^{-4} \times 132.71
$$

$$
R \approx 12.62 \, \text{N}
$$

Thus, the drag force on each ball is approximately \( 12.62 \, \text{N} \).

### Step 4: Calculate the torque

The torque \( \tau \) exerted by the drag force on each ball at a distance \( r = 0.110 \, \text{m} \) is:

$$
\tau = R r = 12.62 \times 0.110 = 1.388 \, \text{N·m}
$$

Since there are three balls, the total torque is:

$$
\tau_{\text{total}} = 3 \times 1.388 = 4.164 \, \text{N·m}
$$

### Step 5: Calculate the power input

The power \( P \) required to spin the beater is given by:

$$
P = \tau_{\text{total}} \times \omega
$$

Substitute the values:

$$
P = 4.164 \times 104.72 = 436.0 \, \text{W}
$$

Thus, the power input required to spin the beater at 1000 rev/min in water is approximately **436 W**.
In this part, we want to find the new rotational speed of the beater in air, assuming the input power remains the same as in water. The key factor is that the drag force in air will be much less than in water due to the lower density of air, which will allow the beater to rotate faster for the same power.

b.
### Step 1: Given information

- Drag coefficient, \( D = 0.500 \)
- Cross-sectional area of each ball, \( A = 3.80 \times 10^{-4} \, \text{m}^2 \)
- Air density, \( \rho_{\text{air}} \approx 1.225 \, \text{kg/m}^3 \)
- Power input, \( P = 436.0 \, \text{W} \) (same as in water)

We will assume the drag force relationship still holds, and we need to find the new rotational speed \( \omega_{\text{air}} \) in air.

### Step 2: Power and drag force relationship

From the drag force equation, we know the force is proportional to the square of the speed:

$$
R \propto \rho v^2
$$

Since power is proportional to the torque and the angular velocity \( P \propto \tau \times \omega \), and torque is related to drag force \( R \), we can establish that:

$$
P \propto \rho \omega^3
$$

This means:

$$
\frac{P_{\text{air}}}{P_{\text{water}}} = \frac{\rho_{\text{air}} \omega_{\text{air}}^3}{\rho_{\text{water}} \omega_{\text{water}}^3}
$$

Given that \( P_{\text{air}} = P_{\text{water}} \), this simplifies to:

$$
\frac{\omega_{\text{air}}^3}{\omega_{\text{water}}^3} = \frac{\rho_{\text{water}}}{\rho_{\text{air}}}
$$

### Step 3: Solve for \( \omega_{\text{air}} \)

Substitute the densities of water and air:

$$
\frac{\omega_{\text{air}}^3}{\omega_{\text{water}}^3} = \frac{1000 \, \text{kg/m}^3}{1.225 \, \text{kg/m}^3}
$$

$$
\frac{\omega_{\text{air}}^3}{\omega_{\text{water}}^3} \approx 816.33
$$

Thus,

$$
\omega_{\text{air}} \approx \omega_{\text{water}} \times 816.33^{1/3}
$$

$$
\omega_{\text{air}} \approx 104.72 \times 9.44 = 988.4 \, \text{rad/s}
$$

### Step 4: Convert to revolutions per minute

To convert angular velocity back to rev/min:

$$
N_{\text{air}} = \frac{\omega_{\text{air}}}{2\pi} \times 60 = \frac{988.4}{2\pi} \times 60 = 9440 \, \text{rev/min}
$$

Thus, the new rotation speed in air, assuming the same power input, would be approximately **9440 rev/min**.