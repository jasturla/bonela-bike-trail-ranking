# Bonela Bike & Trail Ranking

Sistema para gestionar la clasificación semanal del club privado **Bonela Bike & Trail** a partir de la actividad reciente de Strava.

## Objetivo

Cada semana se introducen manualmente los datos de la actividad reciente del club. El sistema parsea las actividades, las clasifica, evita duplicados, conserva un histórico y genera rankings y reportes.

## Categorías

- 🚴 Rey de la Bici
- ⛰️ Rey de la Montaña
- 🥾 Rey del Senderismo
- 👑 General Bonela Bike & Trail

## Estados de clasificación

- `BIKE`
- `TRAIL`
- `HIKING`
- `EXCLUDED`
- `REVIEW`

Las reglas definitivas de puntuación se establecerán después de validar el parser y el clasificador.

## Flujo semanal

1. Copiar la actividad reciente del club desde Strava.
2. Introducir el texto en el sistema.
3. Parsear las actividades.
4. Clasificar cada actividad.
5. Detectar duplicados.
6. Añadir únicamente actividades nuevas al histórico.
7. Calcular rankings.
8. Generar Excel y resumen para WhatsApp.

## Desarrollo

El proyecto se desarrolla de forma incremental mediante Issues de GitHub y Codex. Cada componente debe tener pruebas antes de considerarse estable.
