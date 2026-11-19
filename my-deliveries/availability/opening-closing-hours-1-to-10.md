# Horários de abertura/fecho 1 a 10

### Horário de abertura/fecho

Essas restrições permitem especificar a janela de tempo durante a qual uma visita pode ocorrer.\
**Hora de abertura 1** indica o horário mais cedo em que a visita pode começar, e **Hora de fecho 1** indica o horário mais tarde em que ela pode se iniciar. Esta janela de tempo aplica-se a todos os dias, a menos que **Dias de abertura 1** esteja definido; nesse caso, a janela de tempo aplica-se apenas aos dias especificados.

Se nenhuma janela de tempo for definida para uma visita, ela pode ser realizada a qualquer momento nos Dias de abertura permitidos e dentro do horário de trabalho do recurso. Você pode configurar até quatro janelas de tempo diferentes (cada uma com seus próprios dias associados) para uma única visita.

**Formato:** HH:MM:SS

**Exemplo 1:**\
Hora de abertura 1 = 07:30:00 e Hora de fecho 1 = 11:30:00 criam uma janela de quatro horas durante a qual o cliente pode ser visitado.

**Exemplo 2:**\
Para um cliente que exige entrega entre 23:00 e 03:00, os horários devem ser deslocados para que caibam no mesmo dia. Isso permite que a ordem das visitas seja determinada corretamente.\
Por exemplo:\
Hora de abertura 1 = 19:00:00 e Hora de fecho 1 = 23:00:00 definem uma janela de quatro horas.\
Após a otimização, os horários planejados das visitas devem ser deslocados de volta ao intervalo de tempo original.\
Se o TourSolver programar a visita às 21:00, a visita real ocorrerá às 01:00 (= 23:00:00 + 2 horas).

Janelas de tempo que se estendem por vários dias não são suportadas. Por exemplo, uma janela de tempo das 23:00:00 às 03:00:00 não pode ser usada sem ajustar os horários.

Uma visita não pode começar antes da Hora de abertura. Por padrão, uma visita que começa dentro da janela de tempo pode continuar após a Hora de fecho. Se você desejar que a visita termine antes da Hora de fecho, ative o **Encerrar visita antes da hora de fecho** opção.

### Horários de abertura/fecho 2 a 10

**Horários de abertura e fecho 2**

Essas restrições permitem definir uma segunda janela de tempo que se aplica aos dias de visita especificados em **Possíveis dias de visita 2**.\
**Hora de abertura 2** indica o horário mais cedo em que uma visita pode começar, enquanto **Hora de fecho 2** especifica o horário mais tarde em que ela pode começar.

**Formato:** HH:MM:SS

**Exemplo 1:**\
Um cliente está disponível para entrega durante dois períodos separados:

* Manhã: 09:00 às 12:00
* Tarde: 14:00 às 17:00

**Para configurar isso, defina**:

* Hora de abertura 1 = 09:00:00
* Hora de fecho 1 = 12:00:00
* Hora de abertura 2 = 14:00:00
* Hora de fecho 2 = 17:00:00

**Exemplo 2:**\
Um cliente pode ser visitado em:

* Segunda-feira das 07:00 às 17:00
* Quarta-feira das 09:00 às 18:00

**A configuração seria:**

* Hora de abertura 1 = 07:00:00
* Hora de fecho 1 = 17:00:00
* Dias de abertura 1 = 1 (Segunda-feira)
* Hora de abertura 2 = 09:00:00
* Hora de fecho 2 = 18:00:00
* Dias de abertura 2 = 3 (Quarta-feira)

**Horários de abertura e fecho 3**

Essas restrições permitem definir uma terceira janela de tempo que se aplica aos dias de visita especificados em **Possíveis dias de visita 3**.\
**Hora de abertura 3** indica quando a visita pode começar, e **Hora de fecho 3** indica o horário mais tarde em que a visita pode começar.

**Formato:** HH:MM:SS

**Horários de abertura e fecho 4**

Essas restrições permitem definir um segundo intervalo de tempo que se aplicará aos dias de visita definidos em\
Possíveis dias de visita 4. Hora de abertura 4 corresponde ao horário a partir do qual a visita pode ser realizada.\
Hora de fecho 4 corresponde ao horário além do qual a visita não pode mais ser realizada.
