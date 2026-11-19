# Custo de subcontratação

Esta restrição permite ao usuário indicar que um pedido **pode ser entregue por um serviço de courier externo**. O motor de otimização então decide se é mais eficiente usar este serviço externo ou incluir o pedido em uma rota de entrega padrão. Note que essas visitas terceirizadas **não aparecem em rotas ou no planejamento**. O **custo de terceirização** é incluído no custo total da otimização.

**Formato:** Numérico (inteiro ou número real)

**Exemplo:**

* Cliente A: `1000`
* Cliente B: `100`

Estes valores representam o custo de usar um courier externo para cada cliente.
