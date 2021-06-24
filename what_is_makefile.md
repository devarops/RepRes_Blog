[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) hace de la producción de tu manuscrito una
tarea completamente trivial. Con el uso de Make, con una sola una instrucción generas los análisis
estadísticos, las gráficas, las tablas e integras todo en tu manuscrito. Esto es fundamental para
una investigación reproducible.

Cada vez que los datos o el código fuente de tu investigación cambian debes actualizar tu manuscrito
incorporando los nuevos resultados. Cuando actualizas tu manuscrito manualmente, es fácil cometer
errores por la dependencias entre los elementos de tu investigación. Por ejemplo, podrías generar
las gráficas con datos viejos y ajustar el modelo con datos nuevos o viceversa.

Make es una herramienta que coordina el flujo de trabajo en la producción de tu manuscrito. Tu
describes los objetivos (datos, resultados y manuscrito) y sus dependencias. Make sabe cómo manejar
la propagación de las dependencias y solo generará los resultados afectados por los cambios nuevos
que introduces.

Con Make escribes las instrucciones para generar las componentes de tu manuscrito: de dónde
descargar los datos; cuáles archivos de código correr y en cuál orden; cómo importar los resultados
de los pasos anteriores en nuevos archivos; cuáles archivos de código debes ejecutar para actualizar
los resultados cuando actualizas los datos; y finalmente, cuáles tablas y cuáles gráficas son las
que aparecerán en el manuscrito.

Además de ayudar en la automatización de la producción de tu manuscrito, Make también sirve de
documentación sobre nuestro código fuente. Con Make, las instrucciones sobre cómo generar tu
manuscrito siempre serán claras y estarán actualizadas. Make es una herramienta fundamental para la
investigación reproducible.
