# 1. Noções básicas

[← Índice](./README.md)

---

## O calendário

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/calendar.png" alt="Calendário" width="280">

A grade do mês é a tela inicial. Deslize para a esquerda e para a direita para mudar de mês e toque em um dia para abrir a lista de eventos dele logo abaixo.

- Cada dia mostra uma barra colorida por evento, mais um indicador **+N** quando há mais do que cabe.
- A lista do dia segue esta ordem: tarefas sem horário → tarefas com horário → compromissos → feriados → eventos de calendários externos.
- Toque no cabeçalho para pular para qualquer data, ou use **Mover data** para escolher uma diretamente.

O quanto a grade fica densa — altura das linhas, tamanho do texto dos eventos, texto em negrito, barras de cor, nomes de feriados, calendário lunar — é tudo ajustável. Veja [Personalização](./05-personalization.md).

---

## Tarefas e compromissos

O app tem dois tipos de evento, e a diferença está em poder ou não ser *concluído*.

| | Tarefa | Compromisso |
|---|---|---|
| Horário | Opcional | Obrigatório |
| Conclusão | Sim — é só marcar | Não |
| Sem horário | Fica na **Lista de tarefas atual** até você terminar | Não é possível |

Uma **tarefa sem horário** serve para algo que você precisa fazer em breve, mas ainda não agendou. Ela fica no topo do calendário e no widget de lista de tarefas atual até ser concluída.

Dá para converter nos dois sentidos a qualquer momento — **Converter em compromisso** / **Converter em tarefa**, no menu de mais opções do evento. Converter uma tarefa em compromisso exige um horário.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/event-detail.png" alt="Detalhes do evento" width="280">

Todo evento pode carregar uma **Localização** (com prévia do mapa e abertura em um toque no app de mapas que você preferir), um **link** com pré-visualização e uma **Anotação**.

---

## Adicionar eventos

São três caminhos, conforme o quanto você quer digitar:

- **Adição rápida** — o campo de entrada no fim da lista do dia. Digite um nome, confirme e a tarefa está criada.
- **Detalhes completos** — toque em **+** para abrir o editor com horário, recorrência, lembretes, tipo de evento, localização, link e anotação.
- **Entrada rápida por IA** — descreva em linguagem natural e deixe o app montar o evento. Veja [Entrada rápida por IA](./02-ai-input.md).

Uma tarefa precisa só de um nome. Um compromisso precisa de nome e horário.

---

## Eventos recorrentes

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/repeat-options.png" alt="Opções de recorrência" width="240">

Em vez de pedir que você monte uma regra a partir de menus, o app lê a data escolhida e oferece opções prontas para ela. Escolha uma quinta-feira e a lista traz, literalmente, **Toda Quinta-feira** e **O terceiro Quinta-feira de cada mês**.

**Intervalos comuns**

- Todos os dias
- Toda semana · A cada 2 semanas · A cada 3 semanas · A cada 4 semanas — no mesmo dia da semana do evento
- Todo mês — na mesma data de cada mês
- Todo ano
- Todo ano (calendário lunar) — para aniversários e datas comemorativas seguidas pelo calendário lunar

**Por posição no mês**

- Todo dia útil — de segunda a sexta. Aparece quando o evento começa em um dia útil
- Todos os dias da última semana de cada mês
- O primeiro / segundo / terceiro / quarto / último *dia da semana* de cada mês — para coisas como "a última sexta-feira do mês"

**Término da recorrência**

Depois de escolher a recorrência, defina como ela para: **Nunca**, **Em** uma data específica, ou **Após** um número de ocorrências.

Tarefas recorrentes se comportam de forma diferente de compromissos recorrentes:

- Uma ocorrência não concluída continua visível no calendário de hoje mesmo depois que o horário passa — ela não avança em silêncio.
- Ao concluí-la, aquela ocorrência vai para a lista de tarefas concluídas e a próxima é criada.
- **Pular esta tarefa** leva você para a próxima ocorrência sem marcar a atual como concluída.
- Quando a recorrência tem condição de término e não há próxima ocorrência, a série se encerra.

Ao editar ou excluir uma ocorrência de um evento recorrente, você escolhe o escopo: **Somente este**, **A partir deste** ou **Todos os eventos**.

Para eventos de um calendário externo conectado, a opção de calendário lunar não é oferecida — aquele calendário não tem como expressá-la.

---

## Tipos de evento e cores

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/event-type-list.png" alt="Tipos de evento" width="280">

Os tipos de evento são as suas categorias, e é deles que vem a cor com que o evento aparece no calendário. Crie quantos quiser, cada um com a sua cor.

- Desative um tipo para esconder do calendário todos os eventos dele — útil para silenciar um calendário de trabalho cheio sem desconectá-lo.
- Ao excluir um tipo, você escolhe manter ou excluir os eventos ligados a ele.
- Defina um **Tipo de Evento Padrão** para que os eventos novos já nasçam no lugar certo, sem você escolher toda vez.

Feriados e calendários externos conectados têm tipos próprios, então também dá para escondê-los de forma independente.

---

## Lembretes

Defina quantos lembretes por evento você precisar.

- **Eventos com horário** — no horário do evento, ou 1 / 5 / 10 / 15 / 30 minutos, 1 / 2 horas, 1 / 2 / 7 dias antes.
- **Eventos de dia todo** — às 9h ou ao meio-dia daquele dia, ou às 9h de 1 / 2 / 7 dias antes.
- **Personalizado** — escolha o intervalo que quiser.

Os padrões para eventos com horário e de dia todo são definidos separadamente nos Ajustes, então os eventos novos já vêm com lembrete. Os lembretes precisam de permissão de notificação; se ela estiver desativada, o app leva você até os Ajustes do iOS.

---

## Evento principal

Fixe aquela coisa que você não pode perder. O evento principal fica no topo do calendário independentemente da data que você estiver vendo, e tem um widget só dele.

Tarefas e compromissos não recorrentes podem ser marcados como principais. Compromissos recorrentes, não.

---

## Tarefas não concluídas

As tarefas cujo horário já passou sem que fossem concluídas se juntam em uma seção **Tarefas não concluídas** no topo do calendário, para que um item esquecido não escorregue para a semana passada e suma de vista.

Tarefas sem horário e tarefas futuras não entram nessa conta — elas simplesmente ainda não venceram. Se preferir não ver a seção, dá para escondê-la por completo nos Ajustes.

---

## Tarefas concluídas

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/done-todos.png" alt="Tarefas concluídas" width="280">

Tudo o que você marca como concluído fica guardado e agrupado por quando você terminou — hoje, ontem, este mês e, depois, por mês e ano.

- Desfaça uma conclusão para trazer a tarefa de volta.
- Limpe em lote: exclua tudo, ou só o que tem mais de 1 / 3 / 6 meses ou 1 ano.

---

## Compartilhamento

Compartilhe **um dia, uma semana ou um mês** como texto ou como um cartão de imagem.

Antes de compartilhar, você filtra quais tipos de evento entram e escolhe se os nomes dos tipos aparecem, então dá para mandar a sua semana para alguém sem expor tudo o que há nela.

---

[← Índice](./README.md) · [Próximo: Entrada rápida por IA →](./02-ai-input.md)
