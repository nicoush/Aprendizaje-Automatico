# Aprendizaje Automático

Repositorio de apoyo para las clases del **bloque de Aprendizaje Automático**. Aquí se comparten Jupyter notebooks con explicaciones, ejemplos en Python y actividades para practicar.

## Por dónde empezar

Comenzá por **Introducción a Pandas**, continuá con **Inspección y visualización** y luego avanzá a **Preparación de datos**. El repaso de Matplotlib y los ejemplos de lectura con Pandas quedan como materiales de consulta.

## Materiales por clase

### Clase 2 · Manipulación, limpieza y visualización

| Material | Qué vas a encontrar | Datos necesarios |
|---|---|---|
| [Introducción a Pandas: manipulación y limpieza](clases/02-inspeccion-y-visualizacion/notebooks/01-pandas-manipulacion-y-limpieza.ipynb) | Inspección, filtros, faltantes, duplicados, categorías, tipos, outliers y agrupaciones. Incluye actividades al final. | Genera datos sintéticos de clientes dentro del notebook. |
| [Inspección y visualización de datos](clases/02-inspeccion-y-visualizacion/notebooks/02-inspeccion-y-visualizacion.ipynb) | Histogramas, boxplots, relaciones entre variables e identificación de outliers con IQR. | Crea un dataset de ejemplo dentro del notebook. |
| [Repaso de Matplotlib](clases/02-inspeccion-y-visualizacion/notebooks/03-repaso-matplotlib.ipynb) | Notebook de repaso y consulta. | Incluye archivos sintéticos de Iris y Wine en la carpeta de datos. |
| [Uso de Pandas: lectura de archivos](clases/02-inspeccion-y-visualizacion/notebooks/04-lectura-de-archivos-pandas.ipynb) | Ejemplos de lectura de CSV, Excel, JSON, HTML, SQLite y XML. | Los archivos sintéticos necesarios están incluidos en la carpeta de datos. |

### Clase 3 · Preparación de datos

| Material | Qué vas a aprender | Datos necesarios |
|---|---|---|
| [Preparación de datos paso a paso](clases/03-preparacion-de-datos/notebooks/01-preparacion-de-datos.ipynb) | Conversión de tipos, limpieza, imputación, escalado, normalización, binarización y codificación de categorías. Cada ejemplo explica cuándo usar la función y qué precauciones tomar. | Cada ejemplo crea sus propios datos; no requiere descargar archivos adicionales. |

## Ejercicios y actividades

- **Clase 2:** al final de *Introducción a Pandas* está la sección «Actividades para practicar (extras, no son obligatorias)», con diez consignas sobre el dataset limpio: filtros, promedios, agrupaciones y nuevas columnas.
- **Clase 3:** la mini práctica propone cambiar un número o una categoría, anticipar el resultado y explicar qué información se conserva o se pierde.

Las actividades están dentro de los notebooks enlazados arriba. Actualmente no hay una carpeta independiente de ejercicios.

## Cómo trabajar con los notebooks

Los archivos `.ipynb` combinan texto, código y resultados. Podés abrirlos en GitHub para consultarlos; para ejecutar el código necesitás un entorno como Jupyter o Google Colab.

### En Google Colab

Abrí Colab, elegí la opción para abrir un notebook desde GitHub y pegá la dirección de este repositorio:

```text
https://github.com/nicoush/Aprendizaje-Automatico
```

Seleccioná el notebook de la clase y guardá una copia personal para conservar tus cambios. Para **Uso de Pandas** y **Repaso de Matplotlib**, descargá el repositorio desde **Code → Download ZIP**. Subí el ZIP a Colab, descomprimilo en `/content/` y ejecutá la celda de rutas del notebook. También podés subir directamente la carpeta de datos y ajustar `DATOS`.

### En tu computadora

Descargá el repositorio desde **Code → Download ZIP**, descomprimilo y abrí el notebook con Jupyter Notebook o JupyterLab. Ejecutá las celdas en orden, comenzando por las importaciones.

Los notebooks utilizan pandas, NumPy, Matplotlib, seaborn y scikit-learn. Desde la raíz del repositorio podés instalar las dependencias con `python -m pip install -r requirements.txt`. Abrí Jupyter con `jupyter notebook`. El notebook de Clase 3 indica **scikit-learn 1.2 o posterior**. Los ejemplos de Excel de *Uso de Pandas* utilizan `openpyxl`.

## Datos y disponibilidad

Los notebooks de introducción y limpieza, inspección y visualización, y preparación de datos crean datos de ejemplo dentro de sus celdas. Los datos sintéticos tienen fines educativos y no representan registros reales.

Todos los archivos necesarios para lectura con Pandas y repaso de Matplotlib están incluidos en [datos de Clase 2](clases/02-inspeccion-y-visualizacion/datos/README.md). Allí se describen los formatos, esquemas y codificaciones. Las versiones de Iris, Wine y `anscombe.json` son sintéticas: no son los datasets originales.

## Sugerencias para estudiar

- Leé la explicación antes de ejecutar cada ejemplo.
- Compará los datos originales con el resultado de cada transformación.
- Modificá un valor y anticipá qué debería ocurrir.
- Justificá tus decisiones: no todas las variables necesitan las mismas transformaciones.
- Guardá tus respuestas y experimentos en una copia personal del notebook.

Este repositorio acompaña el trabajo en clase. Las consignas y condiciones de entrega son las que indique el docente.

## Organización

- [Clase 2: inspección y visualización](clases/02-inspeccion-y-visualizacion/README.md)
- [Clase 3: preparación de datos](clases/03-preparacion-de-datos/README.md)

Cada clase reúne sus notebooks y, cuando corresponde, sus datos. Las actividades permanecen dentro de las notebooks.
