$$ \lim_{x\to x}f(x) = L$$
If the values of f can be made as close as *you like* to L for all x sufficiently close to but not equal to, a ("Two-sided" limit)
_______________________
$$ \lim_{x\to 3+}f(x) = L$$
One sided limit, approaching for the positive towards the negative. 
# Limit Laws
1. Arithmatic
2. Composition:  if f is continuous as m and g is continuous as m $$ \lim_{x \to a} f(g(x)) = \lim_{x -> \to a} f(\lim_{x \to a} g(x)) = f(m) $$
3.  Squeezing $$ \lim_{x \to 2} ln(sin(x-2) + e^x*sin(\frac {\pi x}{4})) = ln(\lim_{x \to 2} (sin(x-2) + e^x*sin(\frac {\pi x}{4}))) \ \ ;\ etc $$
5. All famous functions are continuous on their domain.
## Squeeze Theorem
If the only thing we know about a function is its bounds. Ex:
g(x) <= f(x) <= h(x) 
$$ \lim_{x \to a} g(x) = \lim_{x \to a} h(x) = L $$
THEN
$$ \lim_{x \to a} f(x) = L $$
ex:
find:
$$ \lim_{x \to 0} x^2cos(1/x) $$
The problem is that:
$$ \lim_{x \to 0} cos(1/x) $$ DOES NOT EXIST:
SOLUTION, squeeze it:
-1 <= cos(1/x) <= 1
MULT by x^2
$$ -x^2 <= x^2 cos(1/x) <= x^2 $$
$$ \lim_{x \to 0} -x^2 =\lim_{x \to 0} x^2 = 0 $$
SO:
$$ \lim_{x \to 0} x^2cos(1/x) = 0 $$
________________________
### INDETERMINATE FOR = 0/0
$$ \lim_{x \to 1} \frac{\frac{1}{x+1} - \frac{3}{x+5} }{x-1} $$
Mult to and bottom by: (x+1)(x+5)
$$ \lim_{x \to 1} \frac {x+5 - 3(x+1)}{(x-1)(x+1)(x+5)} = \frac {x+5 - 3x -3} {(x-1)(x+1)(x+5) } =  = \frac{-2(x-1)}{(x-1)(x+1)(x+5)} = \frac {-2}{(x+1)(x+5)} $$
$$ = -\frac {1}{6} $$
<center>indeterminate -> determinate</center>
__________________________________________________
$$ \lim_{x \to -5} \frac{\sqrt {4-n} - 3} {n+5} $$
Strategy: top and bottom by "conjugate quantity"
Reason: (a-b)(a+b) = aa - bb
Get rid of sq root!

$$lim_{x \to -5} \frac {(\sqrt {4-n} - 3)(\sqrt {4-n} - 3)} {(n+5)(\sqrt {4-n} - 3)} = \frac {4-n-9}{ {(n+5)(\sqrt {4-n} - 3)} } = \frac {-1(n+5)}{(n+5)(\sqrt{4-n}+3)} = \frac {-1}{\sqrt{4-n} + 3} $$
$$ = \frac {-1}{6} $$
_________________________
$$ \frac{z-1}{\sqrt{2-z}-1} $$
$$ \frac{\left(z-1\right)\left(\sqrt{2-z}+1\right)}{\left(\sqrt{2-z}-1\right)\left(\sqrt{2-z}+1\right)} $$
$$ \frac{\left(z-1\right)\left(\sqrt{2-z}+1\right)}{2-z-1} $$
$$ \frac{\left(z-1\right)\left(\sqrt{2-z}+1\right)}{-1\left(z-1\right)} $$
$$ \frac{\sqrt{2-z}+1}{-1} $$

FIll in where z = 1
and $$ -2 $$
______________________________
## Infinite Limits
$$ \lim_{x \to 0} \frac {x} {x^3} = \frac {1} {x^2} = indeterminate = oo $$
$$ \lim_{x \to 0} \frac {x} {0}  = determinate = DNE $$

Infinity is not a value, but a destination. 
_____________
$$ \lim_{x \to -2} \frac {e^x}{(x+2)^3} $$

$$ \lim_{x \to -2+} \frac {e^x}{(x+2)^3} = oo $$
$$ \lim_{x \to -2-} \frac {e^x}{(x+2)^3} = -oo $$
SO the double sided limit does **not** EXIST.
______________________
$$ \lim_{x \to 3} \frac{x^{2}-9x+14}{x^{2}-5x+6} = \frac {(x-7)(x-2)}{(x-3)(x-2)} $$
FORM
$$ \frac{9-27+14}{9-15+6}=-\frac{4}{0} $$
form is %/0, **form does not exist!**
$$ \lim_{x =\to 3+} \frac {x-7}{x-3}  = -oo $$

