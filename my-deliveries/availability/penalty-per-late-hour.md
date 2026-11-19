# Penalidade por hora de atraso

Esta restrição representa um **custo adicional aplicado por hora de atraso**. Dá ao usuário um controle mais refinado sobre o quão estritamente as janelas de tempo das visitas são respeitadas. **Nota:** Restrições relacionadas à tolerância devem ser usadas com cuidado, pois podem dominar o processo de otimização ao tornar os atrasos a prioridade principal de otimização.

**Formato:** Numérico (inteiro ou decimal)

**Exemplo:**\
Se você estiver disposto a aceitar desvios e distância adicional para respeitar melhor as janelas de entrega—por exemplo, viajar um extra **70 km** para evitar estar **5 minutos atrasado**—a penalidade pode ser calculada da seguinte forma:

* Custo por km = **0.5**
* Distância extra = **70 km**
* Fator de conversão = **12** (60 minutos / 5 minutos)

Penalidade por hora de atraso = **0,5 × 70 × 12 = 420**

Portanto, o valor a inserir para a **Penalidade por hora de atraso** restrição é **420**.

**Depende de:**

* Hora de abertura
* Hora de fechamento

**Incompatível com:**

* Tolerância de atraso
