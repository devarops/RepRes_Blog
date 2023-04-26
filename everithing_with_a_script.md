# Everithing with a script

On many occasions, the analyzes you carry out and the results you obtain are done using software
with a graphical user interface (GUI). However, producing results in this way reduces the reproducibility
of your results, as you may not record some of the steps you take, and you or your colleagues will not be
able to precisely repeat the procedures.

To ensure the reproducibility of your work, all the the data analysis workflow must be done through code:
from the initial data wranwking to the creation of your final results. Carrying out your analysy this way,
you end up with code that also serves as documentation. You code tells you  where your raw data comes from
and how you get the final results. Therefore, your data should not have any prior processing when we start
processing it.

Some steps in wich you should use a script are:

- If your data comes from an external source, for example, downloaded from a website, code is the
  best way to do it. In this way, the same script with which you download the data serves as
  documentation of what you downloaded and from where.

- Suppose you are going to convert a data file. For example, if you are going to convert an Excel
  file to CSV.

- Do not edit your data tables by hand. You must register all aspects of data cleansing in a script,
  such as formatting your tables or modifying the names of columns. Sometimes you must choose a
  certain amount of records that you will use for your analysis, avoid doing it by hand, Create a
  script with which you filter the data from your interest.

- Every aspect of your analysis should be in a script. A lousy practice often used is to execute
  certain lines of code to do one thing and other lines of code to do another, run a script, then
  change the value of a particular variable and rerun it to get the result. Instead of doing the
  above, you should create separate scripts that you can run without the need to change variables or
  execute only particular lines of code.

Following the steps above may seem daunting if you use a GUI; indeed, it may be easier
to execute each step by hand. But imagine if any time your data changes in any way, perhaps by
adding or deleting a record. To get your final result, you will have to perform each step manually,
while executing the scripts should be easy.


---

En muchas ocasiones, los análisis que realizas y los resultados que obtienes los haces utilizando
programas de interfaz gráfica. Obtener los resultados de esta forma reduce la reproducibilidad de
tus resultados, ya que es posible que algunos pasos que realices no queden registrados y tú o tus
colegas no podrán repetir exactamente los procedimientos.

Para asegurar la reproducibilidad de tu trabajo, el procesamiento de tus datos debe ser a través de
código; desde la limpieza, pasando por el acomodo de tus tablas, hasta el análisis de tus datos. El
objetivo de esto es, a grandes rasgos, que el código sirva así mismo como documentación, que te
ayude a conocer la procedencia de tus datos crudos y la forma como obtienes los resultados finales.
De preferencia, y en la medida de lo posible, al comenzar a procesar tus datos, estos no deberían
tener algún procesamiento previo.

Algunos pasos o reglas en donde deberías usar un script son:

- Si tus datos provienen de una fuente externa, por ejemplo descargarlos de algún sitio web, la
  mejor forma de hacerlo es a través de código. De esta manera, el mismo script con el que descargas
  los datos sirve de documentación sobre qué descargaste y de cuál sitio.

- Si vas a convertir un archivo de datos. Por ejemplo, si vas a convertir un archivo de Excel a CSV.

- No edites tus tablas de datos a mano. Todos los aspectos de la limpieza de datos deben quedar
  registrado en un script, como darle cierto formato a tus tablas o modificar los nombres de
  columnas. En ocasiones debes escoger cierta cantidad de registros que servirán para tu análisis,
  evita hacerlo a mano; crea un script con el que realices el filtrado de los registros que son de
  tu interés.

- Cada aspecto de tus análisis debe quedar en un script. Una mala práctica que se usa a menudo es
  ejecutar ciertas líneas de código para hacer una cosa y otras líneas de código para hacer otras, o
  ejecutar un script, después cambiar el valor de cierta variable y ejecutarlo de nuevo para obtener
  el resultado. En lugar de hacer lo anterior, debes crear scripts separados que puedas ejecutar,
  sin necesidad de cambiar variables o ejecutar solo ciertas líneas de código.

Seguir los pasos anteriores puede parecer una tarea ardua si estás acostumbrado a usar programas de
interfaz gráfica; ciertamente, puede ser más fácil ejecutar cada paso a mano. Pero, imagina por un
momento que tus datos cambian de alguna forma, al agregar o eliminar quizá algún registro, para
obtener tu resultado final deberás realizar cada paso de forma manual, mientras que ejecutar los
scripts debería ser una tarea por demás sencilla.
