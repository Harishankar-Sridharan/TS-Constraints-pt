# Ponderação de velocidade

Se os tempos de viagem observados forem geralmente muito baixos ou muito altos, o usuário pode ajustá-los especificando, para cada recurso, se ele opera mais rápido ou mais lento do que a velocidade definida nas estatísticas de estradas. Isso permite ao usuário adaptar os dados de tráfego às restrições específicas de cada recurso, preservando ainda assim as variações de velocidade com base na hora do dia e na direção do deslocamento.

O **Normal** valor é o padrão e serve como velocidade de referência definida no perfil do veículo e/ou fornecida pelos mapas Here (estatísticas de estradas).

**Formato:** Número

**Exemplo:**\
As estatísticas de estradas indicam uma velocidade de **50 km/h** na Avenue Aristide Briand em Bagneux.

* Se o usuário considerar essa velocidade muito alta, ele atribui um **Fator de Velocidade de 1,2 (mais lento)**. O recurso então viaja **20% mais devagar**, a **40 km/h** em vez de 50 km/h.
* Se o usuário considerar essa velocidade muito baixa, ele atribui um **Fator de Velocidade de 1,2 (mais rápido)**. O recurso então viaja **20% mais rápido**, a **60 km/h** em vez de 50 km/h.
