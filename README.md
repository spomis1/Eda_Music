<h1>Exploratory Data Analysis (EDA)</h1>
<div id="header" align="center">
  <img src="https://github.com/spomis1/Music_EDA/blob/main/img/Music.png" width="800"/>
</div>

## Spotify and Youtube Music Analytics Project


El presente trabajo de investigación tiene como objetivo realizar un Análisis Exploratorio de Datos tomando como base un Dataset que contiene información sobre canciones de distintos artistas de todo el mundo, recopilado el 7 de febrero de 2023 en las plataformas musicales Youtube y Spotify. El Dataset incluye atributos, características y métricas de más de veinte mil canciones. Incluye atributos como nombre de la canción, del artista y del álbum, características musicales como la bailabilidad, la energía y la emoción, y métricas de escuchas, likes y comentarios

//

The present research work has as objective to perform an Exploratory Data Analysis based on a Dataset containing information about songs of different artists from all over the world, collected on February 7, 2023 in the music platforms Youtube and Spotify. The Dataset includes attributes, characteristics and metrics of more than twenty thousand songs. It includes attributes such as song, artist and album name, musical characteristics such as danceability, energy and emotion, and metrics for listens, likes and comments.

<h2>Estructura del Proyecto</h2>

```
img/
├── Music.png
src/
├── data/
│ ├── Spotify_Youtube.csv
├── notebooks/
│ ├── EDA_Code.ipynb
├── utils/
│ ├── EDA_Music_PBI.pbix
│ ├── PPT_Presentation.pdf
│ └── Power_BI_Presentation.pdf 
└──  Memoria.pdf
README.md
```


<h2>Hipótesis</h2>

1-	Las canciones más populares son las más bailables, alegres y enérgicas.<br>
Nos basamos en la idea de que a las personas les atraen especialmente las canciones tienen características positivas

2-	Las canciones más escuchadas no pueden tener una duración muy larga.<br>
Partimos de la premisa que las personas no suelen escuchar muchas veces una canción muy larga.

Estudiaremos características musicales de canciones y sus métricas para poder contestar esta pregunta

Otras consultas
•	Artistas más populares en Spotify
•	Artistas más populares en Youtube
•	Canciones más escuchadas en ambas plataformas
•	Canciones con mayor interacción (likes y comentarios)

//

1- The most popular songs are the most danceable, happy and energetic ones. <br>
We base this on the idea that people are especially attracted to songs with positive characteristics.

2- The most listened songs cannot have a very long duration.<br>
We start from the premise that people do not tend to listen many times to a very long song.

We will study musical characteristics of songs and their metrics in order to answer this question.

Other queries
- Most popular artists on Spotify
- Most popular artists on Youtube
- Most listened songs on both platforms
- Songs with more interaction (likes and comments)

<h2>Proceso</h2>


Este proyecto se inició con la tarea de buscar datos apropiados para el estudio, lo cual implicó llevar a cabo una exhaustiva investigación. El segundo paso consistió en depurar los datos hasta lograr que fueran aptos para generar información reveladora que contribuyera a responder nuestras hipótesis. Sin embargo, nos encontramos con diversos desafíos, como la gestión de un extenso conjunto de datos, la conversión de los mismos al formato adecuado, la identificación y eliminación de entradas duplicadas, así como un tratamiento exhaustivo de los valores atípicos y el análisis detallado del comportamiento de cada variable.

Una vez depurados los datos, procedí a crear visualizaciones y gráficos con el objetivo de hacer que la información compleja fuera más accesible para cualquier tipo de audiencia. Todos estos pasos pueden revisarse en detalle en el archivo "EDA_Cocde.ipyb". Finalmente, llevé a cabo la creación de la presentación en PowerBi ("EDA_Music_PBI.pbix" y "Power_BI_Presentation.pdf") y realicé la exposición acompañada de diapositivas ("PPT_Presentation.pdf") en agosto de 2023.

//

This project commenced with the task of sourcing appropriate data for the study, a process that demanded extensive research. The second step involved cleaning the data until it was conducive to generating insightful information that would aid in addressing our hypotheses. However, there were challenges, such as dealing with a large dataset, converting the data to the appropriate format, identifying and eliminating duplicate entries, a thorough treatment of outliers, and studying the behavior of each variable.

Once the data was refined, I began creating visualizations and graphs to make the complex data more comprehensible for any audience. All these steps can be observed in the "EDA_Code.ipynb" file. Finally, I crafted the presentation in PowerBi ("EDA_Music_PBI.pbix" and "Power_BI_Presentation.pdf") and delivered the presentation accompanied by slides ("PPT_Presentation.pdf") in August 2023.


<h2>Dashborard</h2>

Haz clic en el icono de Power BI para interactuar con el dashboard.<br>
Click on the Power BI icon to interact with the dashboard.


<a href="https://www.novypro.com/project/eda---spotify-and-youtube-muisc-analytics">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" title="PowerBi" alt="PowerBi" width="100" height="100"/>
</a>



<h2>Librerias usadas</h2>
<div>
<img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" title="Numpy" **alt="Numpy" width="180" height="180"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" title="Pandas" **alt="Pandas" width="180" height="180"/>
<img src="https://matplotlib.org/stable/_static/logo_dark.svg" title="matplotlib" **alt="Matplotlib" width="220" height="180"/>
<img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" title="Seaborn" **alt="Seaborn" width="180" height="180"/>
<img src="https://www.statsmodels.org/stable/_images/statsmodels-logo-v2-horizontal.svg" title="statsmodels" **alt="statsmodels" width="180" height="180"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/SCIPY_2.svg" title="scipy" **alt="scipy" width="100" height="100"/>
</div>



<h2>Fuentes</h2> 
<a href="https://chartmetric.com/es"> <img src="https://chartmetric.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fzdrkqyxr%2Fproduction-alt%2Fecff7013f37cbf79115cca3d17b47b79de688c0b-161x32.svg%3Frect%3D6%2C0%2C148%2C32%26w%3D153%26h%3D33&w=1920&q=75" title="Chartmetric" **alt="Chartmetic" width="180" height="180"/> </a>
<a href="https://www.kaggle.com/datasets"> <img src="https://www.kaggle.com/static/images/site-logo.svg" title="Kaggle" **alt="Kaggle" width="180" height="180"/> </a>

<br></br>
<p>Espero que este proyecto haya sido de tu interés.<br>
No dudes en consultarme cualquier duda que te haya surgido y siéntete libre de compartirlo! Estoy abierto a recibir tus comentarios y sugerencias.

//

I hope this project has been of interest to you. Feel free to ask me any questions that may have arisen, and feel free to share it! I am open to receiving your comments and suggestions.

</p></br>

<h2>Autor:</h2>
<a href="https://www.linkedin.com/in/sebastianpomi/" target="_blank">Sebastian Pomi</a>

