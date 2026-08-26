# 1. Noções básicas

[← Índice](./README.md)

---

## O calendário

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/calendar.png" alt="Calendário" width="280">

O calendário do mês é a tela inicial. Deslize para a esquerda e para a direita para mudar de mês e toque em um dia para abrir a lista de eventos dele logo abaixo.

- Cada dia mostra uma barra colorida por evento, mais um **+N** quando o dia tem mais eventos do que cabe na linha.
- A lista do dia segue esta ordem: tarefas sem horário → tarefas com horário → compromissos → feriados → eventos de calendários externos.
- Toque no cabeçalho para pular para qualquer data, ou use **Mover data** para escolher uma diretamente.

O quanto cada dia mostra é você quem decide: o nível de detalhe de cada evento, o tamanho do texto, as cores, os nomes dos feriados e o calendário lunar. [Personalização](./05-personalization.md) percorre cada ajuste pelo nome.

---

## Tarefas e compromissos

O app tem dois tipos de evento, e a diferença está em uma coisa: é algo que você marca como concluído?

| | Tarefa | Compromisso |
|---|---|---|
| Horário | Opcional | Obrigatório |
| Conclusão | Sim — é só marcar | Não |
| Sem horário | Fica na **Lista de tarefas atual** até você terminar | Não é possível |

Uma **tarefa sem horário** serve para algo que você precisa fazer em breve, mas ainda não agendou. Ela fica no topo do calendário e no widget Lista de tarefas atual até ser concluída.

Dá para converter nos dois sentidos a qualquer momento — **Converter em compromisso** / **Converter em tarefa**, no menu de mais opções do evento. Só a conversão de tarefa em compromisso exige um horário.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/event-detail.png" alt="Detalhes do evento" width="280">

Todo evento pode carregar uma **Localização**, um **Link** e uma **Anotação**. A localização vem com prévia do mapa e abre em um toque no app de mapas que você preferir; o link tem a sua própria prévia.

---

## Adicionar eventos

São três formas de adicionar um evento, conforme o quanto você quer digitar:

- **Adição rápida** — o campo de entrada no fim da lista do dia. Digite um nome, confirme e a tarefa está criada.
- **Detalhes completos** — toque em **+** para abrir o editor com horário, recorrência, lembretes, tipo de evento, localização, link e anotação.
- **Entrada rápida por IA** — descreva em linguagem natural e deixe o app montar o evento. Veja [Entrada rápida por IA](./02-ai-input.md).

Uma tarefa precisa só de um nome. Um compromisso precisa de nome e horário.

---

## Eventos recorrentes

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/repeat-options.png" alt="Opções de recorrência" width="240">

Em vez de pedir que você monte uma regra de recorrência a partir de menus, o app lê a data escolhida e oferece opções prontas para ela. Escolha uma quinta-feira e a lista oferece **Toda semana: quinta-feira** e **A terceira quinta-feira de cada mês**.

**Intervalos comuns**

- Todos os dias
- Toda semana · A cada 2 semanas · A cada 3 semanas · A cada 4 semanas — no mesmo dia da semana do evento
- Todo mês — na mesma data de cada mês
- Todo ano
- Todo ano (calendário lunar) — para aniversários e datas comemorativas seguidas pelo calendário lunar

**Por posição no mês**

- Todo dia útil — de segunda a sexta. Aparece quando o evento começa em um dia útil
- Todos os dias da última semana de cada mês
- A primeira / segunda / terceira / quarta / última **quinta-feira** de cada mês — o dia da semana é preenchido a partir da data escolhida, então um evento numa sexta-feira oferece **A última sexta-feira de cada mês**

**Término da recorrência**

Escolhida a recorrência, defina também quando ela para: **Nunca** para seguir sempre, **Em** para fixar a data em que ela acaba, ou **Após** um número de **ocorrências**.

Tarefas recorrentes se comportam de forma diferente de compromissos recorrentes:

- Uma ocorrência não concluída continua visível no calendário de hoje mesmo depois que o horário passa — ela não passa sozinha para a próxima ocorrência.
- Ao concluí-la, aquela ocorrência vai para a lista de tarefas concluídas e a próxima é criada.
- **Pular esta tarefa** leva você para a próxima ocorrência sem marcar a atual como concluída.
- Quando a recorrência tem condição de término e não há próxima ocorrência, a série se encerra.

Ao editar ou excluir uma ocorrência de um evento recorrente, você escolhe o escopo: **Somente este**, **A partir deste** ou **Todos os eventos**.

Para eventos de um calendário externo conectado, a opção de calendário lunar não é oferecida — os calendários externos não têm onde guardar uma regra de recorrência lunar.

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

As tarefas cujo horário já passou sem que fossem concluídas se juntam em uma seção **Tarefas não concluídas** no topo do calendário, para que uma tarefa esquecida não fique enterrada numa data já passada.

Tarefas sem horário e tarefas futuras não entram nessa conta — elas simplesmente ainda não venceram. Se preferir não ver a seção, dá para escondê-la por completo nos Ajustes.

---

## Tarefas concluídas

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/done-todos.png" alt="Tarefas concluídas" width="280">

Tudo o que você marca como concluído fica guardado e agrupado por quando você terminou — hoje, ontem, este mês e, depois, por mês e ano.

- Desfaça uma conclusão para trazer a tarefa de volta.
- Limpe em lote: **Todas as tarefas concluídas**, ou só as **Com mais de 1 mês / 3 meses / 6 meses / 1 ano**.

---

## Compartilhamento

Compartilhe **um dia, uma semana ou um mês** como texto ou como um cartão de imagem.

Antes de compartilhar, você filtra quais tipos de evento entram e escolhe se os nomes dos tipos aparecem, então dá para mandar a sua semana para alguém sem expor tudo o que há nela.

---

[← Índice](./README.md) · [Próximo: Entrada rápida por IA →](./02-ai-input.md)
