# Análisis del historial de escucha de Spotify
![image](https://github.com/user-attachments/assets/4d328eb8-670d-48cf-be13-5e794b5d3e39)

En este proyecto se buscó realizar un análisis parecido a "Spotify Wrapped" en el que se muestran las canciones, artistas, etc. más esuchados del año pero de manera más sencilla y breve.
Por privacidad, en los datos originales se borraron datos como "ip_addr", las cuales mostrarían la dirección de IP en la que se reproducieron las canciones.

## Herramientas
Fue analizado usando el lenguaje Python y librerías como Pandas, Matplotlib y Seaborn. Además, se usaron las herramientas de VSCode y Jupyter Notebook como entornos de programación.

# Proceso
Primero se hizo una limpieza de datos en las que se quitaron las columnas no pertinentes al análisis y luego se modificaron para que se pudiese manejar de manera más cómoda.
Por ejemplo, se cambiaron los nombres de las columnas.
![image](https://github.com/user-attachments/assets/e6804aa4-8352-42f1-b67f-a08e6e9bac54)

Y posteriormente se crearon nuevas variables para el análisis. Por ejemplo, se crearon variables que muestren los años únicos en los que se han reproducido canciones.
![image](https://github.com/user-attachments/assets/777a64ce-a4f3-42bc-adf8-1d80baf82c6a)

# Análisis
Primero se hizo un análisis general de los años 2017 al 2025 en el que se averiguaron:
1. TOP 5 artistas más reproducidos
2. TOP 5 canciones más reproducidas
3. TOP 5 álbumes más reproducidos
4. TOP 5 canciones más saltadas

También se hicieron gráficos que mostraban los patrones de escucha en el tiempo:
1. Horas de escucha más activas
2. Días de escucha más activos
3. Comparación de reproducciones por año
4. Distribución de escucha por mes
