Just like in one dimension, we can take integrals of functions with two independent variables, $f\left(x,y\right)$. 

Similarly to Riemann Sums from Calculus One, we define double integrals in a similar way. 

$V=\lim_{\Delta\to0}\sum_{k=1}^{n}f\left(x_{k}^{\ast},y_{k}^{\ast}\right)\Delta A_{k}$ is this definition, where $f\left(x_{k}^{\ast}\right)$ is the height of the rectangle and $\Delta x_{k}$ is the width of the rectangle. 

Example 1. Find the volume under the surface f(x,y) $\ge$ 0 for (x,y) in region R. $R=\left\lbrace\left(x,y\right):a\le x\le b,c\le y\le d\right\rbrace$ (rectangular region, *assumes f(x,y) is continuous*)

Step 1. Partition R into n subintervals. 

i.e. $R_{1,}R_{2,}\ldots,R_{n}$ 

Step 2. Area of $R_{k}$

$\Delta A_{k}=\Delta y_{k}\Delta x_{k}$, width of rectangle $\Delta x_{k}$ and height of rectangle $\Delta y_{k}$. 

Step 3. Select points in $R_{k}$, 

$\left(x_{k}^{\ast},y_{k}^{\ast}\right.)$ $\in R_k$ 

Step 4. Approximate the volume under f(x,y) over $R_{k}$ as a rectangular box.
  

Example 2. $f\left(x,y\right)=5xy$ $R=\left\lbrace\left(x,y\right):0\le x\le1,0\le y\le2\right\rbrace$ 

$\int_0^2\int_0^15 xydxdy$ 

{note: take inside integral with respect to x, treating y as a constant}

$\int_0^2\frac{5x^2y}{2}\vert_0^1$ = $\int_0^2\frac{5y}{2}$ = $\frac{5y^2}{4}\vert_0^2$ = 5   