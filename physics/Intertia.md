See: [[Angular math]]
Point masses:
$$ I = mR^2 $$
With many points:
$$ I = \int R^2dm $$
But this is hard, and we need to look it up in a book. 
However these axis are through the center of mass.
**So be careful to look up the right one**
But rotation does not need to be through the center of mass
## Parallel Axis theorem
$$ I = I_cm  + mD^2 $$
D goes from axis to center of mass

## Examples
![[10-table-02.gif]]


Ex:
Sphere: $$ I_{cm} = \frac 3 5 m R ^2 $$
![[cmROT.png]]

Ex: rod
AXIS-=-=-=-=-=-=-=-=-=cm-=-=-=-=-=-=-=-=-=-
$$ I_{cm}= \frac 1 {12} ml^2$$
$$ I = \frac 1 {12} ml^2 + m (\frac l 2)^2 = \frac 1 {12} ml^2 + \frac 1 4 ml^2 = \frac 1 3 ml^2$$
Ex: lolly with massive stick (moment around end)
$$ I = I_cm  + mD^2 $$
$$ I_{tot} = I_{ROD} + I_{sph} $$
USING FROM LAST PROBLEM:
$$ I_{ROD} = \frac 1 3 ml^2 $$
m_1 = rod len
l = rod len
M = sphere len
R = sphere rad
$$ I_{sph} = \frac 2 5 MR^2 + M(R + l)^2 $$
$$ I_{tot} = \frac 1 3 ml^2 + \frac 2 5 MR^2 + M(l + R)^2 $$

## Newton
Transactional:
$$ \Sigma \bar F = M\bar a $$
$$ \Sigma \bar F = m \frac {d\bar v}{dt} = \frac d{dt}(m\bar V) $$
$$ \Sigma\bar F = \frac{d\bar p}{dt} $$$$ \bar p = m\bar v $$
$$ KE = \frac 1 2 I W^2 $$
- Momentum is concerved
Rotational:
$$ \Sigma \bar \tau  = I\bar\alpha$$
$$ \bar\alpha = \frac {d\bar \omega}{dt} $$
$$ \Sigma \bar \tau  = I\frac {d\bar \omega}{dt} = \frac{d}{dt}(I\bar \omega) $$
$$ \Sigma \bar \tau = \frac {d\bar L}{dt}$$
* WITH:
	$$ \bar L = I\bar\omega $$- Only way to change angular momenturm is to apply torque,
As such it is concerved
____________
To find the moment of inertia of the rolling wheel, we can use the relationship between the rotational kinetic energy, moment of inertia, and angular velocity. The total kinetic energy of the rolling wheel consists of both translational and rotational kinetic energy. 

1. **Translational Kinetic Energy (TKE)**:
   $$
   \text{TKE} = \frac{1}{2} m v^2
   $$
   where \(m\) is the mass of the wheel and \(v\) is the center of mass speed (0.13 m/s).

2. **Rotational Kinetic Energy (RKE)**:
   $$
   \text{RKE} = \frac{1}{2} I \omega^2
 $$
   where \(I\) is the moment of inertia and \(\omega\) is the angular velocity.

3. **Relation between Linear and Angular Velocity**:
   The angular velocity \(\omega\) can be expressed in terms of the linear speed \(v\) and the radius \(r\):
  $$
   \omega = \frac{v}{r}
   $$
   Substituting \(v = 0.13\) m/s and \(r = 0.2\) m:
   $$
   \omega = \frac{0.13 \, \text{m/s}}{0.2 \, \text{m}} = 0.65 \, \text{rad/s}
   $$

4. **Substituting \(\omega\) into the RKE equation**:
   The rotational kinetic energy is given as 35 J:
   $$
   35 = \frac{1}{2} I (0.65)^2
 $$
$$
   35 = \frac{1}{2} I (0.4225)
  $$
   $$
   35 = 0.21125 I
$$

5. **Solving for \(I\)**:
$$
   I = \frac{35}{0.21125} \approx 165.4 \, \text{kg} \cdot \text{m}^2
  $$

Thus, the moment of inertia of the rolling wheel is approximately **165.4 kg·m²**.





