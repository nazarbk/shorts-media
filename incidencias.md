# Incidencias de publicación

Las anota la tarea "Publicación Shorts". El fallo más reciente va arriba. Nunca se apuntan claves ni tokens.

## 2026-11-07 12:15 · Publicación Shorts: pizza ya publicada a mano (no se programa)
- Origen: comprobación anti-duplicados (getScheduledPosts / getAnalyticsDataByMetrics).
- «¿Y si tu pizza doblara su tamaño cada minuto? 🍕🌍» (pizza-x2-es) ya salió en YouTube el 2026-11-05 a las 17:00 con un post creado a mano en Metricool (id 417641063, https://www.youtube.com/shorts/wpfHZ_ejbHo, estado PUBLISHED).
- No se ha programado nada para evitar el duplicado. Se ha movido a programados.json con "hora": "ya publicado a mano".
- Ojo: en TikTok NO aparece publicado en los últimos 7 días (TKPO02/TKPO05). Si quieres que salga en TikTok, súbelo a mano (pizza-x2_tiktok.mp4) o pídelo.
- pendientes.json queda vacío: no hay vídeos en reserva.

## 2026-11-02 12:46 · Publicación Shorts (12:12) no programó nada
- La ejecución de las 12:12 no dejó rastro: no hubo commit ni posts en Metricool. Coincide con el LÍMITE DE USO de 5 horas del plan de Claude, agotado hacia las 12:00 y repuesto a las 12:30 (los agentes de animación también se cortaron por eso).
- Arreglo: la voz v2 se ha programado a mano para el 2026-11-02 a las 14:00. YouTube 413859598 con autoPublish y miniatura portada_1, que Metricool aceptó. TikTok 413859710 con notificación.
- Prevención: la ejecución de las 15:12 hace de reintento. Evitar lanzar trabajos pesados entre las 11:00 y las 12:15.

## 2026-11-02 10:00 · programación duplicada (corregido a mano)
- El estornudo ya se había publicado a mano el 1 nov y estaba programado otra vez para el 2 nov a las 14:00. Se ha pasado a borrador.

## 2026-11-01 · tarea sin ejecutar
- La tarea falló por el límite de uso del plan de Claude. No se programó nada.
