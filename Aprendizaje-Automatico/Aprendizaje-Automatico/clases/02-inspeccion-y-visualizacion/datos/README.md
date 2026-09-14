# Datos sintéticos de Clase 2

[Volver a Clase 2](../README.md)

Todos los registros son ficticios y se crearon para practicar lectura y visualización. No describen personas, salarios ni mediciones reales. Los importes son ejemplos arbitrarios. Semilla usada para las series aleatorias: `20260914`.

| Archivo | Contenido | Formato |
|---|---|---|
| [empleados.csv](empleados.csv) | 12 empleados ficticios: id, Nombre, Sueldo | CSV con encabezado, coma, ISO-8859-1 |
| [empleados.xlsx](empleados.xlsx) | Los mismos 12 registros | Excel, hoja Sheet1 |
| [empleados.html](empleados.html) | Los mismos 12 registros | Tabla HTML, UTF-8 |
| [empleados.db](empleados.db) | Los mismos 12 registros | SQLite, tabla empleados |
| [datos.csv](datos.csv) | 12 registros: nombre, genero | CSV con encabezado, coma, ISO-8859-1; F/M son categorías ficticias del ejemplo |
| [datos.xml](datos.xml) | 12 personas: nombre, email, telefono y direccion/calle | XML, UTF-8; correos example.org y teléfonos no operativos |
| [anscombe.json](anscombe.json) | 44 puntos simulados: Series, X, Y | JSON, lista de registros; NO es el cuarteto de Anscombe |
| [iris.csv](iris.csv) | 150 filas: Sepal.Length, Sepal.Width, Petal.Length, Petal.Width, Species | CSV UTF-8; tres grupos sintéticos, NO es Iris original |
| [wine.data](wine.data) | 178 filas, clase y 13 medidas simuladas | CSV numérico sin encabezado, NO es Wine original |
| [wine.names](wine.names) | Orden de las 14 columnas de wine.data | Texto UTF-8 |

Los archivos empleados.csv, empleados.xlsx, empleados.html y empleados.db contienen la misma tabla para comparar formatos. En los ejemplos de `header=None` o `header=3`, la interpretación de la cabecera cambia intencionalmente para mostrar el efecto del parámetro; no son métodos de limpieza.

Para ejecutar localmente, abrí las notebooks desde su carpeta o desde la raíz del repositorio. En Colab, descargá y descomprimí el repositorio completo en `/content/`; la celda inicial detecta la carpeta `Aprendizaje-Automatico-main`. Podés ajustar `DATOS` si elegís otra ubicación.
