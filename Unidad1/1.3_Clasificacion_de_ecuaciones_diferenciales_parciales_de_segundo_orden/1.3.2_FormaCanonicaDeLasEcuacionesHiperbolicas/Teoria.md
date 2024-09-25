## FORMA CANONICA DE LAS ECUACIONES HIPERBOLICAS ##

Partimos del siguinete lema :  

**Lema #2:** Si $\psi(x, y) = C$ es una integral general de la ecuación
diferencial ordinaria

a)  $$a_{11}dy^2 - 2a_{12}dxdy + a_{22}dx^2 = 0$$

entonces la función $z = \psi(x, y)$ satisface la ecuación

b)  $$a_{11} z_y^2 + 2a_{12} z_x z_y + a_{22} z_x^2 = 0$$

**Demostración:** Consideremos una curva integral de (a) que pasa por el
punto arbitrario $(x_0, y_0)$, donde $\psi(x_0, y_0) = C_0$.

**Observación:** $y_0 = f(x_0, C_0)$ $\rightarrow$ Crea una restricción.

Para todos los puntos en la curva, pediremos que se cumpla la siguiente
relación:

$$a_{11} \left( \frac{dy}{dx} \right)^2 - 2a_{12} \left( \frac{dy}{dx} \right) + a_{22} = a_{11} \left( -\frac{\psi_x}{\psi_y} \right)^2 - 2a_{12} \left( -\frac{\psi_x}{\psi_y} \right) + a_{22}$$

es decir,

$$a_{11} \left( \frac{\psi_x}{\psi_y} \right)^2 + 2a_{12} \frac{\psi_x}{\psi_y} + a_{22} = 0.$$


A una ecuación D.P. le corresponde una ED Característica EDP → ED.

Haciendo $\( x = x_0 \)$ en la última relación se tiene:

$$
a_{11} \psi^2_x(x_0, y_0) + 2 a_{12} \psi_x(x_0, y_0) \psi_y(x_0, y_0) + a_{22} \psi^2_y(x_0, y_0) = 0
$$

$$
a_{11} z^2_x(x_0, y_0) + 2 a_{12} z_x(x_0, y_0) z_y(x_0, y_0) + a_{22} z^2_y(x_0, y_0) = 0
$$

La ecuación $\( a_{11} dy^2 - 2 a_{12} dx \, dy + a_{22} dx^2 = 0 \)$ se llama ecuación característica para la ecuación:

$$
a_{11} u_{xx} + 2 a_{12} u_{xy} + a_{22} u_{yy} + F_1(x, y, u, u_x, u_y) = 0
$$

y sus integrales características.

Haciendo:

Si $\( \xi = \psi(x, y) \)$ con $\( \Psi(x, y) = \text{cte} \)$ y si tiene otra integral general de la ecuación (a), el coeficiente de $\( U_{\xi\xi} \)$ se reduce a 0:

$$
\overline{a_{11}} = 0
$$

Si $\( \eta = \xi(x, y) \)$ con $\( \Psi(x, y) = \text{cte} \)$ y si tiene otra integral general de la ecuación (a) independiente de $\( \Psi(x, y) \)$, se anula también el coeficiente de $\( U_{\eta\eta} \)$ cuando:

$$
\overline{a_{22}} = 0
$$

Las ecuaciones anteriores nos permiten encontrar dos expresiones de $\( \frac{dy}{dx} \)$:

$$
\frac{dy}{dx} = \frac{a_{12} + \sqrt{a_{12}^2 - a_{11} a_{22}}}{a_{11}}
$$

$$
\frac{dy}{dx} = \frac{a_{12} - \sqrt{a_{12}^2 - a_{11} a_{22}}}{a_{11}}
$$




Sea $D = a_{12}^2 - a_{11} a_{22}$. El signo de D determina el tipo de
ecuación: $$a_{11} u_{xx} + 2 a_{12} u_{xy} + a_{22} u_{yy}  = 0$$\
La ecuación se llamará en el punto P en el que se evalúa D, como:

-   Hiperbólica, si en el punto P se tiene $D > 0$.

-   Elíptica, si en el punto P se tiene $D < 0$.

-   Parabólica, si en el punto P se tiene $D = 0$.

**Observación:**

$$D = (\overline{a_{12}})^2 - (\overline{a_{11}})(\overline{ a_{22}})$$

$$\begin{pmatrix}
    \xi_{x} & \xi_{y} \\
    \eta_{x} & \eta_{y}
\end{pmatrix}=
\begin{pmatrix}
    \frac{\partial \xi}{\partial x} & \frac{\partial \xi}{\partial y}\\
    \frac{\partial \eta}{\partial x} & \frac{\partial \eta}{\partial y}
\end{pmatrix}$$

*Es el jacobiano de la transformación de variables y tiene que ser
diferente de cero.*

Consideremos una región $\Omega$ de todos los puntos en la cual la
ecuación es del mismo tipo. Para cada punto en $\Omega$ pasan dos
características.\
**Observación:** La cantidad $\xi_y$ $\eta_x$ - $\xi_x$ $\eta_y$ es el
jacobiano de la transformación de variables y tiene que ser diferente de
cero.

**Forma de la ecuación tipo hiperbólica**

Sus integrales generales $\Phi(x,y) = \text{cte}$ y $\Psi(x,y) = \text{cte}$ son constantes diferentes.

Determinan una familia de características. Se tiene:

$$U_{\eta} = \Phi \left( \xi, \eta, U, U_{\xi}, U_{\eta} \right)$$

con

$$\Phi = \frac{-F}{2a_{12}}$$

Forma canónica de las ecuaciones tipo hiperbólicas
