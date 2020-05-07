# Asimetría en el tensor de esfuerzos $$\sigma$$
De acuerdo con el principio de **conservación del momento angular**, se requiere que la suma de momentos con respecto a un punto arbitrario sea cero, por lo cual el tensor de esfuerzos debe ser **simétrico**, teniendo así solo 6 componentes independientes. [1]

A pesar de lo anterior, hay casos en donde el tensor de esfuerzos no es simétrico. Un caso es cuando se tienen ***couple-stresses*** o momentos por unidad de volumen. Otro caso es, cuando el número de **Knudsen es cercano a 1**. También está el caso en el que el continuo que se está analizando es un **fluido no Newtoniano**, lo cual puede conducir a tener un fluido rotacionalmente no invariante, lo cual pasa con los **polímeros**. [1]

Con respecto al primer caso, en la mecánica clásica del continuo, se asume que la materia se distribuye uniformemente en el cuerpo a analizar, lo cual es razonable y da buenos resultados a macro escala, sin embargo, a **microescala**, este comportamiento no se da de la misma forma. Por esto existe la teoría de ***couple stress***, la cual busca ser una buena aproximación en la mecánica a microescala. De esta forma, para que esta teoría tenga sentido es necesario que el tensor de couple-stress sea **asimétrico** (*skew-symmetric*). [2]

El número de **Knudsen** ($$K_n$$) es un **número adimensional**, que se define como la razón entre la longitud molecular del camino libre medio o mean free path (distancia media que una partícula recorre entre impactos sucesivos) y una longitud característica. Este número sirve para saber si es que para modelar una situación es necesario usar **mecánica estadística** o **mecánica del continuo**. Cuando este número es cercano o mayor a 1, el supuesto de continuidad de la mecánica de fluidos no es una buena aproximación, por lo que se debe usar el método de mecánica estadística. [3]

Sumado a todo lo anterior independiente si se usa mecánica del continuo o mecánica estadística, es posible ver en la práctica que, al medir el tensor de esfuerzos en simulaciones de **dinámica molecular**, usando las definiciones físicas de esfuerzo y fuerza por unidad de área; este resulta ser asimétrico cerca de **núcleos de dislocación** (*dislocation cores*), **límites de fase** (*phase boundaries*) e incluso se ve esto en **materiales homogéneos sujetos a una carga de corte** (*shear loading*). [4]

## Referencias
[1] Cauchy stress tensor. (2020). En Wikipedia. Recuperado el 6 de mayo de 2020, de https://en.wikipedia.org/wiki/Cauchy_stress_tensor.

[2] Hadjesfandiari, A., Dargush, G. (2011). Couple stress theory for solids. Elsevier: International Journal of Solids and Structures. 
Recuperado el 6 de mayo de 2020, de https://www.sciencedirect.com/science/article/pii/S0020768311001727.

[3] Knudsen number. (2020). En Wikipedia. Recuperado el 6 de mayo de 2020, de https://en.wikipedia.org/wiki/Knudsen_number. 

[4] Rigelesaiyin, J., Diaz, A., Li, W., Xiong, L., Chen, Y. (2018). Asymmetry of the atomic-level stress tensor in homogeneous and inhomogeneous materials. Proc. R. Soc. A. Recuperado el 6 de mayo de 2020, de https://royalsocietypublishing.org/doi/pdf/10.1098/rspa.2018.0155.
