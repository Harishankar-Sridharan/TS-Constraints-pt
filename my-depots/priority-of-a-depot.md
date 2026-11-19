# Prioridade de um Depósito

Esta restrição permite definir um Depósito como prioritário em relação a outros locais.

* Se dois Depósitos estiverem próximos entre si, o sistema dará prioridade ao local com o valor de prioridade mais elevado.
* Se os Depósitos estiverem distantes, o sistema continuará a considerar o valor de prioridade, mas também levará em conta a distância entre o recurso e os Depósitos.
* Um depósito com um valor mais alto é considerado de maior prioridade.

**Formato:** Número (inteiro)

**Exemplo:**

* O Depósito A tem um valor de prioridade de 8 e o Depósito B tem um valor de prioridade de 5.
* Se ambos os Depósitos estiverem próximos, o sistema visitará primeiro o Depósito A.
* Se o Depósito B estiver mais distante, o sistema ainda poderá priorizar o Depósito A dependendo da distância de deslocamento.
