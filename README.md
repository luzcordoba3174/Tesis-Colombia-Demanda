# Tesis-Colombia-Demanda


## Archivos de procesamiento
Realizados en Python con Google Collab.

### API UN Comtrade de la ONU
- API_comtrade.ipynb - Procesamiento para la consulta de los datos en la página de Comtrade.

UN Comtrade proporciona una API gratuita y premium para extraer y descargar datos/metadatos del comercio internacional. Este paquete lo simplifica con una función de Python con los parámetros apropiados.

Este proyecto se implementa en The Python Package Index, por lo tanto, la estructura de carpetas sigue el diseño sugerido en Packaging Python Project. Los scripts principales se encuentran en /src/comtradeapicall/. Y la carpeta pruebas contiene scripts de ejemplos sobre cómo instalar y utilizar el paquete.

La plataforma de datos de comercio global más completa del mundo La base de datos Comtrade de las Naciones Unidas agrega estadísticas comerciales globales anuales y mensuales detalladas por producto y socio comercial para uso de gobiernos, instituciones académicas, institutos de investigación y empresas. Los datos compilados por la División de Estadística de las Naciones Unidas cubren aproximadamente 200 países y representan más del 99% del comercio mundial de mercancías. La información se puede extraer en una variedad de formatos, incluidas las herramientas de desarrollo de API para la integración en aplicaciones y flujos de trabajo empresariales. Los suscriptores reciben acceso a funciones adicionales para mejorar la eficiencia y la especificidad.

### Análisis de la Demanda Internacional

Desarrollar un algoritmo que clasifique el potencial exportador para Colombia en cuanto al mercado y productos no minero-energéticos.

- modelo.ipynb - Desarrollo de procesamiento y técnica de segmentación.

### Crear Proyecto Tableu
- tableau.ipynb - ETL (Procesamiento y despliegue de los datos, generación de archivo con extensión a Tableu)

Crear un tablero que compile de forma automatizada indicadores de comercio exterior sobre la demanda de productos no minero-energéticos en diferentes mercados del mundo.

- Se utiliza los datos de Procolombia (Trademap) de las exportaciones e importaciones realizadas por Colombia y de los demás países del mundo. Los datasets se componen de archivos planos por cada país que contienen información de códigos de productos de clasificación arancelarios HS6 y valor en USD de exportaciones e importaciones.
- Se desarrolla un ETL para el procesamiento de los datos para generar la plantilla que despliega el tablero.
- Se utiliza la librería Tableau para generar el archivo en formato hyper para el desarrollo del tablero.
