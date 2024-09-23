# Forma canónica
Consideremos a la forma canónica de las ecuaciones diferenciales parciales de segundo orden como la expresión más simple obtenida mediente una transformación de variables.
Partimos de la expresión general de la ecuación diferencial de segundo orden:

$$a_{11} u_{xx} + 2a_{12} u_{xy} + a_{22} u_{yy} + bu_x + cu_y + u = 0$$

con $a_{11}, a_{12}, a_{22}, b, c$ no necesariamente constantes.

Si se usa una trasformacion admisible de coordenadas: $\xi \= \xi\(x,y),  \eta\=\eta\(x,y)$ entonces las derivadas parciales en las nuevas varibles son:

$$u_x=u_\xi\ \xi\_x +u_\eta\ \eta\_x$$

$$u_{xx}= (u_{\xi\\xi\} \xi\_x + u_{\xi\\eta\}\eta\_x)\xi\_x + u_\xi\ \xi\_{xx} + (u_{\eta\\xi\} \xi\_x + u_{\eta\\eta\}\eta\_x)\eta\_x + u_\eta\ \eta\_{xx}$$

$$=u_{\xi\\xi\}\xi\_x^{2}+ 2u_{\eta\\xi\}\xi\_x\eta\_x+u_{\eta\\eta\}\eta\_x^{2}+u_\xi\\xi\_{xx}+u_\eta\\eta\_{xx}$$

$$u_y=u_\xi\ \xi\_y+u_\eta\\eta\_y$$

$$u_{yy}= (u_{\xi\\xi\} \xi\_y + u_{\xi\\eta\}\eta\_y)\xi\_y + u_\xi\ \xi\_{yy} + (u_{\eta\\xi\} \xi\_y + u_{\eta\\eta\}\eta\_y)\eta\_y + u_\eta\ \eta\_{yy}$$

$$=u_{\xi\\xi\}\xi\_y^{2}+ 2u_{\eta\\xi\}\xi\_y\eta\_y+u_{\eta\\eta\}\eta\_x^{2}+u_\xi\\xi\_{yy}+u_\eta\\eta\_{yy}$$

$$u_{xy}= \frac{\partial(u_\xi\ \xi\_x +u_\eta\ \eta\_x)}{\partial y} = (u_{\xi\\xi\}\xi\_y + u_{\xi\\eta} \eta_y) \xi_x + u_\xi \xi_{xy} + (u_{\eta\xi}\xi_y + u_{\eta\eta} \eta_y)\eta_x + u_\eta \eta_{xy}$$

$$=u_{\xi\\xi\}\xi\_y \xi_x + u_{\xi\\eta} (\eta_y \xi_x + \eta_x \xi_y) + u_\xi \xi_{xy} + u_{\eta\eta}\eta_y\eta_x + u_\eta \eta_{xy}$$

Al sustituir en la ecuación original, tenemos:

$a_{11} (u_{\xi\\xi\}\xi\_x^{2}+ 2u_{\eta\\xi\}\xi\_x\eta\_x+u_{\eta\\eta\}\eta\_x^{2}+u_\xi\\xi\_{xx}+u_\eta\\eta\_{xx}) + 2a_{12} \[u_{\xi\\xi\}\xi\_y \xi_x + u_{\xi\\eta} (\eta_y \xi_x + \eta_x \xi_y) + u_\xi \xi_{xy} + u_{\eta\eta}\eta_y\eta_x + u_\eta \eta_{xy}\]+ a_{22} (u_{\xi\\xi\}\xi\_y^{2}+ 2u_{\eta\\xi\}\xi\_y\eta\_y+u_{\eta\\eta\}\eta\_x^{2}+u_\xi\\xi\_{yy}+u_\eta\\eta\_{yy}) + b(u_\xi\ \xi\_x +u_\eta\ \eta\_x) + c(u_\xi\ \xi\_y+u_\eta\\eta\_y) + u = 0$

Después de ordenar los términos se tiene. Sea:

$\bar{a_{11}}:= a_{11}\xi_x^{2} + 2a_{12} \xi_x\xi_y+a_{22}\xi_y^{2}$

$\bar{a_{12}}:= a_{11}\xi_x \eta_x + a_{12}(\xi_x\eta_y+ \eta_x \xi_y)+ a_{22}\xi_y\eta_y$

$\bar{a_{11}}:= a_{11}\eta_x^{2} + 2a_{12} \eta_x\eta_y+a_{22}\eta_y^{2}$

asi, obtenemos:

$$\bar{a_{11}}u_{\xi\xi}+ 2\bar{a_{12}}u_{\xi\eta}+\bar{a_{22}}u_{\eta\eta}+ \bar{F}=0. $$

En donde $\bar{F}$ no depende de las segundas derivadas.

Ahora, escogemos las variables $\xi$ y $\eta$ de modo que el coeficiente $\bar{a_{11}}$ sea nulo, es decir:

$$a_{11}\xi_x^{2} + 2a_{12} \xi_x\xi_y+a_{22}\xi_y^{2} = 0,$$

en otras palabras, se elige \xi de tal forma que sea solución a la ecuacion diferencial parcial anterior.

Para encontrar $\xi(x,y)$ es necesario demostrar algunos lemas: 

Lema #1: si $z=\varphi(x,y)$ es una solución particular de la ecuación: 

$$a_{11}z_x^{2} + 2a_{12} z_x z_y+a_{22}z_y^{2} = 0,$$

la relación $\varphi(x,y)=0$ es una integral general de la ecuación diferencial ordinaria:
