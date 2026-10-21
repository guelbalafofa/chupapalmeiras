---
name: mensagens-de-venda
description: "Cria, reescreve e revisa mensagens de venda para leads que chegaram pelo site (formulário, pedido de orçamento, chat, botão de WhatsApp): primeira resposta, follow-ups, resposta a objeções, proposta sem resposta e reativação de lead frio. Use quando o usuário pedir para melhorar ou escrever uma mensagem para um lead, cliente em potencial, orçamento ou proposta, quando disser que o lead não respondeu, ou quando colar um rascunho de WhatsApp, e-mail ou DM de venda."
argument-hint: "[canal] [etapa] [rascunho ou dados do lead]"
---

# Mensagens de venda para leads do site

O lead do site já levantou a mão: preencheu um formulário, pediu orçamento ou clicou no WhatsApp. A mensagem tem dois trabalhos: mostrar que uma pessoa leu o pedido e facilitar o próximo passo.

## 1. Juntar o contexto

Pergunte só o que faltar. Se o usuário colou um rascunho, tire dele o que der.

1. **O que o lead fez:** em qual página, o que escreveu no formulário (com as palavras dele), o que pediu, quando.
2. **Canal:** WhatsApp, e-mail, DM do Instagram, SMS ou roteiro de ligação.
3. **Etapa:** primeira resposta, follow-up (qual tentativa), objeção, proposta enviada sem resposta, reativação.
4. **Oferta:** o que é vendido, preço ou faixa (se pode falar), prazo, garantia, diferenciais que dá para provar.
5. **Próximo passo desejado:** ligação de 15 min, visita, envio de orçamento, agendamento, pagamento.
6. **Quem assina:** nome e função de quem envia, e o tom da marca (formal, próximo, descontraído).

Se existir uma persona feita com a skill `audience-profile`, use as objeções e o vocabulário dela.

**Nunca invente** preço, prazo, desconto, garantia, depoimento, número de clientes, prêmio ou escassez ("últimas vagas", "só hoje"). Quando faltar um dado, deixe um `[colchete]` para o usuário preencher.

## 2. Regras da mensagem

- **A primeira linha prova que você leu o pedido.** Cite o que o lead pediu, de preferência com as palavras dele: "Vi que você pediu orçamento de [X] pra [Y] pelo site."
- **Um objetivo, um pedido de ação.** Termine com uma pergunta fácil de responder. "Fica melhor terça às 10h ou quarta às 15h?" funciona; "Fico no aguardo" não pede nada.
- **Curta.**
  - WhatsApp/DM: 2 a 4 linhas por balão, no máximo 2 balões.
  - E-mail: até ~120 palavras, assunto específico com até 50 caracteres, sem anexo na primeira mensagem.
- **Fato no lugar de adjetivo.** Troque "atendimento de qualidade e solução completa" pelo fato que o usuário forneceu: "a instalação leva 1 dia e a garantia é de 12 meses".
- **Fale do problema do lead.** A história da empresa só entra se responder a uma dúvida dele.
- **Nome do lead uma vez,** no começo.
- **Tom de conversa entre adultos.** "Você", frases diretas. "Pra" e "tá" só se a marca já fala assim (siga o rascunho ou pergunte).
- **Emoji:** no máximo 1, e só se a marca usa. Sem CAIXA ALTA, sem "!!!".
- **Pressão só se for verdadeira.** Prazo real pode ser citado; urgência inventada, não.

## 3. Frases e padrões proibidos

Soam como robô, telemarketing ou texto gerado por IA. Corte ou troque por algo específico.

**Aberturas vazias**
- "Espero que esteja bem" / "Espero que esta mensagem te encontre bem"
- "Venho por meio desta" / "Prezado(a) cliente" / "Gostaríamos de informar que"
- "Oi, tudo bem?" sozinho na primeira mensagem (gasta uma troca; junte com o contexto do pedido)
- "Somos uma empresa líder / referência no mercado com mais de X anos" como abertura

**Jargão de folder**
- "Solução completa / inovadora / de ponta / sob medida / 360°" sem dizer o quê
- "Alavancar", "potencializar", "impulsionar", "otimizar seus resultados", "transformar seu negócio", "levar ao próximo nível", "experiência única"

**Pressão falsa**
- "Não perca essa oportunidade única" / "Oferta imperdível" / "Corre que é só hoje" (quando não é)

**Fechamentos que não pedem nada**
- "Fico no aguardo do seu retorno"
- "Qualquer dúvida, estou à disposição"
- "Sem compromisso!" repetido

**Follow-ups preguiçosos**
- "Só passando pra saber se você viu minha mensagem"
- "Estou fazendo um follow-up" / "Conseguiu ver o orçamento?" sem nada novo

**Estruturas manjadas**
- "Não é só X, é Y" e qualquer frase que nega uma ideia para afirmar outra
- Três adjetivos ou três frases curtas no mesmo molde em sequência
- "Imagine…", "E o melhor?", perguntas retóricas em série
- Travessões costurando a frase toda

