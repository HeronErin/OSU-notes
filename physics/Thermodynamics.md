$$ P = \frac FA$$
$$ dV = -Adx$$
$$ dW = Fdx = -PdV$$
$$ W = -\int PdV$$
$$ dx = \frac{-dV}A$$
$$ Q = mc\Delta T$$
$$ \text{Power} = \frac{\text{Work per cycle}}{\text{time per cycle}} $$
## Ideal gas
Similar to: [[Fluid Dynamics]]

Simplified modal of gases (Ie room temp air)
	Gas molecules don't interact with one another
		Low density
	Ignore the container or **any** other forces
	The molecules uniformly fill the container
$$ PV = nRT $$
	n is the amount of gas in moles
	R is the constant (8.314 J/mole)
	Sometimes written as $$ PV=NkT $$
	Where N is amount of and k is Boltzmann constant
### Ideal gas specific heat
$$ \Delta E_{int} = Q = nC_r\Delta T $$
$$ C_r = \text{Molar specific heat at constant volume} $$
Constant pressure:
$$ \Delta E = Q+w $$
$$ w = -P\Delta V$$
$$ Q = nC_p\Delta T$$
$$ C_p = \text {Molar specific heat at constant pressure}$$
![[Screenshot_20241112_104419.png]]
## Thermodynamic work
$$ dW = Pdv$$
$$\Delta E_{int} =W+Q $$
$$ Q = nC_p\Delta T = nC_v\Delta T + P\Delta V$$
## Moles
Amount that can **roughly** fit in your hand
$$ N_a = 6.02*10^{23} $$
**Avogadros's NUMBER**
	1g of hydrogen
	$$ N = m/M $$
	He has a molor mass of 4.003 g/mol

## Temperature
Hotter object higher temperature
* True except for some states of matter
**Thermal equilibrium** = Two objects do **NOT** exchange temp
		Objects without equilibrium attempt to become a state of equilibrium
	Same temperature
## Measuring temperature
Most commonly the volume of a liquid
	* Also volume of a gas, and pressure of gas
	* Or Electrical resistance
		* Can't Fit a foot of Hg in a cpu
	* Or color
**MOST FORMULAS NEED KELVIN!**

## Kelvin
Relative to absolute zero.
Celsius -273
## Fahrenheit
Ice = 32F
Steam  = 212
$$ T_f = \frac 95T_c+32$$
$$ T_c = \frac 95(T_f - 32) $$

## Participation theorem 
$$ E_{avg} = \frac 1 2 k_BT\ \  \ \ \text{Per degree of freedom} $$
$$ K_B = 1.38*10^{-23} $$

Air at room temp
$$ C_v = \frac 52R$$
$$ v_{rms} = \sqrt{\bar{v^2}} = \sqrt{\frac{2K_\text{Kelvin}}{m_o}} $$
$$M_{HE} = 6.64*10^{-27}$$
$$M_{Ar} = 6.63*10^{-26}$$
## Thermal expansion

**SMALL** **EXPANSIONS** ONLY:
$$ \frac {\Delta L}L = \alpha\Delta T$$
$$ \Delta L = \alpha L\Delta T$$
* Alpha is the coefficient of linear thermal expansion. (Unit C^-1, K^-1)
* Different for each material
* All dimensions at once
	* X, Y, and Z
	* Uniform expansion

For solids a ~ 10<sup>-5</sup> to 100<sup>^6</sup>
For liquids 10<sup>-6</sup>
![[Screenshot_20241104_103042.png]]![[Pasted image 20241104103404.jpg]]
### Water
However water is strange and increases in size as it cools

