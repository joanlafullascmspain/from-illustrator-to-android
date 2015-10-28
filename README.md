# From Illustrator to Android
### Sistema para pasar, de forma automática, iconos de Illustrator a las diferentes resoluciones de Android.

##### Archivo "export_illustrator_android.jsx"

El archivo "export_illustrator_android.jsx" es el encargado de automatizar el proceso de conversión de nuestros iconos de Illustrator a Android en las diferentes resoluciones.

Este archivo .jsx debe colocarse, dentro de nuestra instalación de Adobe Illustrator, en la siguiente carpeta:

- *en castellano:* Adobe Illustrator *[version]*\Valores preestablecidos\es_ES\Secuencias de comandos
- *in english:* Adobe Illustrator *[version]*\Presets\en_GB\Scripts\

##### Diseño de los iconos en Illustrator

Se facilitan una serie de pautas con las que trabajar en Illustrator para que el sistema de automatización funcione correctamente:

1. Diseñaremos nuestro icono en la resolución de Android "XHDPI".

2. Cada icono deberá ser incluido en su propia "Mesa de trabajo" *(artboard).*

3. A cada mesa de trabajo que incluya un icono le cambiaremos el nombre por defecto y le asignaremos el nombre del icono.

4. Una vez tengamos nuestros iconos diseñados nos vamos a la opción de Illustrator:
*en castellano:* Archivo -> Secuencias de comandos -> export_illustrator_android

*in english:* File -> Scripts -> export_illustrator_android

5. Se abrirá una pequeña modal y nos pedirá en qué formatos queremos realizar la exportación.

6. A continuación nos dejará escoger la ubicación de los archivos resultantes.

Se incluye en el proyecto un archivo de Illustrator **icons-to-android.ai** que puede resultar útil a modo de plantilla.



