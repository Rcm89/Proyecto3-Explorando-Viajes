
# Proyecto de Planificación de Viajes

Este proyecto consiste en la extracción de datos, de dos apis, Tripadvisor y skyscraper, ambas a través de rapidapi, y el escrapeo de una la web https://www.civitatis.com/ para obtener la inforamción necesaria de cara a la planificación de viajes de clientes. Sobre los datos extraidos se realiza un EDA.

## Objetivos del Proyecto

Los objetivos principales del proyecto son:

1. **Extraccion de datos**: Haciendo request a apis, y escrapeando con Beautiful Soup y Selenium

2. **Análisis Exploratorio de Datos (EDA)**: Examinar la relación entre diferentes variables clave, centrando la atencion en el aspecto econóico pues se establece como premisa la prioridad de los clientes por conseguir un viaje a precios económicos

3. **Conclusiones**: Se establecen una serie de conclusiones a partir del analisis de los datos, que invito al lector que descubra adentrandose en el repositorio.

4. **Puntos de mejora** Se establecen una serie de puntos de mejora posibles para el Proyecto

## Instalación y Requisitos
Este proyecto usa Python 3.12 y requiere importar las siguientes librerías:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- Beautiful soup
- Selenium
- Requests

Para visualizar el proyecto en tu ordenador, sigue estos pasos:

1. **Clona el repositorio**:
   ```bash
   git clone [URL del repositorio]
   
2. **Navega a la carpeta del proyecto**:
   ```bash
   cd Proyecto3-Explorando-Viajes

3. **Ejecutar los archivos**:
   Ejecutar los notebooks llamados "scrap_civitatis.ipynb" y "vuelos_y_hoteles.ipynb" en el orden que se quiera
   y despues ejecutar el notebook llamado "EDA.ipynb"
