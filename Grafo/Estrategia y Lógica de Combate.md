# Estrategia y Lógica de Combate

La estrategia y lógica de combate define cómo el [[Robot de Pelea]] usa sus capacidades físicas para ganar la pelea dentro de las reglas de la arena (puntos, KO, inmovilización o control). En su nivel básico, el operador pilota en remoto; en un nivel avanzado, el [[Microcontrolador Principal]] ejecuta asistencia en tiempo real: control de giroscopio para mantener orientación tras un impacto, mezcla de tracción diferencial, limitación de corriente bajo sobrecarga y secuencias automáticas de "self-righting" (autoenderezamiento) usando motores reversibles. La lógica de combate también gestiona los modos seguros: estado de armado deshabilitado durante el transporte y apagado automático del arma en zona peligrosa.

El diseño estratégico se traduce directamente en hardware. Un robot tipo "wedge" o empujador depende de un frente bajo del [[Chasis y Blindaje]] y alto par de los [[Motores DC Brushless]]; un robot "spinner" prioriza energía rotacional, un blindaje superior y reglas de juego más estrictas por su letalidad. El consumo planeado define la [[Batería LiPo]] y la corriente de los [[ESC - Controlador Electrónico de Velocidad]]. La estrategia también incluye gestionar el calor del sistema entre ataques, el control de ritmo de la pelea según los puntos acumulados, y la decisión de cuándo arriesgar una maniobra de alto consumo contra la probabilidad de quedarse sin energía para el resto del combate. En una competencia como la [[Competencia BotCrash]], la puntuación pondera daño (40%), control (30%), agresividad (20%) y estrategia (10%), por lo que el empuje y el pinning pesan más que el riesgo de un golpe puro; además, el combate dura 3 minutos y la derrota llega tras 10 segundos de inmovilización. El [[BattleDom - Arena de Combate]] introduce trampas mecánicas que obligan a planificar rutas seguras, y el reglamento prohíbe el control autónomo, por lo que toda lógica avanzada debe ejecutarse como asistencia o teleoperación del operador dentro del [[Robot de Pelea]].

### Nodos Relacionados

- [[Robot de Pelea]]
- [[Competencia BotCrash]]
- [[BattleDom - Arena de Combate]]
- [[Chasis y Blindaje]]
- [[Motores DC Brushless]]
- [[ESC - Controlador Electrónico de Velocidad]]
- [[Batería LiPo]]
- [[Microcontrolador Principal]]