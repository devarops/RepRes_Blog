La producción de tus resultados debe ser una tarea absurdamente simple. Así, con una instrucción
simple volveremos a generar los resultados, los ajustes, las gráficas e integrar todo en un reporte,
cunado los datos cambien. 

## Un ejemplo sencillo
Supongamos que recibimos un reporte del ajuste a una recta. Los resultados no son los esperados.
¿Cuál es la fuente de este error?

### Algunas posibles fuentes de error
Los datos podrían tener las unidades unidades incorrectas o magnitudes sin sentido. Tal vez, la
elección al modelo ajustado no fue adecuado. Posiblemente, los puntos graficados no corresponden a 
los datos o los parámetros de la línea no corrresponden a los encontrados en el ajuste. Tal vez todo
lo anterior es correcto, pero no actualizamos el reporte. 

### Problemas al articular el reporte
Hasta un ejemplo tan sencillo como el anterior tiene varias fuentes de error. El proceso para
generar el reporte es claro: obtengo los datos, ajusto el modelo, genero la gráfica e integro el
reporte. Además, dependen unos de otros. Por ejemplo, la gŕafica necesita depende de los datos y del
ajuste del modelo. Podría generar las gráficas con los datos viejos y el modelo correcto o
viceversa.

También las instrucciones para generar cada uno de los componentes del reporte deben ser sencillas.
El orden para llevarlas a cabo no deben ser una otra fuente de error.

## La solución
`make` es una herramienta para controlar el proceso de la generación del reporte. Tu escribes los
objetivos (datos, ajustes, gráficas o reporte) y sus dependencias. `make` sabrá cuáles deben de ser
generadas nuevamente y cuáles no.

Si actualizamos el código encargado de hacer el análisis, no es necesario descarga nuevamente los
datos. Si los únicos cambios son en el reporte, no será necesario generar nuevamente la gráfica y
volver ajustar el modelo.

# Conclusión
Podemos usar `make` para coordinar la producción de un reporte. Sabe cómo atender la propagación de
las dependencias y solo generará los resultados involucrados por los cambios nuevos que
introducimos.