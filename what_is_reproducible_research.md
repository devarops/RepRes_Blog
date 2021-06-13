# What is Reproducible Research?

Reproducible Research es un conjunto de prácticas que adoptamos para que otros puedan reproducir los
resultados de nuestros análisis de datos. La principal ventaja de adoptar estas prácticas es que nos
facilitan la colaboración con otros investigadores.

Para que otros investigadores puedan reproducir nuestros resultados, primero debemos proveer acceso
a tres elementos:

1. El código fuente
1. Los datos crudos
1. El entorno computacional

Después de asegurar el acceso a esos tres elementos, podemos automatizar la producción de nuestros
resultados para verificar continuamente que otros pueden reproducir nuestras gráficas y tablas.

## Código fuente

La manera más fácil de compartir el código fuente es mediante GitHub. Usamos GitHub para compartir
código fuente de manera similar a la que usamos Dropbox para compartir documentos.

> GitHub is a code hosting platform for version control and collaboration. It lets you and others
> work together on projects from anywhere<sup sup id="1">[1](#github)</sup>.

El código fuente incluye los scripts para extraer, transformar y cargar los datos, para el análisis
de los datos, para exportar las gráficas y tablas y para actualizar el reporte técnico.

## Datos crudos

Los datos crudos los compartimos junto con el código, preferentemente como archivos de texto simple.
Los datos tabulares los guardamos en formato CSV y los metadatos en JSON<sup
id="2">[2](#datapackage)</sup>. 

## Entorno computacional

## Automatización

El acceso al código fuente, a los datos crudos y al entorno computacional es necesario pero no
suficiente para asegurar la reproducibilidad. Para verificar continuamente la reproducibilidad de
nuestros resultados, debemos automatizar su producción. Idealmente, verificaremos de manera
automática que nuestros resultados sean reproducibles cada vez que hagamos un cambio.

## Conclusión

## Referencias


- <a name="github">1</a>: https://guides.github.com/activities/hello-world/#what [↩](#1)
- <a name="datapackage">2</a>: https://frictionlessdata.io/data-package [↩](#2)
