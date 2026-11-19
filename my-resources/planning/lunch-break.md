# Pausa de almoço

Estas restrições são usadas para definir a pausa para o almoço do recurso.

**Formato:** HH:MM

**Início:** Especifica o horário mais cedo em que o recurso pode começar sua pausa para o almoço.

**Fim:** Especifica o horário mais tardar até o qual a pausa para o almoço deve ser concluída. Quando essa restrição é usada, a pausa para o almoço definida pelo _Duração_ deve ocorrer inteiramente dentro da janela de tempo Início–Fim.

**Duração:** Indica a duração da pausa para o almoço. Essa duração é tratada como tempo de descanso, não como tempo de trabalho, e portanto é deduzida do total de horas de trabalho definidas para o dia.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

Exemplo 2:

Um recurso com:\
**Hora de início** = 09:00;\
**Hora de término** = 18:00;\
**Hora do almoço** = 01:00;\
será capaz de trabalhar (e cumprir visitas) durante um período de 8 horas (= 18 – 9 – 1).