Para revisar padrões de "texto de IA" com mais rigor, aplique também as skills `voice-dna` e `slop-cop` (adaptando os exemplos em inglês para o português).

## 4. Estrutura por etapa

### Primeira resposta (o ideal é em minutos)
Contexto do pedido → uma informação útil ou uma pergunta de qualificação → pedido de ação com opções.

> Oi, Marcos! Aqui é a Ana, da [Empresa]. Vi que você pediu orçamento de energia solar pelo site, pra uma casa com conta de uns R$ 450.
> Pra eu calcular certinho, me manda uma foto da última conta de luz? Com ela consigo te passar o valor ainda hoje.

### Follow-ups sem resposta
Cadência sugerida: **D+1, D+3, D+7, D+14 (despedida)**. Cada follow-up traz algo novo:
- a resposta para a dúvida mais comum nessa etapa;
- um exemplo, foto ou caso parecido (só se o usuário tiver);
- uma opção menor ou mais simples;
- uma pergunta de sim ou não.

Despedida (deixa a porta aberta e costuma ter a maior taxa de resposta):
> Marcos, vou parar de te mandar mensagem pra não encher. Se o orçamento voltar a fazer sentido, é só responder aqui que eu retomo de onde paramos.

### Objeções
Acolha em uma frase, pergunte o que está por trás, ofereça uma saída concreta. Não discuta.

| O lead diz | Caminho |
|---|---|
| "Tá caro" | Pergunte com o que está comparando; mostre o que está incluso ou ofereça uma versão menor. |
| "Vou pensar" | Pergunte qual ponto ficou em aberto; combine uma data para retomar. |
| "Preciso falar com meu sócio / minha esposa" | Ofereça um resumo curto para encaminhar ou uma conversa com os dois. |
| "Já tenho fornecedor" | Pergunte o que faria trocar; deixe a porta aberta sem falar mal do concorrente. |
| "Me manda por e-mail" | Mande, e marque uma data curta para tirar dúvidas. |

### Proposta enviada sem resposta
Não pergunte "viu a proposta?". Destaque um ponto da proposta ligado ao que o lead pediu e faça uma pergunta de sim ou não ("Quer que eu ajuste o prazo pra caber em [mês]?").

### Reativação de lead antigo
Cite o pedido original e a data aproximada, traga um motivo real para voltar a falar (preço novo, agenda aberta, produto novo) e faça uma pergunta simples.

## 5. Como entregar

Ao **melhorar um rascunho**, devolva:
1. **Versão melhorada**, pronta para copiar e colar.
2. **O que mudei:** 3 a 5 tópicos curtos, citando o trecho original.
3. **Variação:** uma alternativa (mais direta ou mais calorosa), quando fizer sentido.
4. **Falta preencher:** os `[colchetes]` que dependem do usuário.

Ao **criar do zero**, entregue o mesmo. Se for uma sequência de follow-up, mostre cada mensagem com o dia de envio.

### Exemplo

**Antes**
> Olá, tudo bem? Espero que esteja bem! Somos a XYZ, empresa referência em energia solar com mais de 10 anos de mercado. Recebemos seu contato e gostaríamos de apresentar nossas soluções completas e inovadoras que vão transformar sua conta de luz. Fico no aguardo do seu retorno! Qualquer dúvida, estou à disposição.

**Depois**
> Oi, Marcos! Aqui é a Ana, da XYZ Solar. Vi que você pediu orçamento pelo site pra sua casa em [cidade], com conta de luz de uns R$ 450.
> Pra eu montar o orçamento certo, me manda uma foto da última conta? Com ela já te passo o valor ainda hoje.

**O que mudei**
- Tirei "Espero que esteja bem" e a apresentação da empresa: o lead já sabe com quem falou.
- Troquei "soluções completas e inovadoras" pelo que ele pediu (orçamento, casa, conta de R$ 450, dados do formulário).
- Troquei "Fico no aguardo" por um pedido concreto e fácil (foto da conta), com um ganho para ele (valor no mesmo dia).

## 6. Checklist antes de entregar

- [ ] A primeira linha mostra que alguém leu o pedido do lead?
- [ ] Existe um único próximo passo, fácil de responder?
- [ ] No WhatsApp, cabe na tela do celular sem rolar?
- [ ] Algum fato foi inventado (preço, prazo, depoimento, escassez)?
- [ ] Sobrou alguma frase da lista proibida?
- [ ] Dá para ler em voz alta para o lead sem constrangimento?

## 7. Limites

- **Só para leads que pediram contato (inbound).** Para lista comprada ou disparo em massa, avise sobre a LGPD e as regras do WhatsApp Business (fora da janela de 24 h só é permitido modelo aprovado) em vez de escrever o disparo.
- **"Não" é "não".** Se o lead pediu para parar, a única mensagem é de encerramento.
- **Horário:** sugira envio em horário comercial, no fuso do lead.
