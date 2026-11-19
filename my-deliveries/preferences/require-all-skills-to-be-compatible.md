# Exigir que todas as competências sejam compatíveis

Quando o **Compatibilidade com os recursos** restrição é aplicada (especialmente com vários valores), esta configuração permite especificar se **apenas uma** característica da lista é suficiente ou se **todas** as características listadas são necessárias.

**Formato:** Binário

* **0** – Apenas uma característica da lista é necessária.
* **1** – Todas as características da lista são necessárias.

**Valor padrão:** 1

**Exemplo:**\
Se uma visita pode ser realizada por um recurso que atenda **qualquer uma** das características listadas, defina o valor para `0`.\
Se a visita requer que um recurso atenda **todas** características da lista, deixe o valor como `1`.
