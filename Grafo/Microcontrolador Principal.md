# Microcontrolador Principal

El microcontrolador principal es el cerebro del [[Robot de Pelea]]: procesa las señales de control del operador (joystick y radio en frecuencia de 2.4 GHz), ejecuta la lógica de control en tiempo real y distribuye comandos de validación a los actuadores. Las plataformas más comunes son STM32, Teensy y Raspberry Pi Pico, elegidas por su potencia de procesamiento, cantidad de periféricos (PWM, UART, SPI, I2C) y soporte de librerías de robótica. La robustez es prioritaria: el firmware debe incorporar perros guardianes (watchdogs) y monitoreo de voltaje para que un golpe o un corte de alimentación no deje el robot en estado indeterminado.

El microcontrolador se ubica en el núcleo protegido del [[Chasis y Blindaje]] y se alimenta mediante el BEC o regulador que baja el voltaje de la [[Batería LiPo]] a niveles lógicos. Verifica los comandos de seguridad (armado/desarmado de motores), envía señales precisas a los [[ESC - Controlador Electrónico de Velocidad]] (comúnmente vía DShot) y puede recibir telemetría de corriente para ejecutar la [[Estrategia y Lógica de Combate]] de forma autónoma o asistida. La sincronización de giro entre los [[Motores DC Brushless]] suele implementarse en este chip, por lo que su frecuencia de reloj y gestión de interrupciones son determinantes para el rendimiento del robot.

### Nodos Relacionados

- [[Robot de Pelea]]
- [[Chasis y Blindaje]]
- [[Motores DC Brushless]]
- [[ESC - Controlador Electrónico de Velocidad]]
- [[Batería LiPo]]
- [[Estrategia y Lógica de Combate]]