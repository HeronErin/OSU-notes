Difficult due to being curves

## The exact amount
* The exact area is given by
 $$ \int^\text{final}_\text{initial} f(x)dx$$
## The approximation

But we can't easily find that, so we need to approximate it using infinitely many triangles
Steps:
	1. How many triangles?
		1. The more the better
	2. Write down the "Grid points" with equal spacing
	3. Get the area of each
	$$ A_t = \frac 12 \text{Base} \cdot \text{Width} $$
$$ t=\frac{\left(F-I\right)}{a} $$
$$ \sum_{n=1}^{a}\left(t\cdot f\left(I+t\left(n+1\right)\ \right)\right) $$
n+1 makes it an underestimate
Simplify to:
$$ t\cdot \sum_{n=1}^{a}\left(f\left(I+t\left(n+1\right)\ \right)\right) $$
## Riemann sum
![[Screenshot_20241104_134927.png]]
![[Screenshot_20241104_134836.png]]
___________
Ex
$$ F(x) = 16-x^2 $$
Real answer:
$$ \int^3_1 (16-x^2)dx = 23\frac13$$
BUT HOW????????????
Its complicated
