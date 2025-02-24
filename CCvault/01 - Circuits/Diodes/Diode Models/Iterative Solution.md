Using the [[Diode Transfer Function]] (1) and the [[Load Line]] (2) equations plug (2) into (1)
(1) 

$$I_{D}=I_{S}\exp\left( \frac{V_{D}}{nV_{T}} \right)$$
(2)
$$I_{D}=\frac{V_{DD}-V_{D}}{R}$$
(3)
$$V_{D}=nV_{T}\ln\left( \frac{V_{DD}-V_{D}}{R\cdot I_{S}} \right)$$
Use a seed $V_{D}$ (in equation) usually 0.7V then iterate using the result in the nest $V_{D}$

// What is n?