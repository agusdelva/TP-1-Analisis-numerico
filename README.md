# TP-1-Analisis-numerico
Análisis Numérico y Cálculo Avanzado 
TRABAJO PRÁCTICO Nº1: REPASO DE PROGRAMACION            UTN - FRBA 



OBJETIVO:  El objetivo final de este Trabajo Práctico es implementar la fórmula para calcular el volumen del líquido almacenado en un tambor cilíndrico horizontal a partir del conocimiento de la altura libre HL Se propone la utilización del SOFTWARE específico para cálculos numéricos tipo Matlab – Scilab – Octave, o también la opción de uso del lenguaje de programación Python en el entorno Colab. Finalmente, se pide corroboración de resultados mediante planillas de cálculo en SOFTWARE del tipo Excel.

ENUNCIADO:
Introducción:
En una sección distante del centro estratégico de un establecimiento industrial ocurre el hallazgo de un barril metálico dispuesto segun el siguiente esquema:

![imagen1_tp1](https://github.com/agusdelva/TP-1-Analisis-numerico/assets/65829590/8b7afcf9-b88e-4cb5-8551-f833a9522022)

Con el fin de evaluar las características del barril y de su contenido se llevan a cabo distintas acciones. Como primer paso se miden las dimensiones del barril confirmando que es un cilindro con diámetro D y longitud L. Se aprecia una abertura en la parte superior del cilindro, a través de la que se extrae una muestra del contenido, determinando que contiene una sustancia líquida. Durante la extracción se comprueba que el barril no está completamente lleno, ya que se detecta la existencia de una porción libre de altura HL que queda sin cuantificar por carecer de instrumentos de medición adecuados para tal fin.











Fórmulas Geométricas:
La geometría nos brinda fórmulas para calcular áreas de sectores circulares de radio r, a partir del ángulo α en radianes, o partiendo de la distancia c 



Área del segmento circular=(α-sin⁡α)/2.r^2=r^2⋅acos⁡(c/r)-c⋅√(r^2-c^2 )

Entonces, para el tambor cilíndrico con llenado parcial, el volumen se calcula con la siguiente fórmula:
V=L.((π⋅D^2)/4-D^2/4⋅acos⁡((D-2.HL)/D)-(D/2-HL)⋅√(〖D/4〗^2-(D/2-HL)^2 ))


Aclaración: los cálculos numéricos se realizan sin unidades, por eso, se recomienda que tanto las longitudes como los volúmenes se encuentren en un sistema de unidades compatible. Por ejemplo, si se miden distancias en metros, los volúmenes deben medirse en metros cúbicos. Y si los volúmenes se miden en litros, las distancias deben medirse en decímetros.




CONSIGNAS:
	Utilizar software Matlab – Scilab – Octave para implementar la fórmula del volumen. O usar lenguaje de programación Python en el entorno Colab para implementar la fórmula del volumen
	Adjuntar códigos de programación
	Responder los siguientes puntos:
	¿Cuál es el volumen del líquido cuando en el interior no queda altura libre?
	¿Cuál es el volumen del líquido cuando la altura libre HL es igual al radio del tanque? 
	¿Cuál es la máxima capacidad del tanque?
	¿Cuál es el volumen del líquido cuando la altura libre HL es una décima parte del diámetro del tanque? 

Para comprobar si los resultados numéricos obtenidos son los correctos se propone aplicar estos métodos en planillas de cálculo: en Excel o similar. Se pide armar una planilla de cálculo que calcule las respuestas pedidas. Una vez resuelto, seleccionar las celdas utilizadas para copiarlas. Las celdas de Excel deben pegarse como “pegado especial” - “Hoja de Cálculo”. De esa manera, al hacer click sobre ellas en este archivo Word se podrán ver las funciones que se utilizaron. 

