# Batería LiPo

La batería LiPo es la única fuente de energía del robot y, por tanto, el componente que acota el rendimiento de todo el sistema. Sus especificaciones fundamentales son el número de celdas en serie (voltaje nominal), la capacidad en mAh y la tasa de descarga "C", que multiplicada por la capacidad indica la corriente máxima entregable. Un [[Robot de Pelea]] exige picos de corriente muy altos durante aceleraciones y giros bruscos, por lo que un C-rating insuficiente provoca caídas de voltaje, pérdida de par en los [[Motores DC Brushless]] y posibles resets de los controles.

La batería define la masa disponible del resto del robot: junto a los [[Motores DC Brushless]] y los ESCs, es de los elementos más pesados y debe fijarse en el [[Chasis y Blindaje]] con anclajes rígidos y protección anti-impacto, ya que un golpe puede deformar las celdas y causar incendio. El voltaje entregado alimenta directamente a los [[ESC - Controlador Electrónico de Velocidad]] para los motores y a través de un regulador o BEC alimenta al [[Microcontrolador Principal]]. La gestión térmica y de carga (celdas balanceadas) es esencial: una celda fuera de balance es la principal causa de fallas eléctricas prematuras y debe monitorearse entre combates para sostener una correcta [[Estrategia y Lógica de Combate]] durante todo el torneo. En la [[Competencia BotCrash]] el reglamento permite baterías LiPo, Li-ion o NiMH, siempre que el robot cargue con un interruptor general accesible externamente y un sistema failsafe que detenga los motores ante pérdida de señal del control remoto.

### Nodos Relacionados

- [[Robot de Pelea]]
- [[Competencia BotCrash]]
- [[Motores DC Brushless]]
- [[ESC - Controlador Electrónico de Velocidad]]
- [[Microcontrolador Principal]]
- [[Chasis y Blindaje]]
- [[Estrategia y Lógica de Combate]]