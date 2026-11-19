# restrição Duração de Carregamento/Descarregamento por unidade

Esta restrição especifica o **tempo necessário no depósito para carregar ou descarregar uma unidade do produto**. O valor é multiplicado pelo **quantidade de produto** para carregar ou descarregar, dependendo do tipo de rota.

> **Nota:** Isto se aplica **apenas** ao **Quantidade 1** restrição das visitas e **não** às outras 23 quantidades possíveis.

**Formato:** HH:MM

**Exemplo:**

* **Duração fixa de carregamento/descarregamento:** 00:3:00
* **Duração de carregamento/descarregamento por unidade:** 120 segundos (2 minutos por unidade)
* **Quantidade a carregar:** 8 unidades

Cálculo:

* Tempo para unidades = 120 seg × 8 = 960 seg = 16 minutos
* Duração total no depósito = 30 min (fixo) + 16 min = **46 minutos**

**Depende de:** Quantidade (Entregas)
