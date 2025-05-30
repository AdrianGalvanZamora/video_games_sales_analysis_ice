# Análisis de Ventas de Videojuegos para Ice

Proyecto realizado en marzo de 2025 como parte del bootcamp de TripleTen. Analicé datos históricos de ventas de videojuegos (hasta 2016) para identificar patrones que determinen el éxito de un juego, con el objetivo de planificar campañas publicitarias para 2017.

## Tecnologías
- Python (pandas, matplotlib, seaborn, scipy)
- Jupyter Notebook

## Estructura del Proyecto
- **Paso 1:** Estudio de datos generales (`games.csv`).
- **Paso 2:** Preparación de datos (limpieza, manejo de valores ausentes, creación de columna de ventas totales).
- **Paso 3:** Análisis exploratorio:
  - Distribución de lanzamientos por año.
  - Ventas por plataforma y tendencias.
  - Diagramas de caja para ventas globales.
  - Correlación entre reseñas y ventas.
  - Análisis de géneros.
- **Paso 4:** Perfil de usuario por región (NA, UE, JP):
  - Top 5 plataformas y géneros.
  - Impacto de clasificaciones ESRB.
- **Paso 5:** Pruebas de hipótesis:
  - Calificaciones de usuarios para Xbox One vs. PC.
  - Calificaciones de usuarios para géneros Acción vs. Deportes.
- **Paso 6:** Conclusiones generales.

## Archivos
- `notebooks/ice_videojuegos_analysis.ipynb`: Jupyter Notebook con el análisis completo.
- `data/games.csv`: Dataset original (si lo puedes compartir).
- `output/`: Capturas de gráficos (distribuciones, diagramas de caja, gráficos de dispersión).

## Instrucciones
1. Clona el repositorio: `git clone https://github.com/adriangalvanzamora/videojuegos-ice-analysis.git`
2. Instala dependencias: `pip install -r requirements.txt`
3. Abre el notebook: `jupyter notebook notebooks/ice_videojuegos_analysis.ipynb`
