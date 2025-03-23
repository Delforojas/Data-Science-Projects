🎵📊 Análisis de Tendencias Musicales en YouTube y Spotify

🚀 Descripción

Este proyecto es el resultado final del curso de Udemy "Analisis de datos con Python TOLTAL en 7 dias ".Utilizando datos 
reales de plataformas como Youtube y Spotify .

A través de un Jupyter Notebook, se utilizan Pandas, NumPy y Matplotlib para procesar y visualizar datos, 
permitiendo identificar tendencias musicales y carasteristicas sonoras.
⸻

🔧 Tecnologías utilizadas

✅ Python - Lenguaje principal para el análisis
✅ Jupyter Notebook - Entorno de trabajo interactivo
✅ Pandas - Limpieza, análisis y manipulación de datos
✅ NumPy - Procesamiento de datos numéricos
✅ Seaborn & Matplotlib - Visualización de datos

📊 Metodología aplicada

1. 📥 Carga y exploración de datos
	•	Lectura de los datasets desde archivos CSV (YouTube y Spotify).
	•	Visualización de las primeras filas para conocer la estructura.
	•	Identificación de columnas relevantes como: Views, Likes, Comments, Stream, Energy, Danceability, Album_type, Artist.

2. 🧼 Limpieza y transformación
	•	Eliminación de columnas con más del 50% de valores nulos.
	•	Relleno de valores nulos en columnas numéricas con la mediana.
	•	Relleno de valores nulos en columnas categóricas con la moda.
	•	Conversión de tipos de datos (int, float).
	•	Creación de una nueva columna "Likes_to_Views".

3. 📐 Análisis estadístico
	•	Cálculo de media, mediana, desviación estándar, mínimo y máximo para métricas clave (Views, Likes, Comments, Stream).
	•	Agrupación por Album_type para calcular promedios y totales.
	•	Análisis de canciones con baja proporción de likes respecto a views (Likes_to_Views < 0.01).

4. 🔎 Segmentación y filtrado
	•	Identificación de canciones por tipo de álbum (album, single, compilation).
	•	Análisis específico de canciones con baja interacción (low_likes).
	•	Comparativa entre artistas más reproducidos en el subconjunto filtrado.

5. 📈 Visualización
	•	Gráfico de barras para comparar streams entre artistas.
	•	Mapa de calor de danceability según tipo de álbum.
	•	Gráficos de tendencias para visualizar la energía y otros atributos de las canciones.

⸻
