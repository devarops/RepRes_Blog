La producción de tus resultados debería convertirse en una tarea absurdamente simple. Así, cuando los datos
cambien, con una instrucción volverás a generar los resultados, los ajustes, las gráficas e
integrar todo en un reporte. Esto es fundamental para una investigación reproducible.

## Un ejemplo sencillo
Supón que recibes un reporte del ajuste a una recta. Los resultados no son los esperados.
¿Cuál es la fuente de este error?

### Algunas posibles fuentes de error
Los datos podrían tener las unidades incorrectas o magnitudes sin sentido. Tal vez, la elección del
modelo ajustado no fue adecuado. Posiblemente, los puntos graficados no corresponden a los datos o
los parámetros de la línea no corresponden a los encontrados en el ajuste. Tal vez todo lo anterior
es correcto, pero no olvidaste actualizar los resultados en el reporte.

### Problemas al articular el reporte
Hasta un ejemplo tan sencillo como el anterior tiene varias fuentes de error. El proceso para
generar el reporte es claro: obtienes los datos, ajustas el modelo, generas la gráfica e integras el
reporte. Además, dependen unos de otros. Por ejemplo, la gŕafica necesita de los datos y del
ajuste del modelo. Podrías generar las gráficas con los datos viejos y el modelo correcto o
viceversa.

También las instrucciones para generar cada uno de los componentes del reporte deben ser sencillas.
El orden para llevarlas a cabo no debe ser otra fuente de error.

## La solución
[`make`](https://www.gnu.org/software/make/) es una herramienta para controlar el proceso de la generación del reporte ([aquí un tutorial amigable](https://makefiletutorial.com/). Tu escribes los
objetivos (datos, ajustes, gráficas o reporte) y sus dependencias. `make` sabrá cuáles deben de ser
generadas nuevamente y cuáles no.

Si actualizas el código encargado de hacer el análisis, no es necesario descarga nuevamente los
datos. Si los únicos cambios son en el reporte, no será necesario generar nuevamente la gráfica y
volver ajustar el modelo.

# Conclusión
Puedes usar `make` como una forma para coordinar la producción de un reporte. Sabe cómo atender la propagación de
las dependencias y solo generará los resultados involucrados por los cambios nuevos que introduces.
