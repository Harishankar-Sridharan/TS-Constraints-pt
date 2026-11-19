# Dias de abertura 1 a 10

**Dias de abertura 1**

Esta restrição lista todos os dias possíveis de visita (até 64) durante os quais a janela de tempo definida por **Hora de abertura 1** e **Hora de fecho 1** se aplica.\
**Formato:** numérico ou data.

Você pode especificar esses dias individualmente (por exemplo, 1,4), como um intervalo (por exemplo, 1–4), como inteiros (1 a 64) ou usando formatos de data (por exemplo, 14/05/2016 ⇒ 17/07/2016).

**Exemplo 1:**\
**Dias de abertura 1 = 1,2,5** (ou **14/05/2016, 15/05/2016, 18/05/2016**)\
Isto significa que a visita pode ocorrer apenas nos dias 1, 2 e 5 no calendário (ou em 14/05/2016, 15/05/2016 e 18/05/2016) dentro da janela de tempo definida por **Hora de abertura 1** e **Hora de fecho 1**.

**Exemplo 2:**\
**Dias de abertura 1 = 1–5** (ou **14/05/2016 ⇒ 18/05/2016**)\
Isto significa que a visita pode ocorrer em qualquer dia de 1 a 5 (ou entre 14/05/2016 e 18/05/2016) dentro da janela de tempo definida por **Hora de abertura 1** e **Hora de fecho 1**.

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

**Dias de abertura 2**

Esta restrição define o conjunto de dias de abertura (até 64) durante os quais a janela de tempo especificada por **Hora de abertura 2** e **Hora de fecho 2** se aplica.\
Esses dias podem ser listados individualmente ou como um intervalo, e seguem o mesmo formato usado em **Dias de abertura 1**.

**Exemplo 1:**\
O cliente pode receber uma entrega em:

* **Segunda-feira** entre **07:00 e 17:00**, e
* **Quarta-feira** entre **09:00 e 18:00**.

**Configuração**:

* Hora de abertura 1 = 07:00:00
* Hora de fecho 1 = 17:00:00
* Dias de abertura 1 = 1
* Hora de abertura 2 = 09:00:00
* Hora de fecho 2 = 18:00:00
* Dias de abertura 2 = 3

**Exemplo 2:**\
O cliente pode receber uma entrega:

* De **Segunda a sexta** entre **07:00 e 17:00**, e
* No **Sábado** entre **09:00 e 12:00**.

**Configuração**:

* Hora de abertura 1 = 07:00:00
* Hora de fecho 1 = 17:00:00
* Dias de abertura 1 = 1–5
* Hora de abertura 2 = 09:00:00
* Hora de fechamento 2 = 12:00:00
* Dias de abertura 2 = 6

**Dias de abertura 3**

Esta restrição lista todos os dias de abertura (até 64) para os quais a janela de tempo definida por **Hora de abertura 3** e **Hora de fecho 3** se aplica. Esses dias podem ser especificados individualmente ou como um intervalo, usando o mesmo formato que **Dias de abertura 1**.

**Dias de abertura 4**
