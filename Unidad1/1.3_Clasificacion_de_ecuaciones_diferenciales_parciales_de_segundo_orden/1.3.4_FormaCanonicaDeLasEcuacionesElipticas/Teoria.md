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
