## DatasetKaggle

<div align="center">
  <img src="https://media.es.wired.com/photos/66c4d1d1f37d94352f34926f/16:9/w_1920,c_limit/GettyImages-2112446687.jpg" alt="Texto alternativo" width="100%" height="90"/>
</div>

# Sobre este Dataset

Este conjunto de datos ofrece una recopilación exhaustiva de información sobre videojuegos que han vendido más de 100,000 copias en todo el mundo. La industria de los videojuegos ha experimentado un crecimiento explosivo en las últimas décadas, convirtiéndose en un componente clave del entretenimiento global. Este dataset proporciona un marco para el análisis de tendencias, el rendimiento comercial y las preferencias del consumidor a través de diversas métricas.

Los datos se obtuvieron extrayendo información de hltv.org, y fueron compartidos por el usuario [Nilim en Kaggle](https://www.kaggle.com/code/snanilim/video-games-sales-analysis-and-visualization/notebook).

# Columnas

Cada entrada en el conjunto de datos de videojuegos incluye el ranking de ventas, el nombre del juego, la plataforma, el año de lanzamiento, el género, el editor, y las ventas en América del Norte, Europa, Japón y el resto del mundo, además de las ventas totales a nivel mundial.

### Descripción de las columnas del dataset

1. **Ranking**: Posición del videojuego según sus ventas totales.
2. **Nombre**: Título del videojuego.
3. **Plataforma**: Sistema en el que se lanzó el juego (PC, PS4, Xbox, etc.).
4. **Año**: Año de lanzamiento del juego.
5. **Género**: Categoría del videojuego (acción, aventura, RPG, etc.).
6. **Editor**: Compañía que publicó el videojuego.
7. **NA_Sales**: Ventas en América del Norte (millones).
8. **EU_Sales**: Ventas en Europa (millones).
9. **JP_Sales**: Ventas en Japón (millones).
10. **Other_Sales**: Ventas en el resto del mundo (millones).
11. **Global_Sales**: Ventas totales a nivel mundial.

#Valores de Muestra

<table>
    <thead>
        <tr>
            <th>Ranking</th>
            <th>Nombre</th>
            <th>Plataforma</th>
            <th>Año</th>
            <th>Género</th>
            <th>Editor</th>
            <th>NA_Sales (millones)</th>
            <th>EU_Sales (millones)</th>
            <th>JP_Sales (millones)</th>
            <th>Other_Sales (millones)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Deportes de Wii</td>
            <td>Wii</td>
            <td>2006</td>
            <td>Deportes</td>
            <td>Nintendo</td>
            <td>41.49</td>
            <td>29.02</td>
            <td>3.77</td>
            <td>8.46</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Super Mario Bros.</td>
            <td>NES</td>
            <td>1985</td>
            <td>Plataforma</td>
            <td>Nintendo</td>
            <td>29.08</td>
            <td>3.58</td>
            <td>6.81</td>
            <td>0.77</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Mario Kart Wii</td>
            <td>Wii</td>
            <td>2008</td>
            <td>Carreras</td>
            <td>Nintendo</td>
            <td>15.85</td>
            <td>12.88</td>
            <td>3.79</td>
            <td>3.31</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Complejo deportivo Wii</td>
            <td>Wii</td>
            <td>2009</td>
            <td>Deportes</td>
            <td>Nintendo</td>
            <td>15.75</td>
            <td>11.01</td>
            <td>3.28</td>
            <td>2.96</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Pokémon Rojo/Pokémon Azul</td>
            <td>ES</td>
            <td>1996</td>
            <td>Juego de rol</td>
            <td>Nintendo</td>
            <td>11.27</td>
            <td>8.89</td>
            <td>10.22</td>
            <td>1.00</td>
        </tr>
    </tbody>
</table>


# Objetivos del Análisis del Dataset

1. **Identificar Tendencias de Ventas por Año**: Analizar cómo han cambiado las ventas de videojuegos a lo largo de los años.
2. **Comparar el Rendimiento de Plataformas**: Evaluar cuál plataforma ha tenido el mejor rendimiento en términos de ventas globales.
3. **Analizar la Relación entre Género y Ventas**: Investigar qué géneros son más populares y cómo varían en diferentes regiones.
4. **Evaluar el Impacto del Editor en el Éxito Comercial**: Examinar cómo el editor afecta las ventas y sus estrategias de marketing.
5. **Estudiar la Distribución de Ventas Globales**: Analizar ventas en diferentes regiones para entender preferencias de consumidores.

# Variables Elegibles

1. **Identificar Tendencias de Ventas por Año**
   - **Año**: Para observar cambios en las ventas a lo largo del tiempo.
   - **Global_Sales**: Para medir las ventas totales y analizar tendencias.

2. **Comparar el Rendimiento de Plataformas**
   - **Plataforma**: Para identificar diferentes sistemas y su rendimiento.
   - **Global_Sales**: Para medir las ventas totales de cada plataforma.


3. **Analizar la Relación entre Género y Ventas**
   - **Género**: Para categorizar los videojuegos según su tipo.
   - **Global_Sales**: Para medir el éxito comercial de cada género.


4. **Evaluar el Impacto del Editor en el Éxito Comercial**
   - **Editor**: Para identificar la compañía que publica cada juego.
   - **Global_Sales**: Para medir el éxito comercial asociado a cada editor.


5. **Estudiar la Distribución de Ventas Globales**
   - **Global_Sales**: Para observar las ventas totales de cada videojuego.
   - **NA_Sales**: Para analizar ventas en América del Norte.
   - **EU_Sales**: Para analizar ventas en Europa.
   - **JP_Sales**: Para analizar ventas en Japón.

# Referencias

https://www.kaggle.com/code/snanilim/video-games-sales-analysis-and-visualization/notebook#notebook-container
