Repetitive motion ([[Energy#Springs]])


Think of circular momentum ([[Angular math]], [[Centripetal Acceleration]])
$$ \omega= \frac V R $$
$$ \omega = \frac {d\theta}{dt}$$
$$ \omega = \sqrt\frac k v$$
$$ w^2 = \frac km$$

$$ x = R cos\Theta = R cos(\omega t) $$
$$ y = R sin\Theta $$

Time to complete a cycle (**PERIOD**) is:
$$ T = \frac {2\pi}{\omega} $$

Cycle Frequency:
$$ F = \frac \omega{2\pi} $$
$$ \phi=\frac{\arcsin\left(\frac{x\left(t\right)}{A}\right)}{wt} $$
## Spring mass system

$$ F = -kx $$
Newtons 2nd
$$ -kx = ma $$
**NOT CONSTANT ACCELERATION!**
What we need is `x(t)` aka x as a function of time
$$ \frac {d^2x}{dt^2} = \frac {-k}{m}x \  \  OR\  \  \frac{d^2x}{dt^2}+\frac kmx=0$$
$$ \frac{d^2x}{dt^2}=-\frac kmx $$
THIS IS A DIFFERENTIAL EQUATION
Uggghghghgh, we can try...


A function whose second derivative is a negative multiple of the OG function:
* A function of its own derivative is e<sup>x</sup>
* uhuhuhuhu sin(x) is a negative multiple of its own second derivative. 
* chain rule
	* x(t) = sin(wx)
	* x'(t) = wcos(wx)
	* x''(t) = -w<sup>2</sup>sin(wx)
		* This could work...
		* Let w<sup>2</sup> = k / m 
$$ x(t) = sin \omega t$$
$$ x(t) = sin (t\cdot\sqrt{\frac km})$$

$$  \frac {d^2x}{dt} = -\omega^2 sin(\omega t) $$
This is **not** the only solution. You can add **AND** multiply by **ANY CONSTANT** and it **WILL NOT** change the second derivative!


We can also add inside the function
SO THIS IS VALID:
$$ x(t) = A sin (t\cdot\sqrt{\frac km} + \phi) + \beta$$
$$ \frac{d^2x}{dt^2}=\omega^2x(t) $$



Omega = the angular frequency
$$ \omega = \sqrt\frac k m $$
A is the amplitude
PHI is the "Phase constant"
	The "Phase angle" is the part **inside the sine**

Time to complete a cycle (**PERIOD**) is:
$$ T = \frac {2\pi}{\omega} $$

Cycle Frequency:
$$ F = \frac \omega{2\pi} $$
Hertz
__________________________
$$ x(t) = A\cdot sin(\omega t + \phi) $$
ALSO:
$$ x(t) = A\cdot cos(\omega t + \phi) $$

But engineers do:
$$ x(t) = A\cdot sin(2\pi f t + \phi) $$
but that complicates things

## Energy

$$ E_{tot } = \frac 1 2 kA^2 $$

![[Pasted image 20241029104319.jpg]]

## Drag 
Drag force is a negative multiple of velocity
$$ F_d = -bv $$
Newtons 2nd:$$ -kx -bv = ma $$
AKA
$$ -kx-b\frac{dx^{1}}{dt}=m\frac{dx^{2}}{dt} $$
Rearrange to:
$$ b\frac{dx^{1}}{dt}+m\frac{dx^{2}}{dt}+kx=0 $$

Solve with magic that is hidden from us:
$$ x(t) = e^{\frac {-b}{2m}t} sin(\omega t+\phi)$$
Damping slows it down so w =
$$ \omega(t) = \sqrt{w_0^2 - \ (\frac b {em})^2}$$
Where w_0 is the unhampered frequency
$$ \omega_0^2 - \frac km$$

So:
$$ \omega(t) = \sqrt{\frac km - \ (\frac b {em})^2}$$
However the second term can be negative, so things go imaginary. (But keep in mind this happens in reality, so we need imaginary numbers to exist in reality)

But sine happens to work for imaginary numbers, ![[Screenshot_20241031_103616.png]]
$$ x(t) = e^{\frac {-b}{2m}t} sin(\omega t+\phi)$$
![[IMG_20241031_103331215.jpg]]
## Simple harmonic oscillator

$$ \frac{d^2x} {dx^2}  =-\omega^2x \to Asin(\omega t+\phi)$$
________________
Finding phi:
$$ \phi=\frac{\arcsin\left(\frac{x\left(t\right)}{A}\right)}{wt} $$

BUT REMEMBER sine is double sided
____________________________
Simple pendulum with SMALL ANGLES aproximation 

$$ \omega^2 = \frac gL $$


_______________________
## Driving force

$$ F_d = F_Csin(\omega_dt+\phi)$$
where omega d is the driving frequency

Oscillator will eventually converge to the driving frequency. 

$$ A = \frac {F/m}{\sqrt{(\omega_d-\omega)^2 + (\frac b {2m})^2}} $$

| Slow compared to natural frequency   | Matches speed easily                         |
| ------------------------------------ | -------------------------------------------- |
| Close to natural frequency           | Accelerates quickly                          |
| Faster compared to natural frequency | Have a hard time keeping up to driving force |
Frequencies away from natural have low aplitude![[Pasted image 20241031104614.jpg]]
_________________________
## Forced oscillation
Driving frequency = natural frequency
Recall 
$$ \omega^2 = \frac km $$$$ F = \frac \omega{2\pi} $$
$$ P = \frac {2\pi}\omega $$

Toddler bed problem
$$ a_{max} = \omega^2A=-g $$