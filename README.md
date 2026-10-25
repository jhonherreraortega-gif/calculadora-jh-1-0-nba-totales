# CALCULADORA JH 1.0 · NBA TOTALES

Prototipo web interactivo para proyectar el total de puntos de partidos NBA 2026–27 y compararlo con líneas Over/Under.

## Datos y alcance

- Calendario, marcadores, estadísticas, bajas reportadas y cuotas: feeds públicos de ESPN, sin API oficial documentada.
- La app muestra líneas de apertura y las últimas líneas prepartido recibidas; conserva capturas en el almacenamiento local del navegador.
- “Estrella” indica 20 o más puntos por partido en la temporada más reciente con estadísticas disponibles.
- El ajuste por ausencias es experimental y aproximado. Confirma lesiones y sanciones en fuentes oficiales.
- La proyección con línea mezcla 50% modelo y 50% mercado. El rango de incertidumbre aumenta con pocos partidos de la temporada; la app solo señala inclinación Over/Under desde 60/40. Las probabilidades son estimaciones experimentales, no están calibradas con suficiente historial.
- No es una predicción oficial ni una recomendación de apuesta.

## Uso

Abre `index.html` en un navegador o publica la raíz del repositorio con GitHub Pages. No requiere dependencias ni claves de API.

## Fuentes

- ESPN: https://www.espn.com/nba/scoreboard
- Reporte oficial NBA: https://official.nba.com/nba-injury-report-2026-27-season/
