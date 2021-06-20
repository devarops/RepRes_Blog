Supongamos que recibimos un reporte acerca de caída libre. Notamos que la gráfica de distancia
contra tiempo es una línea recta. Pero tú esperábamos ver un movimiento uniformemente acelerado, con
aceleración igual 9.81 m*s^{-2}. ¿Cuál es la fuente de este error?

## ¿Cuáles son los datos?
Pedimos los datos. Una vez que los tenemos revisamos que las columnas tengan los correctos.
Revisamos que las unidades tengan sentido y que la magnitud sean creíbles.

## ¿Cómo analizamos los datos?
Pedimos el análisis de los datos. Vemos los parámetros de la regresión. Hacemos simulaciones.
Revisamos que la magnitud de los parámetros no sean exagerados. 

## ¿Cómo realizamos la gráfica?
Pedimos la gráfica. Revisamos que los puntos graficados correspondan a los datos. Revisamos que la
linea ajustados corresponda al modelo ajustado. Y volvemos a integrar el reporte.

## ¿Cuáles fueron las fuentes del error?
El terminar la revisión notamos que tenemos varias fuente de error. Los datos no tienen las unidades
esperadas, el ajustamos el modelo incorrecto y la gráfica toma otros datos.

Hasta un ejemplo tan sencillo como el anterior tiene varias fuentes de error. El proceso para
generar el reporte es claro: obtengo los datos, ajusto el modelo, genero la gráfica e integro el
reporte. Además, dependen unos de otros. Por ejemplo, la gŕafica necesita depende de los datos y del
ajuste del modelo. Podría generar las gráficas con los datos viejos y el modelo correcto o
viceversa.

## La solución
`make` es una herramienta para controlar el proceso de generación del reporte. Tu escribes los
objetivos (datos, ajustes, gráficas o reporte) y sus dependencias. `make` sabrá cuáles deben de ser
generadas nuevamente y cuáles no.

Si actualizamos el código encargado de hacer el análisis, no es necesario descarga nuevamente los
datos. Si los únicos cambios son en el reporte, no será necesario generar nuevamente la gráfica y
volver ajustar el modelo.

# Conclusión
Podemos usar `make` para coordinar la producción de un reporte. Trabaja con la propagación de las
dependencias y solo generará los resultados involucrados por los cambios nuevos que introducimos.