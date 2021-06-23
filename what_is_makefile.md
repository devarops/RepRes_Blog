# Make your manuscipts with Make
La producción de tus resultados debería convertirse en una tarea completamente trivial. Así, cuando
los datos cambien, con una instrucción volverás a generar los resultados, los ajustes, las gráficas
e integrar todo en un manuscrito. Esto es fundamental para una investigación reproducible.

## Make
[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) es una herramienta para controlar el
proceso de la generación del manuscrito. Tu escribes los objetivos (datos, ajustes, gráficas o
manuscrito) y sus dependencias. Make sabrá cuáles deben de ser generadas nuevamente y cuáles no.

Si actualizas el código encargado de hacer el análisis, no es necesario descargar nuevamente los
datos. Si los únicos cambios son en el manuscrito, no será necesario nuevamente generar la gráfica
ni ajustar el modelo.

## Un ejemplo sencillo
Para reproducir tu manuscrito, podrías escribir las instrucciones para generar las componentes del
manuscrito en un archivo: de dónde descargar los datos; cuáles códigos correr y en cuál orden; cómo
copiar los resultados de los pasos anteriores en nuevos archivos; qué partes de código debes de
comentar para obtener el resto de las gráficas; y finalmente, recordar cuáles tablas y cuáles
gráficas son las que aparecerán en el manuscrito. Sin embargo, después de unas semanas estas
instrucciones dejarán de ser claras e incluso algunas de ellas serán obsoletas.

## Manejo de dependencias
Hasta un ejemplo tan sencillo como ajusitar una recta tiene varias posibles fuentes de error. En
general, el proceso para generar el manuscrito es claro: obtienes los datos, ajustas el modelo,
generas la gráfica e integras el manuscrito. Dado que estos pasos son interdependientes, es fácil
cometer errores cuando actualizamos el manuscrito o cuando alguien más reproduce nuestro manuscrito.
Por ejemplo, podrías generar las gráficas con datos viejos y el ajustar el modelo con datos nuevos o
viceversa.

## Automatización

## Documentación
Las instrucciones sobre cómo generar el manuscrito las guardamos en el archivo Makefile. Makefile
sirve como documentación siempre actualizada sobre nuestro código fuente y sus dependencias.

## Pruebas
Podemos usar Make como una prueba de humo cuando modificamos cualquier parte de nuestra
investigación.

# Conclusión
Puedes usar Make como una forma para coordinar la producción de un manuscrito. Make sabe cómo
manejar la propagación de las dependencias y solo generará los resultados involucrados por los
cambios nuevos que introduces. Make es una herramienta fundamental para la investigación
reproducible.
