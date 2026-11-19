# Começa depois

Esta restrição permite que você **encadear visitas**, garantindo que duas visitas sejam realizadas no **mesmo dia pelo mesmo motorista**.

A visita à qual esta restrição é aplicada será agendada **após a visita à qual está vinculada**. Se qualquer visita na cadeia não puder ser agendada, **nenhuma das visitas na cadeia será posicionada**.

Se usado, o valor deve corresponder ao **ID do Cliente** da visita para encadear com.

**Formato:** Inteiro (correspondente ao ID do Cliente)

**Exemplo:**

* A Visita A tem ID de Cliente 101
* A Visita B tem esta restrição definida como 101

Neste caso, a Visita B será agendada **após a Visita A no mesmo dia pelo mesmo motorista**.

**Depende de:** ID do Cliente\
**Incompatível com:** Frequência da visita
