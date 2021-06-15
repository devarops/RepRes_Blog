# What is Reproducible Research?

Reproducible Research es un conjunto de prácticas que adoptamos para que otros puedan reproducir los
resultados de nuestra investigación. La ventaja principal de adoptar estas prácticas es que nos
facilitan la colaboración con otros investigadores.

Para que otros investigadores puedan reproducir nuestros resultados, primero debemos proveer acceso
a tres elementos:

1. El código fuente
1. Los datos crudos
1. El entorno computacional

Después de asegurar el acceso a esos tres elementos, lo siguiente es automatizar la producción de
nuestros resultados. Con la automatización en la producción verificaremos continuamente que otros
pueden reproducir nuestras gráficas y tablas.

## Código fuente

La manera más fácil de compartir el código fuente es mediante GitHub. Usamos GitHub para compartir
código fuente de manera similar a la que usamos Dropbox para compartir documentos.

> GitHub is a code hosting platform for version control and collaboration. It lets you and others
> work together on projects from anywhere<sup id="1">[1](#github)</sup>.

El código fuente de la investigación incluye los scripts para:

- extraer, transformar y cargar los datos;
- realizar el análisis de datos;
- exportar las gráficas y tablas;
- actualizar el reporte técnico; y
- automatizar el flujo de trabajo.

También todos los archivos de configuración son parte del código fuente de nuestra investigación.

## Datos crudos

Compartimos los datos crudos junto con el código fuente, preferentemente como archivos de texto
simple. Los datos tabulares los guardamos en formato CSV y los metadatos en JSON<sup
id="2">[2](#datapackage)</sup>.

En los casos donde no sea posible consignar los datos en el repositorio del código fuente,
compartimos los datos usando un repositorio de datos especializado<sup id="3">[3](#datos). En estos
casos, los scripts que usamos para obtener los datos crudos a partir del repositorio de datos son
parte del código fuente de la investigación.

## Entorno computacional

El entorno donde corremos los análisis de datos lo compartimos junto con el código fuente. El
formato más popular es `Dockerfile`. Un `Dockerfile`<sup id="4">[4](#dockerfile)</sup> es un archivo
de texto simple que contiene todos los comandos necesarios para ensamblar un contenedor de software
con el entorno requerido para ejecutar nuestros análisis de datos.

## Automatización

El acceso al código fuente, a los datos crudos y al entorno computacional es necesario pero no
suficiente para asegurar la reproducibilidad. Para verificar continuamente la reproducibilidad de
nuestros resultados, debemos automatizar su producción. Idealmente, verificaremos de manera
automática que nuestros resultados sean reproducibles cada vez que hacemos un cambio.

## Conclusión

Reproducible Research nos facilita la colaboración con otros investigadores. Las prácticas de
Reproducible Research incluyen compartir el código fuente, los datos crudos y el entorno
computacional donde producimos los resultados. Además, automatizamos todo el flujo de trabajo: la
adquisición, procesamiento y análisis de los datos; la exportación de gráficas y tablas; la
actualización del reporte técnico. Esta automatización nos asegura que otros investigadores pueden
reproducir nuestros resultados y que podemos colaborar fácilmente con ellos.

## Referencias

- <a name="github">1️⃣</a> https://guides.github.com/activities/hello-world/#what [⤴️](#1)
- <a name="datapackage">2️⃣</a> https://frictionlessdata.io/data-package [⤴️](#2)
- <a name="datos">3️⃣</a> https://www.nature.com/sdata/policies/repositories [⤴️](#3)
- <a name="dockerfile">3️⃣</a> https://docs.docker.com/engine/reference/builder [⤴️](#4)
