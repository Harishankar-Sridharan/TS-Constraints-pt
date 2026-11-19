# Atraso máximo

Esta restrição permite que você defina o **atraso máximo permitido** além do fim da janela de tempo de uma visita.

O **Penalidade por atraso** a restrição deve ser usada ao mesmo tempo.

**Formato:** HH:MM ou HH:MM:SS

**Depende de:**

* Hora de abertura
* Hora de fechamento
* Penalidade por hora de atraso

**Incompatível com:**

* Tolerância de atraso

**Exemplo**

Se a janela de tempo da visita de um cliente termina às **17:00** e o **Atraso máximo** estiver definido como **00:10**, é permitido que o recurso chegue até **10 minutos atrasado**, isto é, não mais tarde do que **17:10**.

Qualquer chegada além de **17:10** não será aceita, e atrasos dentro deste limite serão penalizados de acordo com a **Penalidade por hora de atraso**
