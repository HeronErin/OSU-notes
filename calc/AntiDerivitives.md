
Find something whose [[Derivatives]] IS a function.

Ex:
$$ f'(x) = 5 $$
With some head scratching we can find:
$$ \int f(x) = \frac 2 5 e^{5x} $$
Note:
Their is an **infinite family** of functions who can make said anti derivative.
This class uses the integral symbol aka "indefinite integral"
$$ \int f(x)dx$$

| Deriv              | Function                                                               |
| ------------------ | ---------------------------------------------------------------------- |
| $$ \frac 1 x $$    | $$ln(abs(x))$$                                                         |
| $$e^{nx}$$         | $$\frac {e^{nx}}n$$                                                    |
| $$ a^{kx} $$       | $$ \frac {a^{kx}}{kln(a)} $$                                           |
| $$cos(kx)$$        | $$ \frac 1k sin(kx)$$<br>See [[Derivatives#Trig function derivatives]] |
| $$sin(kx)$$        | $$ -\frac 1k cos(kx) $$                                                |
| $$sec^2(x)$$       | $$tan(x)$$                                                             |
| $$sec(x)tan(x)$$   | $$sec(x)$$                                                             |
| $$csc^2(x)$$       | $$-cot(x)$$                                                            |
| $$ csc(x)cot(x) $$ | $$ -csc(x) $$                                                          |
|                    |                                                                        |
Rules:
Sum rules:
$$ \int(f(x) \pm g(x))dx = \int f(x)dx \pm \int g(x)dx$$
Constant product rules:
$$ \int Kf(x)dx = K\int f(x)dx $$
Constant exponentiation rules:
$$ \int f(x)^N dx = \frac{\int f(x)^{N+1}dx}{N+1}$$
BUT IF NEGATIVE ONE
$$ \int f(x)^{-1} dx = ln(abs(x)$$

![[Screenshot_20241101_135957.png]]