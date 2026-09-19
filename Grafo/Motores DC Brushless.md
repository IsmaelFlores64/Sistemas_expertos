# Motores DC Brushless

Los motores DC brushless (BLDC) son la opción estándar de propulsión y arma de un [[Robot de Pelea]] por su alta relación potencia-peso, eficiencia superior al 85% y ausencia de escobillas, lo que elimina el desgaste mecánico y el arco eléctrico. Están formados por un rotor de imanes permanentes (normalmente neodimio) y un estator con tres fases que deben ser conmutadas electrónicamente en el momento exacto según la posición del rotor (sensores Hall o detección de fuerza contraelectromotriz o "sensored/sensorless"). Esto exige un controlador externo que genere las secuencias de conmutación.

La elección del motor depende de la categoría de peso, la [[Batería LiPo]], el tipo de propulsión y la estrategia de combate: se prioriza el par (KV bajo y motor "torque") para empuje y frenado, o la velocidad (KV alto y motor "speed") para armas rotatorias de alto impacto. Cada motor se maneja con un [[ESC - Controlador Electrónico de Velocidad]] independiente, y su respuesta debe estar condicionada a la corriente máxima que puede entregar la [[Batería LiPo]] sin caídas de tensión peligrosas. Los motores se montan con soportes desmontables en el [[Chasis y Blindaje]] para permitir reemplazo rápido entre rondas, ya que un motor sobrecargado por el calor de una pelea es la primera causa de falla mecánica.

### Nodos Relacionados

- [[Robot de Pelea]]
- [[Chasis y Blindaje]]
- [[ESC - Controlador Electrónico de Velocidad]]
- [[Batería LiPo]]
- [[Microcontrolador Principal]]
- [[Estrategia y Lógica de Combate]]