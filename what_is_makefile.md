Con [GNU Make](https://en.wikipedia.org/wiki/Make_(software)) la producción es una tarea
completamente trivial. Cuando los datos cambian, con una instrucción volvues a generar los
resultados, los ajustes, las gráficas e integrar todo en un manuscrito. Esto es fundamental para una
investigación reproducible.

Make es una herramienta para controlar el proceso de la generación del manuscrito. Tu escribes los
objetivos (datos, ajustes, gráficas o manuscrito) y sus dependencias. Make sabrá cuáles deben de ser
generadas nuevamente y cuáles no.

Si actualizas el código encargado de hacer el análisis, no es necesario descargar nuevamente los
datos. Si los únicos cambios son en el manuscrito, no será necesario nuevamente generar la gráfica
ni ajustar el modelo.

Con Make no es necesario escribir las instrucciones para generar las componentes del
manuscrito en un archivo: de dónde descargar los datos; cuáles códigos correr y en cuál orden; cómo
copiar los resultados de los pasos anteriores en nuevos archivos; qué partes de código debes de
comentar para obtener el resto de las gráficas; y finalmente, recordar cuáles tablas y cuáles
gráficas son las que aparecerán en el manuscrito.

Dado que estos pasos son interdependientes, es fácil
cometer errores cuando actualizamos el manuscrito o cuando alguien más reproduce nuestro manuscrito.
Por ejemplo, podrías generar las gráficas con datos viejos y el ajustar el modelo con datos nuevos o
viceversa.

Con Make las instrucciones nunca dejarán de ser claras ni podrán ser obsoletas.

Además ayudar en la automatización, mancionaremos otras dos ventajas de utilizar Make. La primera es
que Make sirve de documentación siempre actualizada sobre nuestro código fuente. La segunda es que
puede ser usada como prueba de humo al momento de hacer cambios en código fuente. Pero de eso
hablaremos después.

Puedes usar Make como una forma para coordinar la producción de un manuscrito. Make sabe cómo
manejar la propagación de las dependencias y solo generará los resultados involucrados por los
cambios nuevos que introduces. Make es una herramienta fundamental para la investigación
reproducible.
