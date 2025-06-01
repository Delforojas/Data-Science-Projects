⚽📊 **Análisis de Eficacia y Coste Goleador — Temporada 2024-25** 💸
==================================================================

### 🚀 Descripción  
Este proyecto examina el **rendimiento ofensivo** y la **rentabilidad salarial** de **11 atacantes** de la liga 2024-25.  
Combinamos estadísticas de producción (goles, tiros) con salarios para descubrir:

* ¿Quién marca con mayor frecuencia?  
* ¿Quién es más certero al rematar?  
* ¿Cuánto paga el club por cada gol o disparo acertado?

Los datos provienen de **Transfermarkt**, **FotMob** y **Capology**.

---

### 🔧 Tecnologías utilizadas
| Herramienta | Rol |
|-------------|-----|
| ✅ **Python** | Lenguaje principal |
| ✅ **Jupyter Notebook** | Entorno interactivo |
| ✅ **Pandas** | Manipulación de datos |
| ✅ **NumPy** | Cálculos numéricos |
| ✅ **Matplotlib & Seaborn** | Visualización de gráficos |
| ✅ **Git/GitHub** | Control de versiones & publicación |

---

### 📊 Metodología aplicada
1. **Carga y limpieza de datos**  
   * Lectura de tablas individuales (goles, tiros, salarios).  
   * Unión y saneo de valores nulos.  

2. **Cálculo de métricas derivadas**  
   * `Goles / Partido`, `Goles / Tiro`, `Costo / Gol`, `Costo / Tiro`.  
   * Rankings de eficacia y rentabilidad.

3. **Visualización**  
   * Barras horizontales de goles y minutos.  
   * Dispersión *Tiros vs. Goles* con eficiencia anotada.  
   * Tarta de porcentaje de goles del Top-11 vs. resto de la liga.  

4. **Análisis económico**  
   * Tabla ordenada por **€ por Gol** para detectar gangas o “goles de lujo”.  
   * Comparación `€ por Tiro` vs. `€ por Tiro a Puerta`.

5. **Conclusiones**  
   * Identificación de futbolistas **élite** (alto ratio y bajo coste).  
   * Recomendaciones de fichajes y renovaciones basadas en ROI goleador.

---

### 📦 Variables del dataset

| Categoría               | Campo                | Descripción                         |
|-------------------------|----------------------|-------------------------------------|
| **Volumen de juego**    | `Partidos`           | Encuentros disputados               |
|                         | `Minutos`            | Minutos totales                     |
| **Producción ofensiva** | `Goles`              | Goles anotados                      |
|                         | `Tiros`              | Disparos intentados                 |
|                         | `Tiros a Puerta`     | Disparos que fueron a portería      |
| **Economía**            | `Salarios (€)`       | Sueldo anual estimado               |

---

### 👥 Jugadores analizados
Mbappé • Raphinha • Lamine • Vinicius • Julián Alv • Lewandowsky • Budimir • Ayoze • Sorloth • Ferran • Sancet

---

### 🚀 ¡Ejecuta el notebook!
Clona el repo, instala las dependencias y lanza el cuaderno `Goleadores_Liga.ipynb` para reproducir todo el análisis paso a paso.
