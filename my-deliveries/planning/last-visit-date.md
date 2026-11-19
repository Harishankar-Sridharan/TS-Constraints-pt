# Data da última visita

Esta restrição especifica **quantos dias se passaram desde a última visita** antes de iniciar o planeamento atual, para garantir que o intervalo mínimo entre visitas seja respeitado.

**Formato:** Inteiro negativo

**Nota:** Se a frequência de visitas tiver mais de uma recorrência, esta restrição é **não aplicada**.

**Exemplo:**

* **Frequência de visitas:** 1/5
* **Espaçamento mínimo entre visitas:** 2 dias
* **Data da última visita:** -1

Neste caso, o cliente será visitado a partir de **dia 2**, porque uma visita no dia 1 violaria o intervalo mínimo de 2 dias entre visitas.

**Depende de:**

* Frequência da visita
* Espaçamento mínimo entre visitas