![[Screenshot_20241104_103857.png]]
## Ideal Gas Framework
![[Screenshot_20241104_105136.png]]
## Foil approximation 
For x < 1
$$ (1+x)^3 \approx 1+3x $$
## Work
[[Energy#Work]]
$$ dW = -PdV$$$$ W = -\int PdV$$
$$ k = \frac 2 3 NK_BT$$

We need to find the area under the graph, this can be hard, or simple. ( [[Approximating the area under a curve]])
### Constant volume
Work = 0
dE<sub>int</sub> = Q
### Constant pressure
w = -PdV

$$ c_p = c_v + \text{work term} $$
$$ C_v = \frac 2 3 R $$
$$ c_v = \frac 5 2 R $$
WORKS WITH HELIUM BUT NOT HYDROGEN
### Constant temperature
`Adiabatic process` 
`Isothermal`

No heat transfer
dE = w
![[Screenshot_20241106_102254.png]]
$$ w = -Q $$
## Kinetic Theory
Consider the motion of molecules. A fluid/gas is just a sum of its components.

Newton tells us that the molecule hitting the wall causes an equal an opposite reaction
**THIS IS PRESSURE**
$$ \Delta \bar p = \bar F\Delta t$$
$$ P = \frac 2 3 \cdot \frac N V \cdot(\frac 1 2 m\bar{v^2}) $$
Where v bar is the average(squared velocity) NOT average(speed) squared
And capital V is volume
And N is number of moles
(rms = Root mean square)

$$ \sqrt{\bar {v^2}} = \text {Root mean squared average} $$
Also remember:
$$ PV = nRT = Nk_BT$$
**SO:**
$$ \frac 1 2 m \bar {v^2} = \frac 3 2 K_bT$$

## Cyclic process
A process whose starting point is the same as its end
Work is done to the outside world. **Heat turns into work**
![[Screenshot_20241118_104228.png]]
Efficiency: 
$$ e = \frac {W_{tot}}{Q_{in}} $$

## Heat capacity

$$ Q = C\Delta T $$
where C is the **heat capacity** of the object
$$ c = \frac C m $$ $$ C = mc $$
$$ Q = mc\Delta T$$
$$ Q_m + Q_c = 0 $$
For no energy leaving the system
## Calorimetry 
The science of how heat changes (See [[#Heat capacity]])

## Phase changes of matter
Solid <--> Liquid   // Melting
Liquid <--> Gas     // Boiling

Solid <--> Gas       // Sublimation
![[hidden energy.png]]
![[Screenshot_20241112_103052.png]]
## Latent heat
Energy needed to melt a unit of liquid

$$ Q=mL$$
$$ L_f = \text{Heat of fusion}$$$$ L_v = \text{Heat of vaporization}$$$$ L_s =   \text{Heat of sublimation}$$


__________________
Random heat transfer problem
![[IMG_20241107_103506891.jpg]]
___________

A 40g ice as 0C is placed in 1kg of water at 10c, does it all melt?


We need to make assumptions and see if true.
	In full melt:
		$$ m_wc_w\Delta T_w + m_IL_I + m_IC_w\Delta T_I = 0 $$
		$$ m_wc_w(T_{f} - T_{iw}) + m_IL_I + m_IC_w(T_{f} - T_{iI}) = 0 $$
		$$ T_f = \frac {m_wc_wT_w - m_IL}{(m_w+m_w)c_w} $$



____________
1 . The mass of a hot-air balloon and its cargo (not including the air inside) is 120 kg. The air outside is at 10.0°C and 101 kPa. The volume of the balloon is 510 m3. To what temperature must the air in the balloon be warmed before the balloon will lift off? (Air density at 10.0°C is 1.244 kg/m3.)

HOTTER AIR = MORE DENSE
$$ F_b - F_g = 0 $$
$$ \rho_{cold} Vg - \rho_{hot} Vg - mg = 0 $$
$$ \rho = \frac mV$$
$$ \rho = \frac {nM}V$$
$$ M = \text{Molar mass} $$

2.An open cylinder of air has a radius of 36.0 cm and a height of 50.0 cm, as shown in figure (a).

![[19-p-062.gif]]
The air pressure is 1.00 atm and the temperature is 14.5°C. A 25.0 kg piston is then lowered onto the cylinder, forming an airtight seal, as shown in figure (b). The air inside is compressed **until the piston reaches equilibrium** (mechanical and thermal), and at this point the piston is a height _h__i_ from the bottom of the cylinder. Lastly, a 30.0 kg dog steps onto the piston, and the air in the cylinder again compresses, as show in figure (c). After reaching equilibrium, the air inside is again at 14.5°C, and the height of the piston decreases a distance Δ_h_ as shown.

**NO CHANGE IN TEMP**
$$ PV=nRT $$
$$ P_B = P_{atm} + P_{piston} $$
$$ P_C = P_{atm} + P_{piston} + P_{dog} $$


 ________________________
 ![[IMG_20241119_104016277_HDR.jpg]]