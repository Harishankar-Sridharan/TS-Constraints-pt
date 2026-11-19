# Tempo trabalhado 1 a 10

O **Hora de Início/Fim 1 a 10** as restrições definem até quatro diferentes janelas de tempo diárias durante as quais um recurso pode iniciar e concluir suas visitas. Essas janelas de tempo ajudam a controlar quando um recurso pode executar tarefas dentro de um dia de trabalho.

Cada par—**Hora de Início** e **Hora de Fim**—representa um período de operação válido. Você pode configurar até quatro intervalos de tempo separados para refletir horários de trabalho variados, turnos divididos ou disponibilidade especial.

**Formato:** HH:MM\
Você pode definir entre uma e quatro janelas de tempo dependendo de quantos períodos de trabalho o recurso tem em um dia.

***

#### **Exemplo 1: Janela de Tempo Única**

O recurso trabalha todos os dias das **08:00 às 17:00**.

* _Hora de Início 1 = 08:00_
* _Hora de Fim 1 = 17:00_

Isso significa que o recurso pode realizar visitas apenas dentro desta única janela de tempo.

***

#### **Exemplo 2: Turno Dividido**

**O recurso trabalha em dois turnos**:

* Turno da manhã das **08:00 às 12:00**
* Turno da tarde das **14:00 às 18:00**

**Configuração**:

* _Hora de Início 1 = 08:00_, _Hora de Fim 1 = 12:00_
* _Hora de Início 2 = 14:00_, _Hora de Fim 2 = 18:00_

O sistema agendará visitas apenas dentro desses dois intervalos.

***

#### **Exemplo 3: Três Períodos de Trabalho Distintos**

**O recurso está disponível**:

* Início da manhã das **06:00 às 08:00**
* Meio-dia das **11:00 às 13:00**
* Fim de tarde das **16:00 às 19:00**

**Configuração**:

* _Hora de Início 1 = 06:00_, _Hora de Fim 1 = 08:00_
* _Hora de Início 2 = 11:00_, _Hora de Fim 2 = 13:00_
* _Hora de Início 3 = 16:00_, _Hora de Fim 3 = 19:00_

As visitas serão planejadas apenas dentro desses três blocos de tempo.

***

#### **Exemplo 4: Usando Todas as Quatro Janelas de Tempo**

**O recurso tem períodos curtos de disponibilidade variados ao longo do dia:**

* **07:00–09:00**
* **10:00–12:00**
* **14:00–15:00**
* **17:00–19:00**

**Configuração**:

* _Hora de Início 1 = 07:00_, _Hora de Fim 1 = 09:00_
* _Hora de Início 2 = 10:00_, _Hora de Fim 2 = 12:00_
* _Hora de Início 3 = 14:00_, _Hora de Fim 3 = 15:00_
* _Hora de Início 4 = 17:00_, _Hora de Fim 4 = 19:00_

De maneira semelhante, você pode configurar os seis tempos de trabalho restantes.

