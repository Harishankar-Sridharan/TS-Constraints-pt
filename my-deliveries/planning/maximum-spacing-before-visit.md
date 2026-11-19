# Espaçamento máximo antes da visita

Esta restrição define o **intervalo de tempo máximo permitido** entre duas visitas encadeadas.

**Formato:** HH:MM

**Nome técnico do campo:** `tsOrderBeforeMaxTimeSpacing`

**Depende de:** Começa depois

**Exemplo:**

* A Visita A e a Visita B estão encadeadas.
* O espaçamento máximo entre elas é definido como `01:30:00`.

Neste caso, **A Visita B deve começar dentro de 1 hora e 30 minutos após a Visita A**; caso contrário, a cadeia não pode ser agendada.
