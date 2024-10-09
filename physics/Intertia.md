Depends on the mass of the object AND its size and shape.
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
$$ \Sigma \bar F = n\bar a $$
$$ \Sigma \bar F = m \frac {d\bar v}{dt} = \frac d{dt}(m\bar V) $$
$$ \Sigma\bar F = \frac{d\bar p}{dt} $$$$ \bar p = m\bar v $$
- Momentum is concerved
Rotational:
$$ \Sigma \bar \tau  = I\bar\alpha$$
$$ \bar\alpha = \frac {d\bar \omega}{dt} $$
$$ \Sigma \bar \tau  = I\frac {d\bar \omega}{dt} = \frac{d}{dt}(I\bar \omega) $$
$$ \Sigma \bar \tau = \frac {d\bar L}{dt}$$
* WITH:
	$$ \bar L = I\bar\omega $$- Only way to change angular momenturm is to apply torque,
As such it is concerved
