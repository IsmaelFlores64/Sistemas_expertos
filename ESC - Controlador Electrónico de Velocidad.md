# ESC - Controlador Electrónico de Velocidad

El ESC (Electronic Speed Controller) es un variador de potencia que conmuta las tres fases de un [[Motores DC Brushless|motor DC brushless]] y regula su velocidad y corriente. Internamente integra un puente trifásico de transistores MOSFET, un controlador de conmutación (a menudo con firmware como BLHeli o AM32), y en los modelos de gama alta un sensor de corriente y voltaje. En un [[Robot de Pelea]] su clasificación en amperios continuos y de pico debe superar holgadamente la corriente máxima que demandará el motor para evitar su degradación térmica durante una pelea.

El protocolo de control dominante es DShot, un protocolo digital de alta velocidad que envía los valores de PWM desde el [[Microcontrolador Principal]] sin necesidad de calibración y con menor latencia que el PWM clásico. La gestión de energía es crítica: el ESC debe operar dentro del voltaje y capacidad de descarga (C-rating) que entrega la [[Batería LiPo]], y sus cables de potencia deben estar blindados contra golpes en el [[Chasis y Blindaje]]. Muchos ESCs para robótica de pelea incluyen entrada para telemetría, con la que el [[Microcontrolador Principal]] monitorea corriente, temperatura y RPM para decidir la [[Estrategia y Lógica de Combate]] y proteger el sistema ante sobrecargas.

### Nodos Relacionados

- [[Robot de Pelea]]
- [[Motores DC Brushless]]
- [[Batería LiPo]]
- [[Microcontrolador Principal]]
- [[Chasis y Blindaje]]
- [[Estrategia y Lógica de Combate]]