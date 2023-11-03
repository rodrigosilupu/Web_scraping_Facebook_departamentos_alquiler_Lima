# Proyecto de Scraping y Análisis de Precios de Alquiler de Departamentos en Facebook Marketplace

Este proyecto tiene como objetivo obtener y analizar información sobre los precios promedio de alquiler de departamentos en Lima a partir de anuncios en Facebook Marketplace. Utiliza técnicas de web scraping para recopilar datos relevantes y visualiza los resultados en un gráfico de barras.

## Descripción del Proyecto

En este proyecto, hemos utilizado Python y diversas bibliotecas, como Selenium y BeautifulSoup, para automatizar la navegación en Facebook Marketplace y extraer información de los anuncios de alquiler de departamentos. Hemos definido parámetros como el precio mínimo, el precio máximo y el número de días desde la publicación, lo que nos permite obtener datos más específicos.

Los pasos clave del proyecto incluyen:

1. Navegación automatizada en Facebook Marketplace y carga de más resultados mediante scrolling.
2. Extracción de datos relevantes, como el título, el precio, el lugar y la URL de los anuncios.
3. Limpieza y organización de los datos en un DataFrame de Pandas.
4. Cálculo del precio promedio de alquiler por distrito.
5. Visualización de los resultados en un gráfico de barras utilizando la biblioteca Matplotlib.

## Requisitos del Proyecto

Para ejecutar este proyecto, necesitarás instalar las siguientes bibliotecas de Python:

- `selenium`: para la navegación automatizada en la web.
- `beautifulsoup4`: para analizar el contenido HTML de las páginas.
- `pandas`: para el procesamiento y análisis de datos.
- `matplotlib`: para la visualización de los resultados.

Asegúrate de que tengas Chrome instalado y la versión adecuada del controlador de Selenium para Chrome.

## Cómo Ejecutar el Proyecto

1. Clona este repositorio en tu máquina local.

2. Asegúrate de que todas las bibliotecas necesarias estén instaladas.

3. Modifica los parámetros, como el precio mínimo, precio máximo y días desde la publicación, según tus preferencias en el archivo `code.py`.

4. Ejecuta el script `code.py` para obtener los datos de Facebook Marketplace.

5. El script generará un gráfico de barras que muestra los precios promedio de alquiler por distrito y lo guardará en la carpeta "outputs".

6. Puedes ajustar el tamaño del gráfico y los detalles de las etiquetas según tus necesidades en el mismo script.

## Resultados

Los resultados se muestran en un gráfico de barras que te permite visualizar los precios promedio de alquiler por distrito en Lima. Además, se incluyen detalles sobre los parámetros utilizados en la consulta, como el precio mínimo, el precio máximo y el número de días desde la publicación.

¡Explora y analiza los datos para tomar decisiones informadas sobre el alquiler de departamentos en Lima!

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar o extender este proyecto, no dudes en abrir un pull request.

## Licencia

Siéntete libre de utilizar, modificar y distribuir el código como desees.

---

¡Espero que este proyecto te resulte útil y te inspire a explorar más sobre scraping y análisis de datos!
