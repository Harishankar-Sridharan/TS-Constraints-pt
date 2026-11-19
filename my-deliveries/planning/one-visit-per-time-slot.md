# Uma visita por intervalo de tempo

Esta opção habilita o **repetição de uma visita** para cada período de tempo disponível.

**Formato:** Binário

* Se definido como **1**, o recurso **retorna ao depósito** entre repetições.
* Se definido como **0** (padrão), o recurso não **retorna ao depósito** entre repetições.

**Exemplo:**

* Uma visita tem 3 períodos de tempo durante o dia.
* Se esta restrição for definida como `1`, o recurso realizará a visita **três vezes**, retornando ao depósito **após cada visita**.
