Repetitive motion ([[Energy#Springs]])


Think of circular momentum ([[Angular math]], [[Centripetal Acceleration]])
$$ \omega= \frac V R $$
$$ \omega = \frac {d\theta}{dt}$$


$$ x = R cos\Theta = R cos(\omega t) $$
$$ y = R sin\Theta $$
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