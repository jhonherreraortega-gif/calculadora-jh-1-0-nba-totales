# CALCULADORA JH 1.0 · NBA TOTALES

Prototipo web interactivo para proyectar el total de puntos de partidos NBA 2026–27 y compararlo con líneas Over/Under.

## Datos y alcance

- Calendario, marcadores, estadísticas, bajas reportadas y cuotas: feeds públicos de ESPN, sin API oficial documentada.
- La app muestra líneas de apertura y las últimas líneas prepartido recibidas; conserva capturas en el almacenamiento local del navegador.
- “Estrella” indica 20 o más puntos por partido en la temporada más reciente con estadísticas disponibles.
- El ajuste por ausencias es experimental y aproximado. Confirma lesiones y sanciones en fuentes oficiales.
- La proyección usa más peso de la línea de mercado al inicio (75%) y baja gradualmente hasta 50% al completar 10 partidos por equipo. El rango orientativo visible es fijo: proyección ±10 puntos. Las probabilidades Over/Under se estiman por separado y solo se señala inclinación desde 60/40; son experimentales y no están calibradas con suficiente historial.
- No es una predicción oficial ni una recomendación de apuesta.

## Uso

Abre `index.html` en un navegador o publica la raíz del repositorio con GitHub Pages. No requiere dependencias ni claves de API.

## Fuentes

- ESPN: https://www.espn.com/nba/scoreboard
- Reporte oficial NBA: https://official.nba.com/nba-injury-report-2026-27-season/
