# Frequência da visita

Essa restrição especifica quantas vezes uma visita deve ocorrer dentro de um número definido de dias. O TourSolver otimiza o planejamento distribuindo as visitas o mais uniformemente possível, enquanto considera todas as demais restrições aplicáveis.\
Observação: a restrição de frequência orienta o planejamento, mas não garante aderência perfeita aos intervalos definidos. A interface do TourSolver exibe um indicador mostrando o número de visitas que não atendem à frequência esperada.

**Formato:** Caractere 1/5

Se essa restrição estiver ativada, o **Dias trabalhados** deve também ser definido para os recursos.

***

**Exemplos**

**Exemplo 1:**

* **Frequência de visita = 3/5**\
  O cliente deve ser visitado **3 vezes dentro de 5 dias**.\
  O TourSolver busca manter um **intervalo de 2 dias** entre cada visita.

***

**Exemplo 2:**

* **Frequência de visita = 3/5\***\
  O cliente deve ser visitado **3 vezes dentro de 5 dias**.\
  O TourSolver prioriza atribuir todas as 3 visitas ao **mesmo recurso**.\
  Nesse caso, manter o espaçamento igual entre as visitas torna-se secundário.

***

**Exemplo 3:**

* **Frequência de visita = 1/5**\
  O cliente deve ser visitado **uma vez a cada 5 dias**.\
  Se **Dias trabalhados = 1–5**, o cliente será visitado:
  * uma vez entre **dias 1–5**
  * uma vez entre **dias 6–10**
  * uma vez entre **dias 11–15**\
    Para garantir um intervalo mínimo específico entre essas visitas, você pode usar o **Espaçamento mínimo entre visitas** .
