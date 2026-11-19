# Dias trabalhados 1 a 10

Esta restrição especifica todos os **Dias Trabalhados** (até 64 dias) nos quais as janelas de tempo definidas pelas **Tempo de Trabalho** restrições se aplicam.

\
**Formato:** Valores de caractere.

Dias trabalhados podem ser inseridos individualmente (por exemplo, _1,4_), como inteiros (_1 a 64_), ou usando intervalos de datas (por exemplo, _14/05/2016 => 17/07/2016_).

**Exemplo 1:**

* _Dias trabalhados = 1,2,5_ (ou _14/05/2016, 15/05/2016, 18/05/2016_) significa que o recurso pode realizar visitas nos dias 1, 2 e 5 do período de planejamento (ou nas datas correspondentes) dentro das janelas de tempo definidas pelas restrições de Horário de Trabalho.
* _Dias trabalhados = 1–5_ (ou _14/05/2016 => 18/05/2016_) significa que o recurso pode realizar visitas em todos os dias de 1 a 5 do período de planejamento (ou em todas as datas do intervalo) dentro das janelas de Horário de Trabalho definidas.

**Exemplo 2:**\
Um recurso trabalha:

* Segundas-feiras das 07:00 às 17:00
* Quartas-feiras das 09:00 às 18:00\
  Configuração:
* _Horário de trabalho = 07:00–17:00_, _Dias trabalhados = 1_
* _Horário de trabalho 2 = 09:00–18:00_, _Dias trabalhados 2 = 3_

**Exemplo 3:**\
Um recurso trabalha:

* Segunda a sexta das 07:00 às 17:00
* Sábado das 09:00 às 12:00\
  Configuração:
* _Horário de trabalho = 07:00–17:00_, _Dias trabalhados = 1–5_
* _Horário de trabalho 2 = 09:00–12:00_, _Dias trabalhados 2 = 6_
