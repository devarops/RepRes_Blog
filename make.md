[GNU Make](https://en.wikipedia.org/wiki/Make_(software)) makes the production of your manuscript a
completely trivial task. With the use of Make, with a single instruction you generate the analyzes
statistics, graphs, tables and you integrate everything in your manuscript. This is essential for a
reproducible investigation.

Every time the data or source code of your research changes, you must update your manuscript.
incorporating the new results. When you update your manuscript manually, it's easy to commit errors
due to dependencies between the elements of your research. For example, you could generate the
graphs with old data and fit the model with new data or vice versa.

Make is a tool that coordinates the workflow in the production of your manuscript. Your You describe
the objectives (data, results, and manuscript) and their dependencies. Make know how to handle the
propagation of the dependencies and will only generate the results affected by the new changes that
you enter.

To use Make, you first write the instructions to get the dependencies from your script. Then you use
Make to download the data and perform the analyzes. When your data changes or modify your analysis,
Make will determine which code files to run and in what order to update the results. Finally, Make
will import the tables, graphs and the updated results.

In addition to assisting in automating the production of your manuscript, Make also serves as
documentation of your source code. With Make, the instructions on how to generate your manuscript
they will always be clear and up to date. Make is a fundamental tool for reproducible research.

---

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
