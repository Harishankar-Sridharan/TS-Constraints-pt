# Duração mínima da pausa de condução

Esta restrição define a duração mínima que uma pausa de condução deve ter para ser contabilizada como tempo de descanso durante uma sessão de condução.

\
**Formato**: HH:MM

**Nota**:\
A duração da pausa de condução não é considerada tempo de trabalho pelo TourSolver. Portanto, o expediente total é prolongado pela duração equivalente da pausa.

**Exemplo**:\
Se uma pausa só for considerada descanso quando durar pelo menos 15 minutos, então _Duração mínima da pausa de condução = 00:15_.

Cenário de exemplo (Duração máxima de condução sem pausa + Duração da pausa de condução + Duração mínima da pausa de condução)

* Duração máxima de condução sem pausa = 04:30
* Duração da pausa de condução = 00:45
* Duração mínima da pausa de condução = 00:15

Isto significa que o recurso pode conduzir durante 4 horas e 30 minutos se fizer um total de 45 minutos de pausa. Essa pausa pode ser dividida, por exemplo, em três pausas de 15 minutos, ou numa pausa de 30 minutos seguida de uma de 15 minutos.

No entanto, se o recurso fez duas pausas de 20 minutos e uma de 10 minutos, ainda deve fazer uma pausa adicional de pelo menos 15 minutos para atingir os 45 minutos necessários de descanso qualificável, porque a pausa de 10 minutos não satisfaz o requisito mínimo de 15 minutos e, portanto, não é contabilizada.