as (x - 3) for the + as approaching 0, so inf, and x-7 is -5
_____________
$$ \lim_{x \to 1} \frac {sin\ x} {\sqrt{2-x^2} - 1} $$
FORM
$$ \frac {+N}{0}$$
________
$$ \lim_{x \to 1} \frac {(sin\ x)(\sqrt{2-x^2} - 1)} {(\sqrt{2-x^2} - 1)(\sqrt{2-x^2} - 1)} =\lim_{x \to 1} \frac  {(sin\ x)(\sqrt{2-x^2} - 1)}{1-x^2} $$
$$ \lim_{x \to 1^+} \frac {(sin~x)(\sqrt{2-x^2} - 1)}{(1-x)(1+x)} or \frac {+}{(0+)(+)} = +oo $$
$$ \lim_{x \to 1^-} \frac {+}{(-0)(+)} = oo$$
NO DOUBLE SIDED = DNE
________________
$$ f(x) = $$
$$ \frac{2x-3}{x-2}~~~~;~~~~~ x < 2 $$
$$ \frac {x^2+5x+6}{x^2-4}~~~~;~~~~~x > 2$$
$$\lim_{x \to 2^+} f(x) $$
form 0/0
$$ \frac {x^2+5x+6}{x^2-4} = \frac {(x-3)(x-2)}{(x-2)(x+2)} = \frac {-1}{4} $$
FORM N/N
$$ \frac{2x-3}{x-2} = + / (-0) = -oo $$
___________________
$$ \lim_{x \to +oo} \frac {x}{x^2-4} = \frac {\frac {1}{x}}{1- \frac 4{x^2}} =0 $$
only 1 HA, y = 0
**divide by highest x^2**\
___________________
$$ \lim_{x \to oo} \frac {\sqrt{2x^2 +1}}{3x-5} $$
Mult by 1/x
$$ \frac{\sqrt{\frac 1{x^2}} \sqrt{2x^2+1} }{3-\frac5 x} = \frac {\sqrt{\frac1{x^2}(2x^2+1)}}{3-\frac 5x} = \frac {\sqrt2}3$$

$$ \frac 1x=\sqrt{\frac 1{x^2}} $$
_________________________________
$$ f\left(x\right)=\frac{\sin x+7x}{2x} $$
H.As
$$ f\left(x\right)=\frac{\sin x}{2x}+\frac{7x}{2x} $$
$$ f\left(x\right)=\frac{\sin x}{2x}+\frac{7}{2} $$
$$ Know:\ -1\ \le\ \sin x\ \le\ 1 $$$$ -\frac{1}{2x}\le\frac{\sin x}{2x}\le\frac{1}{2x}$$
$$ lim_{x \to oo} \frac {-1}{2x} = 0$$
$$ lim_{x \to oo} \frac {1}{2x} = 0$$$$ lim_{x \to oo} f(x) = 7/2 $$
V.A:
**1/2** as x = 0
_________________
Q4
$$ g(v) = \frac {v^3-3 v^2-3 v+2}{4 v^2+\sqrt {v^6-4 v^3+3 v^2}+2 v-3} $$
Divide by v^3

$$ g(v)=\frac{1-\frac{3}{v}-\frac{3}{v^{2}}+\frac{2}{v^{3}}}{\frac{4}{v}+\sqrt{\frac{1}{v^{3}}\left(v^{6}-4v^{3}+3v^{2}\right)}+\frac{2}{v^{2}}-\frac{3}{v^{3}}} $$
$$ g(v)=\frac{1-\frac{3}{v}-\frac{3}{v^{2}}+\frac{2}{v^{3}}}{\frac{4}{v}+\sqrt{\left(1-\frac{4}{v^{3}}+\frac{3}{v^{4}}\right)}+\frac{2}{v^{2}}-\frac{3}{v^{3}}} $$
Toward infinity resolves to 1/1
______________________________________
## Intermediate value theorem
if f is a continuous function on \[A, b] and c is between f(a) and f(b)
There is (at least one) x value between  the two where f(d) = c

aka if f(a) goes to f(b) then it is continuous
Show that the equation has a solution in (0, pi)
$$ x^3 = x + sin x + 1$$
so:
$$ x^3 - x - sin  x - 1 = 0 $$
f(x) is continuous from (0, pi)
f(0) = -1
f(pi) = pi^3 - pi - 0 - 1
pi > 3
pi(pi^2 - 1) - 1
\> 3 (9-1) - 1

0 is between f(0) and f(pi)
**IT EXISTS**
