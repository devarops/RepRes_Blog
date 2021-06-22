# Make your manuscipts with Make
La producción de tus resultados debería convertirse en una tarea completamente trivial. Así, cuando
los datos cambien, con una instrucción volverás a generar los resultados, los ajustes, las gráficas
e integrar todo en un manuscrito. Esto es fundamental para una investigación reproducible.

## Un ejemplo sencillo
Podrías escribir las instrucciones para volver a generar las componentes del manuscrito en el
archivo README: de dónde descargar los datos; cuáles códigos correr y en cuál orden; cómo copiar los
resultados de los pasos anteriores en nuevos archivos; qué partes de código debes de comentar para
obtener el resto de las gráficas; y finalmente, recordar cuáles tablas y cuáles gráficas son las
únicas que aparecerán en el manuscrito. Después de unas semanas estas instrucciones podrían no ser
tan claras o incluso algunas de ellas obsoletas. Por un momento ponte en el papel de tus
colaboradores.

Supón que recibes un puño de programas que debes de correr en algún orden particular. Algunos de los
resultados parciales los usarás para generar nuevos resultados. Alguna instrucción es obsoleta, pues
los archivos ya no se llaman como antes. Finalmente, ves los resultados y no son los esperados.
¿Cuál es la fuente de este error?

### Algunas posibles fuentes de error
Los datos podrían tener las unidades incorrectas o magnitudes sin sentido. Tal vez, la elección del
modelo ajustado no fue adecuada. Posiblemente, los puntos graficados no corresponden a los datos o
los parámetros de la línea no corresponden a los encontrados en el ajuste. Tal vez todo lo anterior
es correcto, pero olvidaste actualizar los resultados en el manuscrito.

### Problemas al articular el manuscrito
Hasta un ejemplo tan sencillo como ajustar una recta tiene varias posibles fuentes de error. En
general, el proceso para generar el manuscrito es claro: obtienes los datos, ajustas el modelo,
generas la gráfica e integras el manuscrito. Cada uno de estos pasos pueden tener dependencias unos
de otros. Por ejemplo, la gŕafica necesita de los datos y del ajuste del modelo. Podrías generar las
gráficas con los datos viejos y el modelo correcto o viceversa.

Para reducir las posibles causas de error, las instrucciones para generar cada uno de los
componentes del manuscrito deben ser sencillas. El orden para llevarlas a cabo no debe ser otra
fuente de error.

## La solución
[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) es una herramienta para controlar el
proceso de la generación del manuscrito. Tu escribes los objetivos (datos, ajustes, gráficas o
manuscrito) y sus dependencias. Make sabrá cuáles deben de ser generadas nuevamente y cuáles no.

Si actualizas el código encargado de hacer el análisis, no es necesario descarga nuevamente los
datos. Si los únicos cambios son en el manuscrito, no será necesario generar nuevamente la gráfica y
volver ajustar el modelo.

# Conclusión
Puedes usar Make como una forma para coordinar la producción de un manuscrito. Make sabe cómo
manejar la propagación de las dependencias y solo generará los resultados involucrados por los
cambios nuevos que introduces. Make es una herramienta fundamental para la investigación
reproducible.
