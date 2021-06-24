[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) hace de la producción de tu manuscrito una
tarea completamente trivial. Con el uso de Make, con una sola una instrucción generas los análisis
estadísticos, las gráficas, las tablas e integras todo en tu manuscrito. Esto es fundamental para
una investigación reproducible.

Cada vez que los datos o el código fuente de tu investigación cambian debes actualizar tu manuscrito
incorporando los nuevos resultados. Cuando actualizas tu manuscrito manualmente, es fácil cometer
errores por las dependencias entre los elementos de tu investigación. Por ejemplo, podrías generar
las gráficas con datos viejos y ajustar el modelo con datos nuevos o viceversa.

Make es una herramienta que coordina el flujo de trabajo en la producción de tu manuscrito. Tú
describes los objetivos (datos, resultados y manuscrito) y sus dependencias. Make sabe cómo manejar
la propagación de las dependencias y solo generará los resultados afectados por los cambios nuevos
que introduces.

Para usar Make, primero escribes las instrucciones para obtener las dependencias de tu manuscrito.
Luego, usas Make para descargar los datos y realizar los análisis. Cuando tus datos cambien o
modifiques tus análisis, Make determinará cuáles archivos de código debe correr y en cuál orden para
actualizar los resultados. Finalmente, Make importará en tu manuscrito las tablas, las gráficas y
los resultados actualizados.

Además de ayudar en la automatización de la producción de tu manuscrito, Make también sirve de
documentación de tu código fuente. Con Make, las instrucciones sobre cómo generar tu manuscrito
siempre serán claras y estarán actualizadas. Make es una herramienta fundamental para la
investigación reproducible.
