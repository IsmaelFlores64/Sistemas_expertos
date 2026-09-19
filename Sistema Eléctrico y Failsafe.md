# Sistema Eléctrico y Failsafe

El [[Sistema Eléctrico y Failsafe]] agrupa los requisitos de alimentación y seguridad eléctrica obligatorios de BotCrash. La energía proviene de una [[Batería LiPo]] (el reglamento permite también Li-ion y NiMH) con interruptor general externo accesible que corte toda la alimentación sin abrir el [[Chasis y Blindaje]]. Además es obligatorio un interruptor independiente para bloquear o apagar exclusivamente las [[Armas y Mecanismos]], sin cortar la tracción. El receptor de radio control debe incluir función failsafe: ante pérdida de señal del operador, el sistema detiene el [[Robot de Pelea BotCrash]] de forma automática en un estado seguro.

Desde el interruptor general, la potencia se reparte al [[ESC - Controlador Electrónico de Velocidad]] que comanda los [[Motores DC Brushless]] y al [[Microcontrolador Principal]] a través de un regulador o BEC. La secuencia de seguridad es crítica: el operador arma la tracción y luego el arma por separado, y en emergencia el failsafe y el interruptor del arma actúan de forma redundante. Todo el cableado debe soportar vibración e impacto, ya que una desconexión durante la pelea significa pérdida de control y posible derrota por inmovilización de 10 segundos según el [[Reglamento y Normativa BotCrash]].

### Nodos Relacionados

- [[Robot de Pelea BotCrash]]
- [[Reglamento y Normativa BotCrash]]
- [[Batería LiPo]]
- [[Motores DC Brushless]]
- [[ESC - Controlador Electrónico de Velocidad]]
- [[Microcontrolador Principal]]
- [[Armas y Mecanismos]]