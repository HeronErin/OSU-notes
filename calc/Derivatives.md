Differentiable == continuous 
BUT
Continuous != differentiable


See: [[Limits]]


Reasoning:

If f'(a) exists
$$ \lim_{h \to 0} \frac {f(a+h) - f(a)}h$$
Need to show f is continuous at a MEANING:
$$ \lim_{x \to a} f(x)=f(a) $$
Step 1:
$$ \lim_{h \to 0} (f(a+h)-f(a)) = 0 $$
As
$$ \lim_{h \to 0}h = 0 $$
Step 2:
$$ \lim_{h \to 0} f(a+h) = \lim_{h \to 0}(f(a+h) - f(a) + f(a)) $$
$$ \lim_{h \to 0} f(a+h) = f(a) $$

-------------
## Product rule
$$ \frac d{dx}(f(x)g(x)) = f'(x)g(x) + f(x)g'(x) $$
## Quotient Rule
$$ \frac d{dx} \frac {f(x)}{g(x)} = \frac {f'(x)g(x) - f(x)g'(x)}{g(x)^2}$$
## Chain rule
Composition MAGIC
$$ \frac d{dx} f(g(x)) = f'(g(x))g'(x) $$
## Ln
 $$ \frac d{dx} ln(x) = 1/x $$
 $$ \frac d{dx} (log_bx) = \frac 1{ln b} * \frac 1x$$
 See: [[Logs]]
## Tangent line
At know point
$$ y−y_0​=m(x−x_0​) $$
$$ y=m(x−x_0​) + y_0​ $$
$$ y=f'(x_0)(x−x_0​) + f(x_0) $$

## Trig function derivatives

![[Pasted image 20240920140430.jpg]]
![[Screenshot_20241001_135116.png]]
______________
## Higher Order  Derivatives
Get the derivative of the derivative
## Implicit Differentiation
Classic Example: $$ x^2 + y^2 = 1 $$
Circle of rad 1
$$ y^2 = 1-x^2 $$
$$ y = \pm \sqrt{1-x^2} $$ $$ y' = ...$$
BUT THIS SUCKS

Instead find dy/dx: (Remember y depends on x, need dy/dx)
$$ \frac d{dx} (x^2) + \frac d{dx} (y^2)  = \frac d{dx}(1) $$
$$ 2x + 2y \frac d{dx} = 0 $$
$$ 2y\frac d{dx} = -2x $$
$$ \frac d{dx} = \frac {2x}{-2y} = \frac  {-x}y $$
WE PUT dy/dx AFTER y as it is the DEPENDENT VARIABLE!


Solving for ln(x)'
$$ x = e^{ln(x)}$$
$$ 1 = e^{ln(x)}ln'(x)$$
$$ 1 = xln'(x)$$
$$ ln'(x) = 1/x$$
## High order implicit
$$ x^2 + y^2 = 1$$
find $$ \frac {d^2y}{d^2x} $$
$$...$$$$ \frac {dy}{dx} = -\frac xy $$
$$ \frac {d^2y}{d^2x} = -\frac {1y-x\frac {dy}{dx}}{y^2} $$
$$ \frac {d^2y}{d^2x} = -\frac {y-x\frac {-x}{y}}{y^2} $$
$$ \frac {d^2y}{d^2x} = -\frac {y+\frac {x^2}{y}}{y^2} $$
$$ \frac {d^2y}{d^2x} = -\frac {y^2+x^2}{y^3} $$
Knowing: $$ x^2 + y^2 = 1$$
We can do:
$$ \frac {d^2y}{d^2x} = -\frac {1}{y^3} $$

## Logarithmic differentiation 
Example, find the derivative of x<sup>x</sub>
1. ln(f(x)) = ln(x<sup>x</sup>)
2. ln(f(x))  = x ln(x)
3. d/dx ln(f(x)) = d/dx( x ln(x) )
$$ \frac 1 {f(x)} f'(x) = 1 * ln(x) + x *1/x $$
$$ \frac 1 {f(x)} f'(x) = ln(x) + 1 $$
$$ f'(x) = f(x)ln(x) + f(x) $$
$$ f'(x) = x^xln(x) + x^x $$

## Derivatives of inverse
You might need to restrict the original domain (inverse range) to make one to one
$$ \frac d{dx} (f^{-1}(x)) = \frac 1 {f'(f^{-1}(x))} $$
## Related Rates of change
Suppose we know
1) A relation between x at y
2) The rate of change of x with respect to t
From this we can find the rate of change at y with t

Ex x<sup>2</sub> + y<sup>2</sup> = 25
We know (3, 4) exists at t=2
And that dx/dt = -7
Problem Find dy/dt at t=2
$$ 2x\frac{dx}{dt}  + 2y\frac{dy}{dt} = 0 $$
Plug in x=3, y=4, and dx/dt = -7

$$ 2(3)(-7)  + 2(4)\frac{dy}{dt} = 0 $$
$$\frac{dy}{dt} = \frac{-2(3)(-7)}{2(4)} = 5.25 $$

Ex2:
The radius of a circle is increasing at a rate of 2 in/sec. That is the rate the at which the area is increasing at 12 in?

So we know $$ \frac {dr}{dt} = 2 $$
and
$$ a = \pi r^2 $$
$$ \frac{da}{dt} = \pi 2r\frac {dr}{dt} $$
$$ \frac{da}{dt} = 48\pi $$

## Mean value theorem

If f'(x) = 0, it is necessary a constant function? 
**SOMETIMES**

Ex:
$$ f(x) = \frac x{|x|}$$
So it is only true of a function on its domain is differentiable and continuous. 
## L'Hôpital's rule

If f and g are differentiable near x=a

and
$$ |\lim_{x\to a}f(x)|= |\lim_{x\to a} g(x)| = 0\ OR\ \infty$$
at $$ g'(x) \ne 0 $$
then 
$$ \lim_{x\to a} \frac {f(x)}{g(x)} = \lim_{x\to a} \frac {f'(x)}{g'(x)} $$


The key is just to put it in that form:
Ex:

$$ f(x)^{g(x)} = e^{g(x)ln(f(x))} =  e^{\frac {g(x)} {\frac 1 {ln(f(x))}}}$$
