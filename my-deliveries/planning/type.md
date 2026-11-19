# Tipo

Esta restrição especifica se uma visita envolve um **entrega/entrega** ou um **retorno/coleta**.

**Formato:** Binário

* **0** – A rota está em **modo de entrega**.
* **1** – A rota está em **modo de coleta**.
* **2** – A rota está em **modo de entrega**, que deve ser concluído **antes de quaisquer coletas** poderem ocorrer.

**Depende de:** Quantidade

**Exemplo:**\
Se um recurso deve primeiro entregar itens antes de recolher quaisquer devoluções, defina o valor para `2`.\
Se a visita envolver apenas uma coleta, defina o valor para `1`.
