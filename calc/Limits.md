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

