Related to [[Angular math#Step 5 Calculate the power input]]

# Equations
In general :
$$ F = PA $$
$$ m = pv $$
$$ F_g = \rho V_g$$
$$ P = P_c+\rho gh$$
$$ f = \rho V g $$
$$ \rho_1 v_1 A_1 = \rho_2 v_2 A_2$$
$$ P_1 + \frac{1}{2} \rho v_1^2 = P_2 + \frac{1}{2} \rho v_2^2 $$
$$ W = F_x\cdot\Delta x$$
# Fluid
Randomly moving particles
Types:
- Liquid
	- Moves within fluid, but can't escape
	- Gravity makes it take shape of container
	- Treat as incompressible
- Gas
	- Fills its container on all sides
		- Gravity doesn't matter
	- Compressible
	- Not closely bound
- Other
	- corn
# Density
Mass per unit volume
$$ \rho = \frac m V $$
Gas is about 10<sup>-3</sup>
Metals are about 10<sup>1</sup> water
Rocks are about 10<sup>1</sup> water

# Pressure
See: [[Stress#Pressure]]
Force per unit volume measured in [[Stress#Pascals]]
Pressure is perpendicular to surface

$$ F = PA $$
$$ P =\frac F  A $$
$$ P = P_\text{surface} + \rho gh$$
If not moving the pressure at the surface is atmospheric 
# Gauge pressure
Subtract atmospheric. ITS THE **DIFFERENCE**
$$ P_\text{gauge} = P_\text{abs} - P_\text{atm} $$
# Pascals Law
Adding pressure to a liquid adds to the pressure uniformly 

## Hydraulic principle
Small piston with small area is easier to move than  big piston with big area, so car go up.

$$ A_1\Delta x_1 = A_2\Delta x_2 $$
$$ F_1\Delta x_1 = f_2\Delta x_2 $$
# Barometer
Tub of mercury
$$ P_{atm} = \rho_{hg}gh$$
$$ 1\ atm = \ 0.76\ mHg$$
# Buoyancy
An upward force of an object immersed in a liquid. Happens when the pressure on an object is less on top than on bottom. **Pressure difference is what matters**1 Buoyancy is the weight of the **displaced fluid**
$$ F_b = \rho_\text{fluid} Vg$$
$$ V_\text{displaced} = \frac w{\rho_{water}g}$$
Identifying theses variables are the goal: THE VOLUME IS THE **IMMERSED VOLUME**
## Iceberg
$$ \rho_\text{ice} = 0.9\rho_\text{water} $$
## Motion
Keep in mind many assumptions (i.e no friction, incompressible etc)

## Principle of continuity
	Fluid in neither created nor detroyed, thus any new liquid is added to the system.
Equation of continuity
$$ \rho_1 v_1 A_1 = \rho_2 v_2 A_2$$
As liquids are incompressible, we can remove rho!
$$ v_1 A_1 =v_2 A_2$$
So speed is low when tube is wide.



## Work done by pressure
([[Energy#Work]])

$$ W = F_x \cdot \Delta x$$
$$ W = PA\Delta y$$
$$ W = P\Delta V $$
$$ W = \int pdV $$
$$ dW = P\ dV$$
## Bernoulli Equation

Bernoulli IS **conservation of energy**
$$ \Delta K + \Delta U = W $$
$$ W = \frac 1 2 \Delta m(v_2^2-v_2^2) + \Delta mg(y_2-v_1)$$
$$ \text{INTO:} $$
$$ P + \frac 1 2 \rho v^2 + \rho gy = \text{constant}$$
$$ \text{Kinetic energy per kg} =  \frac 1 2 \rho v^2  $$
$$ \text{Potential energy per kg} = \rho gy $$
**REMEMBER**: After the liquid leaves the container it is atmoshperic! 
## Lift forces
Speed above is greater than the speed bellow the air foil
Pressure above is < Pressure bellow

## Flow rate

Velocity at depth on hole: $$v=\sqrt{2gh}$$
Flow rate of hole: $$ Q = aV $$
$$ Q = a\sqrt{2gh}$$
Time to fill volume: $$t = \frac VQ $$



_________________________
## Examples
To find the volume flow rate (\(Q\)) as a function of the pressure difference (\(\Delta P\)) between the two sections of the tube, we can use Bernoulli's equation and the continuity equation.

### Step 1: Apply Bernoulli's equation

Bernoulli’s equation for an ideal, incompressible fluid in steady flow is:

$$
P_1 + \frac{1}{2} \rho v_1^2 = P_2 + \frac{1}{2} \rho v_2^2
$$

Where:
- \(P_1\) and \(P_2\) are the pressures in the two tubes
- \(\rho\) is the density of the fluid (\(860 \, \text{kg/m}^3\))
- \(v_1\) and \(v_2\) are the fluid velocities in the two tubes

The pressure difference is defined as \(\Delta P = P_1 - P_2\), so Bernoulli’s equation can be rearranged as:

$$
\Delta P = \frac{1}{2} \rho (v_2^2 - v_1^2)
$$

### Step 2: Apply the continuity equation

The continuity equation for incompressible fluid flow is:

$$
A_1 v_1 = A_2 v_2
$$

Where:
- \(A_1 = \pi r_1^2\) and \(A_2 = \pi r_2^2\) are the cross-sectional areas of the tubes
- \(r_1 = 1.60 \, \text{cm} = 0.0160 \, \text{m}\) is the radius of the first tube
- \(r_2 = 0.800 \, \text{cm} = 0.00800 \, \text{m}\) is the radius of the second tube

Solving for \(v_2\) in terms of \(v_1\):

$$
v_2 = \frac{A_1}{A_2} v_1 = \frac{r_1^2}{r_2^2} v_1
$$

Substituting this into Bernoulli’s equation:

$$
\Delta P = \frac{1}{2} \rho \left( \left( \frac{r_1^2}{r_2^2} v_1 \right)^2 - v_1^2 \right)
$$

Simplifying:

$$
\Delta P = \frac{1}{2} \rho v_1^2 \left( \frac{r_1^4}{r_2^4} - 1 \right)
$$

Solving for \(v_1\):

$$
v_1^2 = \frac{2 \Delta P}{\rho \left( \frac{r_1^4}{r_2^4} - 1 \right)}
$$

$$
v_1 = \sqrt{\frac{2 \Delta P}{\rho \left( \frac{r_1^4}{r_2^4} - 1 \right)}}
$$

### Step 3: Find the volume flow rate

The volume flow rate is given by:

$$
Q = A_1 v_1 = \pi r_1^2 v_1
$$

Substitute the expression for \(v_1\):

$$
Q = \pi r_1^2 \sqrt{\frac{2 \Delta P}{\rho \left( \frac{r_1^4}{r_2^4} - 1 \right)}}
$$

### Final Expression:

$$
Q = \pi (0.0160)^2 \sqrt{\frac{2 \Delta P}{860 \left( \frac{(0.0160)^4}{(0.00800)^4} - 1 \right)}}
$$

This is the volume flow rate as a function of the pressure difference \(\Delta P\).