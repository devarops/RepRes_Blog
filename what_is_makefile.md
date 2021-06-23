[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) hace de la producción de tu manuscrito una
tarea completamente trivial. Cuando los datos cambian, con solo una instrucción vuelves a generar
los resultados, los ajustes, las gráficas, las tablas e integras todo en tu manuscrito. Esto es
fundamental para una investigación reproducible.

Make es una herramienta que controla el proceso de la generación del manuscrito. Tu describes los
objetivos (datos, ajustes, gráficas o manuscrito) y sus dependencias. Make sabrá cuáles deben de ser
generadas nuevamente y cuáles no.

Por ejemplo, si actualizas el código encargado de hacer el análisis, no es necesario descargar
nuevamente los datos. Si los únicos cambios son en el manuscrito, no será necesario generar
nuevamente la gráfica ni ajustar el modelo.

Dado que estos pasos son interdependientes, es fácil cometer errores cuando actualizas tu manuscrito
o cuando alguien más reproduce tu manuscrito. Por ejemplo, podrías generar las gráficas con datos
viejos y ajustar el modelo con datos nuevos o viceversa.

Puedes usar Make como una forma para coordinar la producción de tu manuscrito. Make sabe cómo
manejar la propagación de las dependencias y solo generará los resultados involucrados por los
cambios nuevos que introduces.

Con Make escribes las instrucciones para generar las componentes de tu manuscrito: de dónde
descargar los datos; cuáles archivos de código correr y en cuál orden; cómo copiar los resultados de
los pasos anteriores en nuevos archivos; cuáles archivos de código debes ejecutar para obtener el
resto de las gráficas; y finalmente, cuáles tablas y cuáles gráficas son las que aparecerán en el
manuscrito.

Además de ayudar en la automatización, Make sirve de documentación siempre actualizada sobre nuestro
código fuente. Con Make, las instrucciones sobre cómo generar tu manuscrito nunca dejarán de ser
claras ni podrán ser obsoletas. Make es una herramienta fundamental para la investigación
reproducible.
