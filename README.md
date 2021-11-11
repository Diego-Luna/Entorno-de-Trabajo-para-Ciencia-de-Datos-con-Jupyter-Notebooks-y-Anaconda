# Entorno-de-Trabajo-para-Ciencia-de-Datos-con-Jupyter-Notebooks-y-Anaconda

## Google Colab: Primeros pasos.

- Es una herramienta basada en la nube que te permite trabajar en notebooks, y se guardan en tu cuenta de Google Drive 😃.

- Nube vs local: Ambas son útiles, pero se diferencian en la configuración de entornos, ya que en la nube ya están precargadas, y de local tienes que configurarlo manualmente. También es diferente el tiempo de ejecución y la escalabilidad: la nube tiene más poder porque puedes rentarlo!. 💸

- Google Colab: Servicio en la nube basado en Jupyter Notebooks, no requiere configuración y tiene un trabajo a nivel de archivo (el notebook es la base). Tiene uso de gratuito de GPUs y TPUs para correr modelos grandes. ☁️

- Puedes acceder a Google Colab desde tu drive o desde el navegador.

- Para aprender Markdown.

- Markdown Guide

- Las variables son persistentes (se conservan) entre celdas de código!. 🔥

- Para llamar a la línea de comandos, debemos usar primero un signo de admiración ! y luego un comando válido, por ejemplo !pwd o !pip install session-info.

## Google Colab: ciencia de datos

Puedes cargar archivos a tu notebook desde tu computadora, pero se borrarán una vez cierres tu notebook. También puedes vincular tu google drive para que tome los archivos desde ahí y de esta forma conservarlos.

Colab está enfocado a trabajar con Python (también puede usar otros lenguajes) y ya trae librerías de ciencia de datos precargadas como:

- matplotlib: Generación de gráficos a partir de listas o arrays.

- numpy: Cómputo científico para la manipulación de vectores.

- pandas: Manipulación y análisis de datos de tablas y series temporales.

- scipy: Herramientas y algoritmos matemáticos.

- seaborn: Visualización de datos estadísticos.

Colab también tiene fragmentos de código (parecido a la herramienta para insertar funciones de Excel) que te facilita la programación.
Con ctrl + shift +p abres la paleta de comandos, si escribes shortcuts o atajos de teclado te mostrará una lista de todos los atajos que puedes ejecutar en Colab.

## Utilizar Deepnote

- Deepnote es un servicio en la nube basado en Jupyter Notebooks. No requiere configuración y tiene un trabajo a nivel de proyecto. Tiene colaboración en tiempo real, integración con múltiples Apps y tiene acceso a una terminal o línea de comandos integrada 😎.
- Tiene también variables de entorno y permite publicar proyectos (para construir portafolio). 🎉
- Podemos correr y agregar lo mismo que en Colab, pero además podemos subir archivos que se quedan siempre en el proyecto.
- Permite previsualizar los archivos CSV de manera muy bonita 😄.
- Parte de lo poderoso de Deepnote es que podemos integrar muchas cosas 🔥.
- No solo podemos agregar celdas de código y de texto, si no que en la opción de Bloque vienen muchos más tipos, como input, chart, dataframe sql, etc 🤯. Puede crear gráficas de manera automática sin código!
- Para acceder a los atajos de teclado usamos Ctrl + i.
- También es importante resaltar que tenemos una terminal integrada 🤖.

## Uso de VSCode notebooks

* Esto es un nuevo estilo de Notebook, integrado dentro de VSCode 🤯.
* Puedes abrir VSCode en una carpeta específica para ver todos los archivos dentro (y solo esos). Menos distracción que tener todo abierto con WSL. 😆
* Podemos correr los archivos .py directamente en la terminal dando click en ▶️.
* Con las extensiones que instalamos, podemos darle formato de manera automática a nuestro código 🐍.
* Dentro de los Jupyter Notebook en VSCode podemos usar todas estas extensiones 💕. La extensión de los Notebooks es .ipynb. Podemos exportar los notebooks a texto plano!.
