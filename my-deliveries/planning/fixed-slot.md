# Período fixo

Esta restrição designa um **visita prioritária**, fixando o **recurso, dia e hora** da visita se especificado.

**Formato:** Binário

* **0** – A visita é **não fixa**.
* **1** – A visita é **fixa** de acordo com as condições especificadas.

**Valor padrão:** 1

**Depende de:**

* Hora de abertura
* Duração da visita

**Exemplo:**

* Uma visita é agendada com a flag de prioridade definida como 1, hora de início às 09:00 e duração de 2 horas.
* O sistema garante que o recurso atribuído realize esta visita **exatamente às 09:00** por 2 horas, respeitando o horário de funcionamento.
