# eb-2022-1-cc51
Repositorio para el desarrollo del TF de Administración de la Información

## Objetivo del trabajo

Para el presente trabajo final, debemos desarrollar un Análisis Exploratorio de Datos (EDA). Donde resolveremos un problema básico de Modelación de Datos, en nuestro caso, con la finalidad de conocer las tendencias de los videos de Youtube en Estados Unidos. A partir de ellos podremos responder a varios requerimientos de información que se presentarán a continuación.

## Autores

- Galindo Alvarez, Franco - [@FrowsyFrog](https://github.com/FrowsyFrog)
- Goyas Ayllon, Leonardo Andre - [@Elyeet9](https://github.com/Elyeet9)
- Villafuerte Ramirez, Diego Tomas - [@DTomasVr](https://github.com/DTomasVr)

## Breve descripción del conjunto de datos

Para el presente trabajo, empleamos el conjunto de datos llamado Hotel booking demand, la cual se obtuvo de la página web Kaggle. Este dataset fue modificado para incorporar ruido en los datos, con valores faltantes (NA) y datos atípicos (outliers).

El conjunto de datos empleado en el proyecto de análisis se denomina [Tendencias de las estadísticas de videos de YouTube (Trending YouTube Video Statistics)](https://www.kaggle.com/datasets/datasnaek/youtube-new), donde se modificó, incorporándole cuatro nuevas columnas.
Este conjunto de datos es un registro diario de los videos de YouTube de mayor tendencia, cuyo contenido incluye varios meses sobre datos de tendencias diarias de videos en los siguientes países:
- EE. UU. (US)
- Gran Bretaña (GB)
- Alemania (DE)
- Canadá (CA)
- Francia (FR)
- Rusia (RU)
- México (MX)
- Corea del Sur (KR)
- Japón (JP)
- India (IN)

Sin embargo, bajo el proyecto actual, solo se analizará el país de **EE.UU. (US).**

[(Clic aquí para ir al Informe Grupal - PDF Adjuntado)]([https://github.com/FrowsyFrog/EB-2022-1-CC51](https://github.com/FrowsyFrog/EB-2022-1-CC51/blob/main/Grupo%202%20-%20Administración%20de%20la%20Información%20TF.pdf))

## Conclusiones

- La categoría de vídeos con más apariciones en tendencias es “Entertaiment”
- La categoría de vídeos con más “Me gusta” es “Music”
- La categoría de vídeos con un mejor ratio entre “Me gusta” y “No me gusta” es “Shows”
- A partir de abril del 2018 el volumen de videos en tendencia disminuyó considerablemente.
- El canal con más videos que aparecieron en tendencias es ESPN.
- El estado con la mayor cantidad de vistas es Delaware.
- Gracias a un modelo de regresión lineal. si es factible predecir la cantidad de “Vistas”, “Me gusta” y “No me gusta”.
- Finalmente, gracias a la propuesta de modelo brindada, se facilita el hallar el promedio de vistas para fechas posteriores al 15/11/2017

## Licencia

Este proyecto analítico se encuentra bajo la licencia [Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)
