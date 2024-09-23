# Ecuaciones cuasi - lineales, lineales y no lineales.
Análogamente se escribe la ecuación para un número mayor de variables independientes.
La ecuación se llama lineal con respecto a las derivadas de orden mayor si ésta tiene la forma:

$a_{11}u_{xx}+2a_{12}u_{xy} + a_{22}u_{yy} + F_{1} (x, y, u, u_x, u_y) = 0$

donde $a_{11}, a_{12}, a_{22}$ son funciones de $(x,y)$, no de $u$.

Si los coeficientes $a_{11}, a_{12}, a_{22}$ no dependen solo de $(x,y)$, sino que son funciones de $x, y, u, u_x, u_y$, entonces la ecuación se denomina cuasi - lineal.

Ejemplo:

  $uu_x, u_x u_{xx}, u_yu_x, u_yu_{yy}$

La ecuación se llama lineal, si es lineal tanto en las derivadas de orden mayor $u_{xx}, u_{xy}, u_{yy}$, como en la función $u$ y en sus primeras derivadas $u_x, u_y$:

$a_{11}u_{xx} + 2a_{12}u_{xy} + a_{22}u_{yy}+b_1u_x+b_2u_y+Cu+f = 0$

Siendo $a_{11}, a_{12}, a_{22}, b_1, b_2, C, f$ funciones sólo de $(x,y)$

Si los coeficientes de la ecuación anterior no dependen de $(x,y)$, se trata de una ecuación lineal con coeficientes constantes.

La ecuación se llama homogénea, si $f(x,y) = 0$

<br>

### Forma Canónica de la ecuación de onda.

Consideremos la ecuación de onda:
  $u_{xx}(x,t) - \frac{1}{V^2}u_{tt}(x,t) = 0$

donde V es la velocidad de la onda.
Ahora consideremos la siguiente transformación de coordenadas (admisible).

$\xi = x-vt$ <br>   $\eta = x+vt $

$u_x(\xi, \eta) = \frac{\partial u(\xi,\eta)}{\partial x} = \frac{\partial u}{\partial \xi} \frac{\partial \xi}{\partial x} + \frac{\partial u}{\partial \eta} \frac{\partial \eta}{\partial x}$

<br>

$u_x = u_\xi + u_\eta$

<br>

$u_{xx}(\xi, \eta) = \frac{\partial^2u (\xi, \eta)}{\partial x^2} = \frac{\partial u_\xi}{\partial \xi}\frac{\partial \xi}{\partial x} + \frac{\partial u_\xi}{\partial \eta} \frac{\partial \eta}{\partial x} + \frac{\partial u_\eta}{\partial \xi} \frac{\partial \xi}{\partial x} + \frac{\partial u_\eta}{\partial \eta} \frac{\partial \eta}{\partial x}$

<br>

$u_{xx} = u_{\xi\xi} + u_{\xi\eta} + u_{\eta\xi} + u_{\eta\eta}$

<br>

$u_t(\xi,\eta) = \frac{\partial u}{\partial \xi} \frac{\partial \xi}{\partial t} + \frac{\partial u}{\partial \eta}\frac{\partial \eta }{\partial t}$

<br>

$u_t = V \frac{\partial u}{\partial \eta} - V\frac{\partial u}{\partial \xi}$

<bt>

$u_{tt}(\xi,\eta) = \frac{\partial^2u (\xi, \eta)}{\partial t^2} = V [\frac{\partial u_\eta}{\partial \xi}\frac{\partial \xi}{\partial t} + \frac{\partial u_\eta}{\partial \eta}\frac{\partial \eta}{\partial t}] - V[\frac{\partial u_\xi}{\partial \xi}\frac{\partial \xi}{\partial t} + \frac{\partial u_\xi}{\partial \eta}\frac{\partial \eta}{\partial t}]$

<br>

$=  V[u_{\eta\xi}(-V) +  u_{\eta\eta}(V)] - V[u_{\xi\xi}(-V) + u_{\xi\eta}(V)]$ 

<br>

$u_{tt}= -V^2 U_{\xi\xi} + V^2 u_{\eta\eta} - 2V^2u_{\eta\xi}$

<br>

$u_{xt}(\xi,\eta) = \frac{\partial u_x}{\partial t} = (\frac{\partial u_\xi}{\partial \xi}\frac{\partial \xi}{\partial t} + \frac{\partial u_\xi}{\partial u_\eta}\frac{\partial u_\eta}{\partial t}) + (\frac{\partial u_\eta}{\partial \xi}\frac{\partial \xi}{\partial t} + \frac{\partial u_\eta}{\partial \eta}\frac{\partial \eta}{\partial t})$

<br>

$u_{xt} = -Vu_{\xi\xi} + Vu_{\xi\eta} - Vu_{\eta\xi} + Vu_{\eta\eta}$

<br>

Sustituimos $u_{xx}$, $u_{tt}$ en la ecuación de onda y obtenemos:

<br> 

$u_{\xi\xi} + u_{\xi\eta} + u_{\eta\eta} - (u_{\eta\eta} - 2u_{\eta\xi} + u_{\xi\xi}) = 0$

<br>

Así, la forma canónica de la ecuación de onda es:

<br>

$u_{\xi\eta} = 0$

<br>

Si integramos esta última ecuación respecto de $\eta$ se tiene:

$u_\xi = f(\xi)$

<br>

Ahora integramos respecto de $\xi$

$u = \int f(\xi) d\xi + g(\eta)$

Regresando a la forma canónica de la ecuación de onda pero ahora integramos primero respecto de $\xi$.

$u_\eta = h(\eta)$

Luego integramos respecto a $\eta$

$u = \int h(\eta) d\eta + k(\xi)$

<br>

Entonces:

$k(\xi) = \int f(\xi) d\xi$

<br>

$g(\eta) = \int h(\eta) d\eta$

<br>

Por lo tanto:

$u(\xi, \eta) = \int f(\xi) d\xi + \int h(\eta) d\eta$