# Ecuaciones diferenciales parciales tipo elípticas

Para este tipo de ecuaciones se tiene una forma compleja de $\frac{dy}{dx}$. Sea $\varphi(x,y)=cte$ una integral compleja de:

$$\frac{dy}{dx} = \frac{a_{12}+\sqrt{a_{12}^{2}-a_{11}a_{22}}}{a_{11}}$$

Entonces $\varphi^{*}(x,y)$ (la compleja conjugada de $\varphi(x,y)$), sera la integral comppleja de:

$$\frac{dy}{dx} = \frac{a_{12}-\sqrt{a_{12}^{2}-a_{11}a_{22}}}{a_{11}}$$

Sea $\xi=\varphi(x,y)$ y $\eta=\varphi^{*}(x,y)$ 

Ahora bien, en las ecuaciones tipo elípticas se introducen las variables: 
$$\alpha= \frac{\varphi+\varphi^{*}}{2}$$

$$\beta=\frac{\varphi-\varphi^{*}}{2i}$$

entonces:

$$\xi=\alpha + i\beta$$

$$\eta= \alpha-i\beta$$

Además de cambiar la forma canónica de la ecuación tipo elíptica, nos evitaremos trabajar con cantidades complejas.

Como antes, se exige que $\bar{a_{11}}=0$

$$\bar{a_{11}=a_{11}\xi_x^{2}+2a_{12}\xi_x\xi_y+a_{22}\xi_y^{2}}$$

$$=a_{11}(\alpha_x+ i\beta_x)^{2} +2a_{12}(\alpha_x+ i\beta_x)(\alpha_y+ i\beta_y)+a_{22}(\alpha_y+ i\beta_y)^{2}$$

$$=a_{11}\alpha_x^{2}+2a_{11}\alpha_x i\beta_x-a_{11}\beta_x^{2}+2a_{12}(\alpha_x \alpha_y + \alpha_x i \beta_y+ i \beta_x \alpha_y + i^{2} \beta_y \beta_x)+a_{22}\alpha_y^{2}+ 2a_{22}\alpha_y i \beta_y - a_{22}\beta_y$$

## Rectas Características

Recordando la ecuación característica:

$$a_{11} \frac{dy}{dz} + 2a_{12} \frac{dy}{dx} + a_{22} \frac{dz}{dx} = 0$$

La cual se puede escribir como:

$$a_{11} \left( \frac{dy}{dz} \right)^2 - 2 a_{12} \frac{dy}{dx} + a_{22} = \lambda_2$$

Cuyas soluciones son :

$$
\frac{dy}{dx} = \frac{a_{12} + \sqrt{a_{12}^2 - a_{11} a_{22}}}{a_{11}} = \lambda_1
$$

$$
\frac{dy}{dx} = \frac{a_{12} - \sqrt{a_{12}^2 - a_{11} a_{22}}}{a_{11}} = \lambda_2
$$

Sabemos que:

$$\frac{dy}{dx} = \lambda_1$$

$$y = \lambda_1 x + c_1 \quad \text{con} \quad c_1 = \text{cte}$$

De igual manera:

$$y = \lambda_2 x + c_2 \quad \text{con} \quad c_2 = \text{cte}$$

Estas relaciones se consideran como rectas ecuacionales, junto con el
lema #2 se tiene la función $\Phi(x, y) = \c$ tal que permite encontrar
la forma canónica.

Por lo tanto, $$y - \lambda_1 x = \Phi(x,y) = \xi$$
$$y - \lambda_2 x = \Phi(x,y) = \eta$$

**Obs.:** Cuando se trabaje con ecuaciones tipo elípticas:

$$\frac{dy}{dx} = z_{x} \quad \rightarrow \text{número complejo}$$

$$\frac{dy}{dx} = z^{*}_{x} \quad \rightarrow \text{complejo conjugado}$$

Donde:

a) $$y = z_x + \xi =  z_x + (\alpha + i\beta)$$

b) $$y = z^{*}_{x} + \eta = z^{*}_{x}+ (\alpha - i\beta)$$

Sumando $a)$ y $b)$

$$2y = (z_x + z^*_x) x + 2\alpha$$

$$2y = 2{Re}(z_x) x + 2\alpha$$

$$y = {Re}(z_x) x + \alpha$$

$$\alpha= y - {Re}(z_x) x$$

Restando $a)$ y $b)$
