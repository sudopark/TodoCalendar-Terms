# 2. Entrada rápida por IA

[← Índice](./README.md)

---

Descreva o que você quer em linguagem natural e o app monta para você — "almoço com a Sara sexta ao meio-dia", "passa o dentista para terça que vem", "marca a lavanderia como concluída". Sem formulários, sem seletor de data.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/ai-input.png" alt="Entrada rápida por IA" width="280">

A entrada rápida por IA exige login. Todo o resto do app funciona sem conta.

---

## O que ela pode fazer

- Criar tarefas e compromissos, com horário, recorrência e tipo de evento deduzidos do que você disse
- Alterar um evento existente — mudar de dia, renomear, trocar o horário
- Concluir uma tarefa, ou desfazer uma conclusão
- Excluir um evento
- Resolver várias coisas em uma só solicitação ("adiciona academia segunda, quarta e sexta às 7h")

---

## Formas de enviar uma solicitação

### No app

Toque no botão de IA na tela do calendário. A folha de entrada abre com dois modos, e você alterna entre eles quando quiser:

- **Voz** — fale e veja a transcrição aparecer ao vivo. Precisa de permissão de microfone e de reconhecimento de fala; se alguma delas for negada, o app oferece abrir os Ajustes do iOS ou passar para o teclado.
- **Teclado** — digite. Útil quando você está em um lugar onde não dá para falar.

### A partir de uma imagem

**Ler a partir de uma imagem** transforma uma foto em eventos. Escolha **Tirar uma foto** ou **Escolher da biblioteca**; o app lê o texto da imagem — uma grade de aulas, um cartaz de evento, a captura de tela de uma mensagem — e mostra o que encontrou, para você corrigir o que tiver saído errado antes de enviar.

Dá para anexar uma instrução para direcionar o resultado, como "adicione isso como tarefas", no campo **Instruções adicionais (opcional)**. Se não houver texto legível na imagem, o app avisa em vez de enviar uma solicitação vazia.

### Siri

Diga **"Ei, To-do Calendar"** — "Solicitação ao To-do Calendar", "Perguntar ao To-do Calendar", "Enviar uma solicitação ao To-do Calendar" e "Adicionar com IA no To-do Calendar" também funcionam. Você também pode dizer "Todo Calendar", sem o hífen. A Siri pergunta o que ela deve fazer e a solicitação roda **em segundo plano, sem abrir o app**. A Siri responde "Entendido. Vou te avisar quando terminar." e você recebe uma notificação quando o resultado estiver pronto.

### Botão de Ação

Associe o botão de Ação ao atalho **Enviar**. Um toque, você diz o que quer e está enviado — o app nem precisa abrir.

### Widget e Central de Controle

- **Widget Adicionar com IA** — um widget de Tela de Início ou de Tela Bloqueada que abre a tela de entrada de IA com um toque.
- **Central de Controle** (iOS 18 ou posterior) — adicione o mesmo controle à Central de Controle para ter uma entrada a um deslize de distância.

### Menu de compartilhamento

Compartilhe **texto ou imagem de qualquer outro app** direto para a IA do To-do Calendar. Está lendo uma mensagem com os detalhes de um encontro, ou olhando um cartaz nas Fotos? Toque em Compartilhar, escolha o To-do Calendar, acrescente uma instrução se quiser e envie.

A solicitação vinda do menu de compartilhamento também roda em segundo plano. Você recebe a confirmação de que ela foi enviada e confere o resultado no app.

---

## Como uma solicitação é processada

1. **Enviada** — sua solicitação parte. Se veio da Siri, do botão de Ação ou do menu de compartilhamento, você não precisa manter o app aberto.
2. **Processando** — o app mostra o andamento. Dá para **Parar** uma solicitação enquanto ela roda, mas parar descarta o trabalho em andamento e ele não pode ser retomado.
3. **Confirmação necessária** — se a solicitação for mexer em algo importante, o app pede sua aprovação antes e mostra exatamente o que pretende fazer. Há uma contagem regressiva; se ela expirar, é só pedir de novo.
4. **Comando concluído** — o resultado cai no seu calendário na hora, com um resumo do que mudou.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pt-BR/ai-result.png" alt="Resultado da IA" width="280">

Só uma solicitação roda por vez. Se você enviar outra enquanto uma ainda espera sua aprovação, o app pede que você resolva antes a que está pendente.

---

## Créditos

Cada solicitação de IA consome **créditos**, e seus créditos são renovados todo dia. Quanto sobrou aparece no topo da tela de entrada de IA, então você já sabe antes de enviar.

Quando eles acabam, a entrada rápida por IA espera a renovação do dia seguinte. Todo o resto do app continua funcionando.

---

## Permissões que podem ser solicitadas

| Permissão | Para que serve |
|---|---|
| Microfone + Reconhecimento de fala | Entrada por voz |
| Câmera | Tirar uma foto para **Ler a partir de uma imagem** |
| Fototeca | Escolher uma imagem já existente |
| Notificações | Avisar o resultado de uma solicitação em segundo plano |

Cada uma é pedida só quando você usa pela primeira vez o recurso que precisa dela, e o app continua funcionando sem ela — a entrada por voz recorre ao teclado, e a entrada por imagem, à digitação.

---

[← Índice](./README.md) · [Próximo: Widgets e Tela Bloqueada →](./03-widgets.md)
