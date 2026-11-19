# Duração de uma parcela recortada de uma entrega

Esta restrição especifica o **duração mínima necessária para permitir que uma visita seja dividida** em múltiplas porções. Uma visita pode ser dividida em dias diferentes ou ao redor de uma pausa para o almoço. Este valor está intimamente ligado ao **Duração da visita** .

**Formato:**  HH:MM

**Exemplo:**

* A visita A tem um **Duração da visita** de 4 horas.
* A visita B tem um **Duração da visita** de 30 minutos.
* O **Duração de uma parte de uma visita dividida** está definido para 01:00

Isto significa que **apenas visitas com mais de 1 hora** podem ser divididas:

* A visita A pode ser dividida em múltiplas porções, se necessário.
* A visita B não pode ser dividida, pois é mais curta que a duração mínima da porção.

O **duração mínima para cada porção dividida** é controlada pelo **Duração limite para dividir visitas** .

**Regra adicional:** Uma visita **não pode ser dividida em mais de 16 blocos**.

**Depende de:**

* Duração da visita
* Duração limite para dividir visitas
