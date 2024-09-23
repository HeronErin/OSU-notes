Differentiable == continuous 
BUT
Continuous != differentiable

Reasoning:

If f'(a) exists
$$ \lim_{h \to 0} \frac {f(a+h) - f(a)}h$$
Need to show f is continous at a MEANING:
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
$$ \frac d{dx}(f(x)f(x)) = f'(x)f(x) + f(x)g'(x) $$
## Quotient Rule
$$ \frac d{dx} \frac {f(x)}{g(x)} = \frac {f'(x)g(x) - f(x)g'(x)}{g(x)^2}$$
## Chain rule
Composition MAGIC
$$ \frac d{dx} f(g(x)) = f'(g(x))g'(x) $$
## Trig function derivatives

![[Pasted image 20240920140430.jpg]]
