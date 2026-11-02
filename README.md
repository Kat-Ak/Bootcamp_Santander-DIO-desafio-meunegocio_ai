<div align="center">

# 🌐 AGENTEX | O gerenciador de fluxo de e-mail ideal para o comércio exterior

  <img src="http://img.shields.io/static/v1?label=STATUS&message=VERSAO%20BETA%20|%20v2%20|%2029/10/2026&color=purple&style=for-the-badge"/>

</div>
<h2 align="center">
Desafio 2 | MeuNegócio.AI: Construindo um Produto Digital com Agentes de IA e Lovable<br>
[ Bootcamp | Construa seu primeiro App com IA ]<br>
Santander em parceria com a plataforma da DIO
<p align="center">
  </div>
  
---
## 📟 Resumo do Enunciado

A proposta desse desafio é **construir do zero um [MVP](#mvp) (Mínimo Produto Viável) de um produto digital real utilizando a IA como [Co-Founder](#co-founder) ([ChatGPT](#chatgpt)) e uma plataforma [No-Code](#no-code) ([Lovable](#lovable)) para validar uma tese de negócios própria com motivação real e clara no mercado, contendo uma interface de cliente, formulários de triagem, [ganchos](#gancho) de conversão de [leads](#lead) e um painel administrativo funcional de controle de [leads](#lead)**.

Este repositório reúne os bastidores de planejamento, lógica de processos e inteligência estratégica desse desafio, utilizando linguagem prática, acessível e com glossário retrátil separados por conceitos de mercado & negócios e conceitos técnicos & interface & engenharia de IA.

---

## 🧬 Estrutura do Desafio | Índice Prático

- 🛰️ 1. [A Dificuldade Real & a Visão do Negócio](a-dificuldade-real---a-visão-do-negócio) 
- 📊 2. [Mercado & Negócios](mercado--negócios) 
- 🧪 3. [A Tese do MVP & os Processos Manuais](a-tese-do-mvp--os-processos-manuais) 
- 🤖 4. [Mega Prompt Otimizado & Correções Pós-Teste](mega-prompt-otimizado--correções-pós-teste) 

---

## 🛰️ 1. A Dificuldade Real & a Visão do Negócio

Empresários e profissionais que têm contato com parceiros de outros países entram em uma corrida contra o tempo devido à desorganização com fusos horários diferentes, gerando perdas críticas em prospecções e pedidos de cotação por puro atraso de resposta comercial.

**O Problema Prático:** Responder por ordem de chegada ignora o horário de expediente de quem recebe. Se um e-mail de Lisboa for respondido quando o escritório de lá já fechou, a oportunidade pode ser perdida para a concorrência.
**A Solução:** O **AGENTEX** ([aplicação](#aplicação) web que roda direto no navegador) distribuída e comercializada como um [SaaS tipo Freemium](#freemium), separa e ordena os e-mails recebidos automaticamente por prioridade de fuso horário internacional através do recurso [🧭 modo priorizar caixa de entrada], oferecendo um período de degustação grátis de 30 dias do Plano Padrão🔹.

---

## 📊 2. Mercado & Negócios

### Tamanho de Mercado
*   **[TAM](#tam) (Mercado Total Disponível):** Todas as micro e pequenas indústrias e empresas do mundo que compram ou vendem para o exterior usando e-mail.
*   **[SAM](#sam) (Mercado Disponível Atendível):** O grupo de pequenas empresas e indústrias localizadas no Brasil que lidam ativamente com transações internacionais comerciais semanais.
*   **[SOM](#som) (Mercado Alvo Prático):** As pequenas indústrias importadoras/exportadoras que usam Gmail ou Outlook e têm dificuldade para organizar o tempo e as tarefas da equipe sem processos automatizados.

### Quadro de Modelo de Negócios ([Business Model Canvas](#canvas))
*   **Proposta de Valor:** Automação inteligente da fila de atendimento de e-mails internacionais que se auto-organiza visualmente por fusos horários, minimizando perdas por atraso operacional.
*   **Fontes de Receita:** [Modelo de distribuição e comercialização SaaS tipo freemium](#freemium) baseado em assinaturas recorrentes. O usuário experimenta a plataforma na degustação grátis de 30 dias do Plano Padrão 🔹, enquanto o recurso automático avançado premium 🔼 atua como barreira de upgrade exclusivo da assinatura do Plano Pro 💠.
*   **Canais de Vendas:** Atração direta de [leads](#lead) no LinkedIn e parcerias em comunidades de negócios [B2B](#b2b).

---
## 🧪 3. A Tese do [MVP](#mvp) & os Processos Manuais

### A Tese do [MVP](#mvp) (Mínimo Produto Viável)
A nossa tese que o [MVP](#mvp)(Mínimo Produto Viável) precisa testar é: *"O pequeno empresário iniciante no mercado internacional tem interesse em um software que automatize sua rotina de e-mails recebidos, ordenando, filtrando e separando em caixinhas visuais de prioridade, que se auto-organizam em tempo real por fuso horário do país de origem enviado, para que seja atendido primeiro quem ainda não encerrou o expediente e pode estar esperando um retorno, minimizando perdas de negócios e contratos por demora no tempo de resposta? E caso não seja possível responder esses e-mails recebidos, 30 minutos antes do fim do expediente, através de um único botão inteligente enviar respostas automáticas para todos os e-mails no idioma recebido, buscando ter um bom padrão no nível de relacionamento comercial?"*

Pensando nisso, criamos O AGENTEX, uma [aplicação](#aplicação) web (software) que atua como um [Agente](#agente) de IA (identifica o fuso horário do país de origem, calcula o horário comercial de destino e toma a decisão autônoma de organizar aquela mensagem na caixinha de prioridade visual correta, além de disparar respostas multilíngues em momentos de [contingência](#contingência)), distribuída e comercializada como um [SaaS tipo freemium](#freemium) com período de oferta de degustação gratuita de 30 dias do Plano Padrão 🔹.

### Os Processos Manuais no [Backstage](#backstage)
Para manter o desenvolvimento enxuto, ágil e com custo praticamente zero na validação de teste pelo [Lovable](#lovable), os seguintes processos operam de forma manual:
1.  **Leitura de Dados:** O software simula uma caixa estática pré-configurada para o cenário do dia **29/10/2026 às 13:00h (Horário de Brasília)**.
2.  **Disparo de Mensagens:** O botão inteligente chamado [0️⃣ modo zerar caixa de entrada] de resposta automática multilíngue de [contingência](#contingência) abre uma janela [pop-up](#pop-up) com [minutas](#minuta) padrão prontas em 3 idiomas para simular a automação.
3.  **Fechamento Comercial:** Os botões de conversão capturam a intenção do clique e direcionam o [lead](#lead) para um atendimento humano estratégico no WhatsApp.

A tese valida o interesse de pequenos empresários em automatizar a rotina de e-mails por fuso horário. Os processos operam de forma enxuta com simulações de horários e interações direcionadas para atendimento humano.

---

## 🤖 4. [Mega Prompt](#mega) Otimizado & Correções Pós-Teste

### [Mega Prompt](#mega) Otimizado

Para garantir que o software ficasse pronto e funcional logo na primeira tentativa, minimizando o uso de créditos na conta gratuita do [Lovable](#lovable), foi desenvolvido este [Mega Prompt](#mega) estruturado em [Markdown](#markdown), aplicando a [tipografia](#tipografia) corporativa **Segoe UI**, fixando dados estáticos de fuso horário e interface responsiva e cores de alto contraste em [Tailwind CSS](#css).

<details>
<summary><b>Clique para visualizar o [Mega Prompt](#mega) utilizado no [Lovable](#lovable)</b></summary>

```[Markdown](#Markdown)
# [MEGA PROMPT](#mega): AGENTEX ([versão BETA](#beta) v2 29/10/2026)

## 1. Visão Geral, Identidade Visual e Design ([UI](#ui)/[UX](#ux))

Crie um software de página única ([SPA](#spa)) responsivo, clean, minimalista usando [Tailwind CSS](#css).
- **Menu Superior (Navbar - Canto Esquerdo):** Exibir o emoji 🌐 seguido imediatamente pelo texto em negrito "AGENTEX" e uma etiqueta cinza claro escrita "([versão BETA](#beta)) v2 29/10/2026)".
- **[Tipografia](#tipografia):** Use estritamente a fonte "Segoe UI" ou fontes nativas do sistema equivalentes, garantindo um visual limpo de produtividade corporativa e excelente legibilidade.
- **Cores Institucionais:** 
  - Fundo da página: Cinza ultra-claro/gelo (`bg-slate-50`) para dar aspecto de software profissional.
  - Estruturas e Títulos: Azul Marinho Escuro (`text-slate-900` ou `text-blue-950`).
  - Cards internos: Fundo totalmente branco (`bg-white`) com bordas finas e sombras suaves (`shadow-sm`).
- **Configuração de Tempo:** Fixe os horários internacionais de forma estática simulando exatamente o cenário da data de **29 de outubro de 2026** às 13:00 no Brasil (Horário de Brasília). Para evitar erros de cálculo da IA, utilize estritamente os seguintes horários locais fixos nos cards: Portugal (PT): 16:00h | Chile (CL): 13:00h | Estados Unidos (US): 12:00h | Catar (QA): 19:00h | Japão (JP): 01:00h (Madrugada)**.

## 2. Interface do Usuário (Telas dispostas na mesma página)

### Seção 1: [Landing Page](#landing) & Entrada (Topo da Página)

- **Título Principal (Grande, Centralizado e em Destaque):** O texto deve ser "AGENTEX \| O gerenciador de fluxo de e-mail ideal para o comércio exterior". Aplique a cor Azul Marinho Escuro (text-slate-900) e destaque bem o nome AGENTEX.
- **Subtítulo (Tamanho Médio, Cor Cinza Escuro, Centralizado):** "O software inteligente desenvolvido para otimizar sua rotina diária".
- **Texto Explicativo (Tamanho padrão, Cor Azul-acinzentado Escuro `text-slate-600`, Centralizado, Máximo de largura `max-w-3xl mx-auto mt-4`):** "Experimente o 🧭 Modo Priorizar Caixa de Entrada por um período de degustação grátis de 30 dias do Plano Padrão 🔹 e melhore seu timing comercial com uma rotina inteligente, respondendo primeiro quem ainda não encerrou o expediente, pois seus e-mails serão separados em 3 blocos de atendimento por prioridade baseado no fuso horário do país de origem. 

E caso perceba que não será possível responder a todos, 30 minutos antes do fim do expediente, envie respostas de [contingência](#contingência) automáticas multilíngues padronizadas no idioma do país de origem do e-mail (PT-PT [padrão internacional], EN, ES), agradecendo pelo recebimento, explicando que o e-mail está em análise e logo dará um retorno definitivo, buscando ter um bom padrão no nível de relacionamento comercial, através de um único botão inteligente chamado 0️⃣ Modo Zerar Caixa de Entrada, recurso automático avançado premium 🔼 exclusivo para assinantes do Plano Pro 💠."

- **Ação:** Dois botões seletores lado a lado com cantos arredondados:
  - `[ 📥 Atendo Fornecedores (Importador) ]`
  - `[ 📤 Atendo Clientes (Exportador) ]`
- Logo abaixo, exiba uma lista horizontal simples simulando "5 e-mails recebidos em 29/10/2026 às 13:00 (horário do Brasil)" contendo as siglas e os emojis das bandeiras dos países: 🇵🇹 PT, 🇨🇱 CL, 🇺🇸 US, 🇶🇦 QA, 🇯🇵 JP.
- Botão central de destaque em azul marinho ou ciano tecnológico: `[ 🧭 modo priorizar caixa de entrada ]`

### Seção 2: O Painel Automatizado (Exibido de forma elegante após o clique)

Ao clicar em [🧭 modo priorizar caixa de entrada], o software revela a estrutura de 3 caixinhas organizadoras estáticas dispostas lado a lado (em telas grandes) ou empilhadas (em telas mobile), simulando o padrão [Google Keep](#keep) / [Google Tarefas](#tarefas). Todos os cards internos devem exibir os dados padronizados e divididos por barras verticais: Emoji da Bandeira + Sigla + Nome do País + | + Idioma: XX + | + Horário Local Fixo.

1. **Caixinha 1: 🚨 Atendimento Prioritário**
- Visual: Borda superior fina na cor laranja para indicar a prioridade de atendimento operacional.
- Card Interno: 🇵🇹 PT [Portugal] | Idioma: [PT-PT](#pt-pt) [padrão internacional] | Horário Local: 16:00
- Texto de Justificativa: "Expediente encerrando em breve no destino (16h). Responda agora para garantir que seu e-mail possa ser lido ainda hoje."
- Interação: Um [checkbox](#checkbox) lateral. Ao ser marcado (tickado), aplica um risco (strikethrough) no texto do card e reduz a opacidade do bloco.

2. Caixinha 2: ⏳ Atendimento em Espera Padrão.
- Visual: Borda superior fina na cor amarela.
- Card 1: 🇨🇱 CL [Chile] | Idioma: ES | Horário Local: 13:00
- Card 2: 🇺🇸 US [Estados Unidos] | Idioma: EN | Horário Local: 12:00
- Texto de Justificativa: "Expediente em horário comercial pleno. Próximo da fila de atendimento. Respondendo hoje ainda pode ser lido hoje."
- Interação: [Checkboxes](#checkbox) individuais para marcar cada um como concluído.

3. Caixinha 3: 🌙 Atendimento em Espera Estendido.
- Visual: Borda superior fina na cor azul.
- Card 1: 🇶🇦 QA [Catar] | Idioma: EN | Horário Local: 19:00
- Card 2: 🇯🇵 JP [Japão] | Idioma: EN | Horário Local: 01:00 (Madrugada)
- Texto de Justificativa: "Expediente encerrado. Último da fila. Procure responder hoje para ser lido fora do seu horário de expediente ou somente amanhã, respondendo amanhã só será lido depois de amanhã."
- Interação: [Checkboxes](#checkbox) individuais para marcar cada um como concluído.

### Seção 3: Botão Inteligente [0️⃣ modo zerar caixa de entrada]  & Conversão (Rodapé)

### Botão Inteligente [0️⃣ modo zerar caixa de entrada] de Resposta Automática Multilíngue de [Contingência](#contingência) 

- Exiba o botão com uma pequena etiqueta roxa contendo o texto "PRO 💠": [ 0️⃣ modo zerar caixa de entrada ]

- Ação ao clicar: Abre uma janela [pop-up](#pop-up) elegante mostrando as [minutas](#minuta) padrão de e-mail de resposta automática do AGENTEX nos 3 idiomas:

- Versão [PT-PT](#pt-pt)[padrão internacional]: "Agradecemos o contacto. Confirmamos a receção do e-mail e informamos que a sua solicitação já se encontra em análise pela nossa equipa. Devido ao elevado volume de pedidos, daremos uma resposta definitiva o mais breve possível."
- Versão EN: "Thank you for your message. We have successfully received your email and our team is currently reviewing your request. Due to high demand, we will get back to you with a detailed response as soon as possible."
- Versão ES: "Gracias por su contacto. Confirmamos la recepción de su correo electrónico e informamos que nuestro equipo ya se encuentra analizando su solicitud. Debido a la alta demanda, le responderemos formalmente lo antes posible."
- Mensagem de trava comercial: "Esta é uma demonstração do recurso do botão inteligente chamado [0️⃣ modo zerar caixa de entrada] de resposta automática multilíngue de [contingência](#contingência) recurso automático avançado premium 🔼 exclusivo para assinantes do Plano Pro 💠. Com ele nenhum e-mail ficará mais sem resposta! Envio de respostas automáticas no idioma do país de origem do e-mail, faltando 30 minutos para o fim do expediente."
- **Botão de ação destacado (Estilização de Alta Conversão B2B):** 
  - O texto do botão deve ser limpo e direto: "Falar com Consultor e Ativar Plano Pro 💠"
  - Estilização visual: Use um botão elegante com fundo Azul Marinho Escuro profundo (classe Tailwind `bg-slate-900`), texto em branco (`text-white font-medium`), cantos suavemente arredondados (`rounded-lg`), preenchimento refinado (`py-2.5 px-5`) e uma transição suave ao passar o mouse (`hover:bg-slate-800 transition-colors`).
  - Destaque sutil de conversão: Logo ao lado do texto, inclua um pequeno ponto esmeralda elegante (bg-emerald-500 w-2 h-2 rounded-full inline-block ml-2 align-middle shadow-[0_0_8px_#10b981]) para indicar que há atendimento humano online e disponível imediatamente.
  - Comportamento: O clique simula o fechamento comercial estratégico via WhatsApp.

### Rodapé Geral (Seção de Conversão)

- Adicione um botão definitivo de conversão para o [MVP](#mvp) com sombra elegante.
- Texto do botão: "β Quero acesso antecipado ao AGENTEX (versão [BETA](#beta))" 
- Estilização visual do botão:
  - O botão deve ter um fundo dourado/âmbar vibrante usando a classe bg-amber-500 com texto em azul escuro profundo usando text-slate-900 para garantir alto contraste e legibilidade.
  - O símbolo 'β' deve ser destacado em negrito com a cor ciano/azul escuro contrastante (text-cyan-950).
  - Aplique cantos arredondados (rounded-lg), preenchimento generoso (px-6 py-3) e uma sombra projetada (shadow-md) elegante.

### Seção 4: Painel de Administração (Acesso via Rota /admin ou link discreto no rodapé)

- Uma tela com uma tabela simples contendo as colunas: nome do [lead](#lead), perfil (importador/exportador), recurso clicado, status (interessado na [versão Beta](#beta)), entregas pendentes, lembretes de retorno.

- Salve as interações locais usando o banco interno gratuito do [Lovable Cloud](#cloud).
```
</details>


### 🔧 Correções Pós-Teste

Após a primeira geração no Lovable, foram aplicadas duas novas versões para adequar às alterações/correções rápidas de [engenharia de prompts](#prompts) para blindar o layout e garantir o uso mínimo de créditos da plataforma:
* v1. **Otimização de Processamento (Fuso Horário):** Substituição do cálculo dinâmico de horários por dados estáticos explícitos para cada país (PT: 16h | CL: 13h | US: 12h | QA: 19h | JP: 01h), poupando créditos de IA.
* v2.1 **Melhoria e alteração do título:** Ajuste de "O organizador inteligente de e-mail do comércio exterior" para inclusão do nome do software + mudança para um título mais robusto condizente com a aplicação AGENTEX \| O gerenciador de fluxo de e-mail ideal para o comércio exterior.
* v2.2. **Correção de Acessibilidade & [UX](#ux) (Contraste Visual):** Ajuste fino nas classes do [Tailwind CSS](#css) do botão de conversão da pop-up (`bg-slate-900` com ponto de notificação `bg-emerald-500`), eliminando cores amadoras e garantindo alto contraste corporativo.
---

## 📈 Estratégias Comerciais

O software evidencia o potencial do negócio de conversão de [leads](#lead) [B2B](#b2b) através do [modelo de **comercialização SaaS (Software como Serviço)** baseado na estratégia de aquisição de clientes (precificação) Freemium](#freemium):
*   **Degustação de 30 Dias (Plano Padrão🔹):** O usuário experimenta gratuitamente o `🧭 modo priorizar caixa de entrada`. Uma automação inteligente para ordenar a fila de atendimento no início do dia de trabalho por fuso horário.
*   **Barreiras Visuais Premium 🔼 e [Paywall](#paywall) (Plano Pro 💠):** O botão inteligente `[0️⃣ modo zerar caixa de entrada]` de resposta automática multilíngue de [contingência](#contingência) opera bloqueado com opacidade reduzida sob um selo roxo corporativo "PRO 💠". O clique abre uma simulação informativa e direciona o usuário a assinar a versão SaaS completa (Plano Pro 💠) via suporte humano premium 🔼, validando a intenção de compra imediata.

## ☑️ Checklist de Requisitos do Enunciado

| Status | Requisito do Enunciado | Link de Evidência / Entregável |
| :---: | :--- | :--- |
| ✔️ | **Definição do Problema & Dores do Negócio** | [Ir para Seção 1](a-dificuldade-real--a-visão-do-negócio) |
| ✔️ | **Tamanho de Mercado & Business Model Canvas** | [Ir para Seção 2](2-mercado--negócios) |
| ✔️ | **Tese do MVP & Processos Manuais** | [Ir para Seção 3](a-tese-do-mvp--os-processos-manuais) |
| ✔️ | **Mega Prompt Otimizado & Correções Pós-Teste** | [Ir para Seção 4](mega-prompt-otimizado--correções-pós-teste) |
| ✔️ | **Captura de tela 1: landing page** | `print_tela/landing_page.png` |
| ✔️ | **Captura de tela 2: formulário de perfil** | `print_tela/formulario_perfil.png` |
| ✔️ | **Captura de tela 3: conversão via Whatsapp** | `print_tela/conversao_whatsapp.png` |
| ✔️ | **Captura de tela 4: painel admin (leads, clientes, entregas e lembretes)** | `print_tela/painel_admin.png` |
| ✔️ | **Segurança da Informação sem chaves de API expostas ou senhas salvas** | [Nenhum problema de Segurança encontrado] |
| ✔️ | **Endereço da aplicação publicada** | [Link da Aplicação no Lovable](https://agentex-mvp-beta.lovable.app) |

## 🏆 Conclusão | Melhorias & Próximos Passos

O desenvolvimento do software *AGENTEX* demonstrou a viabilidade de modelar um negócio internacional [B2B](#b2b) digital complexo sem digitação de código tradicional. Com um planejamento inteligente de processos aplicado ao uso combinado de [engenharia de prompts](#prompts) com [mega prompt](#mega) no [Lovable](#Lovable), guiamos a inteligência artificial para construir um [MVP](#mvp) interativo, seguro e funcional com uso mínimo de créditos.

Próximos Passos (Evolução)

• Automação Real com [n8n](#n8n) (plataforma de automações): Conectar a [API](#api) oficial do Gmail/Outlook via [n8n](#n8n) para que o Agente faça a ordenação real nas caixas de entrada dos assinantes.
• Integração do [Stripe](#stripe) [checkout](#checkout): configurar o período de teste gratuito (trial) de 30 dias no 🔹 Plano Padrão, realizando a primeira cobrança recorrente automática apenas após o vencimento deste prazo. E implementar o [Paywall](#paywall) no 0️⃣ Modo Zerar Caixa de Entrada que direcione para a página do [Stripe](#stripe), processando pagamento/upgrade imediato, para liberar o recurso instantaneamente após a confirmação da transação.
• Disparo Automático de [Leads](#lead): Configurar a chave do [Resend](#resend) para alertar o e-mail do administrador a cada novo [lead](#lead) coletado no formulário ou cliques nos [ganchos](#gancho) do WhatsApp.

## 🆘 Central SOS (Glossário Retrátil)

Se você tiver dúvidas sobre os termos utilizados neste projeto, clique nas setinhas abaixo para abrir a nossa biblioteca de conceitos:

<details>
  <summary> Clique para expandir o glossário 📇 CONCEITOS DE MERCADO & NEGÓCIOS</summary>

<a id="b2b"></a>
### B2B

**B2B (Business-to-Business / De Empresa para Empresa):** Modelo de comércio onde o cliente final não é uma pessoa física comum, mas sim outra empresa (como uma indústria que vende peças para outra fábrica, ou uma trading que fornece insumos para um importador).

<a id="canvas"></a>
### Business Model Canvas

**Business Model Canvas:** Mapa visual estruturado do negócio em um quadro dividido em blocos estratégicos utilizado para visualizar, estruturar, analisar e validar o funcionamento prático de uma empresa (proposta de valor, clientes, custos e canais) em uma única folha, funcionando como um guia dinâmico que substitui planos de negócios longos, evitando desperdício de tempo e dinheiro.

<a id="contingência"></a>
### Contingência

**Contingência:** Um recurso ou plano de segurança alternativo projetado para ser ativado em momentos de falhas, imprevistos ou panes técnicas (como a queda de um servidor ou falta de memória da IA), a fim de evitar gargalos (travamentos ou acúmulos de tarefas que atrasam todo o processo) e garantir a continuidade segura da operação, protegendo os dados. No Agentex, o recurso serve tanto para proteger o sistema contra panes tecnológicas quanto para resolver o gargalo do fim do expediente, permitindo responder automaticamente a todos os e-mails internacionais pendentes antes de fechar a fábrica.

<a id="escopo"></a>
### Escopo

**Escopo:** Definição exata de um projeto ou trabalho. É a descrição detalhada do alcance, limites, objetivos e entregas obrigatórias de uma solução. Funciona como um guia prático para alinhar exatamente o que o software faz e o que ele resolve, evitando o desperdício de tempo, dinheiro e recursos durante o desenvolvimento.

<a id="receita"></a>
### Fontes de Receita

**Fontes de Receita:** As diferentes maneiras e formatos estruturados que uma empresa ou produto digital utiliza para faturar, captar recursos financeiros e gerar lucros (como assinaturas mensais ou taxas por serviços).

<a id="freemium"></a>
### modelo de comercialização SaaS (Software como Serviço) baseado na estratégia de 
aquisição de clientes (precificação) Freemium

**Modelo de **comercialização SaaS (Software como Serviço)** baseado na estratégia de aquisição de clientes (precificação) Freemium / Modelo de Distribuição e Comercialização SaaS Tipo Freemium | (Modelo de Negócio):** 
Saas: É um modelo de comercialização e distribuição de tecnologia onde o cliente não precisa instalar nenhum programa no computador nem comprar uma licença cara para sempre. O software fica hospedado na nuvem (na internet) e o usuário o acessa direto pelo navegador (como um site), pagando um valor recorrente (um serviço de assinatura mensal ou anual) para utilizá-lo. Exemplos: Netflix, Spotify, Gmail, Canva, Notion e Agentex (você não "compra" o software deles, você assina o direito de usá-los pela internet). 
SaaS Tipo Freemium: É uma estratégia de negócios onde o software é hospedado na nuvem e distribuído com uma camada de acesso gratuito ou degustação (Free), mas que restringe os recursos mais valiosos, automatizados e avançados (Premium) sob uma barreira de pagamento ([Paywall](#Paywall)). No AGENTEX, o usuário experimenta as funções básicas do software de graça (free) como o "Modo Priorizar Caixa de Entrada" do Plano Padrão 🔹, mas precisa pagar um valor de assinatura (Plano Pro 💠) se quiser usar as funções mais avançadas e automatizadas [recursos premium] 🔼 "0️⃣ Modo Zerar Caixa de Entrada".

<a id="gancho"></a>
### Gancho

**Gancho (de conversão de leads):** link ou botão estratégico espalhado colocado em um texto, site ou anúncio, como uma isca estratégica criado especificamente para "fisgar" a atenção de quem está navegando e incentivar essa pessoa a tomar uma ação. O termo vem do comportamento de "pescar" o interesse do usuário no meio de tantas distrações digitais, servindo como o ponto de partida para transformar um visitante comum em um [lead](#lead).

<a id="lead"></a>
### Lead

**Lead:** contato (e-mail ou Whatsapp) de uma pessoa ou empresa (cliente em potencial) que demonstrou interesse real no seu produto ou software.

<a id="minuta"></a>
### Minuta

**Minuta:** Rascunhos ou modelos de textos padronizados e pré-redigidos. No Agentex, as minutas servem como mensagens de segurança automáticas prontas para serem enviadas aos parceiros comerciais sem que o usuário precise reescrever o e-mail do zero.

<a id="mvp"></a>
### MVP

**MVP (Mínimo Produto Viável):** Versão inicial e simplificada de um produto ou software (um protótipo), lançada no mercado com o menor custo e tempo possíveis, contendo apenas as funções principais para começar a rodar. Permite testar a ideia na prática e validar o interesse do mercado antes de investir em um desenvolvimento pesado. Ver se os clientes gostam da solução e faturar os primeiros reais. Usar os comentários dos usuários reais para melhorar o sistema aos poucos.

<a id="pt-pt"></a>
### PT-PT

**PT-PT [padrão internacional] | Português de Portugal | Português Europeu | Português Global:** O Português do Brasil (PT-BR) é uma variação única. Para o comércio exterior, o Brasil é a exceção da língua portuguesa. PT-PT é o padrão internacional utilizado por todos os outros países do mundo que também falam português fora o Brasil. O Agentex usa o padrão internacional (PT-PT) na resposta automática para garantir que a mensagem seja compreendida corretamente.

<a id="sam"></a>
### SAM

**SAM (Serviceable Addressable Market / Mercado Disponível Atendível):** A fatia do mercado total que está ao alcance geográfico, financeiro e operacional do seu modelo de negócio atual.

<a id="som"></a>
### SOM

**SOM (Serviceable Obtainable Market / Mercado Alvo Prático):** O grupo mais realista e focado de clientes iniciais que a sua empresa pretende conquistar e atender no curto prazo (nossos clientes ideais do dia a dia).

<a id="tam"></a>
### TAM

**TAM (Total Addressable Market / Mercado Total Disponível):** O tamanho do universo total de faturamento que a sua empresa conseguiria alcançar se vendesse o seu produto para absolutamente todo mundo do planeta que possui aquela dificuldade.

</details>

<details>
  <summary> Clique para expandir o glossário 🧰 CONCEITOS TÉCNICOS & INTERFACE & ENGENHARIA DE IA</summary>

<a id="agente"></a>
### Agente de IA

Agente de IA (AI Agent) | (A Tecnologia): É um sistema inteligente de computador (o cérebro que roda dentro dessa aplicação). É o que diferencia o seu sistema de um site comum. Não apenas responde a comandos de texto simples (como um chat tradicional), mas tem a capacidade de agir de forma autônoma, analisar dados, calcular fusos horários, organizar caixas de entrada, tomar decisões lógicas e executar tarefas completas sozinho para atingir um objetivo específico. Ele funciona como um "funcionário virtual" focado em uma função. O Agentex atua como um Agente porque analisa o e-mail recebido, identifica o fuso horário do país de origem, calcula o horário comercial de destino e toma a decisão autônoma de organizar aquela mensagem na caixinha de prioridade visual correta, além de disparar respostas multilíngues em momentos de contingência.


<a id="api"></a>
### API

**API (Application Programming Interface / Interface de Programação de Aplicações):** Espécie de ponte ou canal de comunicação seguro que permite que dois sistemas totalmente diferentes "conversem" entre si e troquem informações automaticamente (como o AGENTEX se conectando diretamente com a sua caixa de entrada real do Gmail ou Outlook).

<a id="aplicação"></a>
### Aplicação

**Aplicação / Aplicativo (App) | (O Formato):** É a base de tudo. Nome técnico dado a qualquer programa, software ou sistema de computador que foi construído para realizar uma tarefa prática útil para o usuário (como organizar e-mails, calcular rotas ou processar pagamentos). No contexto de internet, quando dizemos "aplicação publicada", significa que o sistema saiu do computador do programador e já está "no ar" em um endereço de site acessível para qualquer pessoa usar. Aplicação Web, significa que o programa roda direto na internet através de um navegador (Chrome, Safari, etc.), sem que o usuário precise baixar e instalar um arquivo .exe ou .apk no computador ou celular.

<a id="backstage"></a>
### Backstage

**Backstage (Bastidores):** Toda a estrutura de processos manuais ou automações que acontecem por trás das cortinas do software para que o cliente receba o valor final, sem que ele precise ver a mecânica acontecendo.

<a id="beta"></a>
### Beta / Versão Beta

**Beta / Versão Beta:** É uma versão de testes de um software que já está funcional, mas é liberada antecipadamente para um grupo restrito de clientes reais. O objetivo é coletar opiniões e validar o uso prático antes do lançamento oficial no mercado.

<a id="chatgpt"></a>
### ChatGPT

**ChatGPT:** É um sistema de Inteligência Artificial em formato de chat (conversa) que consegue entender perguntas em texto e gerar respostas humanas, profissionais e completas de forma instantânea.

<a id="chaves"></a>
### Chaves de API

**Chaves de API (Tokens/Senhas de Integração):** Códigos secretos que funcionam como uma "chave digital" para permitir que um aplicativo acesse os recursos de outro de forma segura. Por segurança, elas nunca devem ficar visíveis ou expostas no código público do GitHub.

<a id="checkbox"></a>
### Checkbox / Checkboxes

**Checkbox / Checkboxes (Caixas de Seleção):** Pequenos quadradinhos interativos na tela que o usuário clica para marcar ou desmarcar opções, muito utilizados para fazer listas de tarefas (to-do lists) e dar "checks" visuais de conclusão.

<a id="checkout"></a>
### Checkout

**Checkout:** A tela ou página final onde o cliente insere os dados de pagamento (como cartão de crédito) para concluir uma compra ou assinatura. No AGENTEX, essa tela é fornecida de forma segura pelo próprio [Stripe](#stripe).

<a id="co-founder"></a>
### Co-Founder

**Co-Founder (Co-Fundador):** O parceiro de negócios que ajuda a fundar a empresa. Neste projeto, o [ChatGPT](#chatgpt) foi utilizado como um co-founder analítico para validar o mercado e desenhar a lógica das regras operacionais.

<a id="prompt"></a>
### Engenharia de Prompt

**Engenharia de Prompt:** A técnica especializada de planejar, estruturar e redigir comandos textuais ultra-detalhados e lógicos para que uma inteligência artificial construa um layout ou código sem erros e sem desperdiçar processamento.

<a id="keep"></a>
### Google Keep

**Google Keep:** Ferramenta de produtividade que usa o modelo de cartões colados lado a lado (estilo o método Kanban) como um mural de Post-its, facilitando a visualização da gestão de tarefas e ideias de forma organizada.

<a id="tarefas"></a>
### Google Tarefas

**Google Tarefas:** Ferramenta de produtividade que usa o modelo de tópicos de listas verticais que você vai riscando, embora em algumas visualizações integradas (como no Google Agenda ou no painel lateral do Gmail), também se comporte como uma caixinha de controle de status, facilitando o controle de tarefas.

<a id="landing"></a>
### Landing Page

**Landing Page** (Página de Destino): É uma página de internet criada com um único objetivo comercial muito específico: prender a atenção do visitante imediatamente, explicar a proposta de valor de forma clara e direta e levá-lo a tomar uma única ação importante, como preencher um formulário de cadastro ou clicar em um botão de compra. Ao contrário de um site tradicional, ela elimina distrações para transformar um visitante comum em um [lead](#lead) ou cliente pagante no menor tempo possível.

<a id="lovable"></a>
### Lovable

**Lovable:** é uma plataforma moderna de Inteligência Artificial que funciona como um "programador virtual", permitindo criar softwares e aplicativos inteiros sem precisar digitar códigos complexos. Na prática, o criador apenas escreve comandos simples em português — explicando o que o sistema deve fazer e como deve ser o visual — e a tecnologia gera instantaneamente as telas e funções automáticas de bastidores, reduzindo drasticamente o tempo e o custo de desenvolvimento de soluções como o Agentex.

<a id="cloud"></a>
### Lovable Cloud

**Lovable Cloud:** serviço de hospedagem e infraestrutura integrado do [Lovable](#lovable). 
Cria o banco de dados para salvar informações de forma segura, gerencia o cadastro e login dos usuários e garante que o sistema (como o Agentex) funcione 24 horas por dia, eliminando totalmente a necessidade inicial (possui limites no plano grátis) de contratar servidores externos ou especialistas em infraestrutura de TI.

<a id="markdown"></a>
### Markdown

**Markdown:** Método de formatação de texto extremamente simples e universal que utiliza símbolos básicos (como hashtags para títulos e asteriscos para negrito) para organizar e estruturar documentos e instruções textuais de forma limpa, garantindo que tanto humanos quanto inteligências artificiais consigam ler e entender a hierarquia das informações perfeitamente (organização visual e leitura eficiente).

<a id="mega"></a>
### Mega Prompt

**Mega Prompt (Supercomando):** É um comando textual ultra-detalhado, estruturado e extenso que reúne em um único bloco de texto o contexto do negócio, as regras lógicas de programação, o papel esperado da inteligência artificial e os limites do sistema. Ao contrário de um comando simples, o Mega Prompt funciona como um manual de instruções completo fornecido à IA (como o [ChatGPT](#chatgpt) ou o [Lovable](#lovable) para que ela execute tarefas complexas de ponta a ponta — como programar uma funcionalidade inteira do Agentex — com máxima precisão e sem margem para erros. 

<a id="n8n"></a>
### n8n

**n8n:** Ferramenta moderna de automação e integração de processos que funciona como um "maestro de sistemas", conectando aplicativos e criando fluxos de trabalho automáticos sem complicação.

<a id="no-code"></a>
### No-Code

**No-Code (Sem Código):** Ferramenta ou software de desenvolvimento que permite criar sistemas modernos (como o [Lovable](#lovable)), aplicativos inteiros e automações apenas por comandos de texto ou blocos visuais, sem precisar saber programar ou escrever linhas de código de computador.

<a id="paywall"></a>
### Paywall

**Paywall:** Uma "parede de pagamento" ou trava digital que bloqueia o acesso a um recurso exclusivo. O usuário só consegue visualizar ou usar aquela funcionalidade (como o Modo Zerar Caixa de Entrada) depois que realizar o pagamento ou upgrade do plano.

<a id="pop-up"></a>
### Pop-up

**Pop-up:** Elemento de interface visual que surge subitamente centralizado na frente da tela principal do site após um clique para prender a atenção do usuário, borrando e escurecendo de leve o fundo da página. Costuma ser uma caixinha utilizada para exibir avisos urgentes, mensagens de [contingência](#contingência), formulários elegantes ou conteúdos complementares importantes sem tirar o usuário da página atual.

<a id="resend"></a>
### Resend

**Resend:** É um serviço moderno de internet especializado em disparar e-mails automáticos direto de dentro de aplicativos e sistemas. Ele funciona como o "carteiro virtual" do software, garantindo que mensagens de alerta (como avisos de que um novo cliente se cadastrou) cheguem de forma instantânea e sem cair na caixa de spam.

<a id="spa"></a>
### SPA

**SPA (Single Page Application / Aplicação de Página Única):** Formato de site moderno onde tudo roda em uma única tela dinâmica. Conforme o usuário clica nos botões, os elementos aparecem e desaparecem, mudando de forma fluida e limpa, sem que a página precise ficar recarregando inteira, eliminando a lentidão.

<a id="stripe"></a>
### Stripe

**Stripe:** Uma das plataformas de pagamentos e cobranças digitais mais seguras do mundo. Funciona como a "maquininha de cartão invisível" do seu site, permitindo que a empresa receba pagamentos por cartão de crédito ou assinaturas recorrentes de forma automatizada e protegida.

<a id="css"></a>
### Tailwind CSS

**Tailwind CSS:** Manual de componente de estilos modernos que a inteligência artificial usa para desenhar (caixas, botões e cores), pintar e estruturar as telas de forma rápida e padronizada. Funciona como um catálogo pronto de formatações visuais (bordas, sombras e espaçamentos), deixando o site bonito e profissional sem peso de carregamento.

<a id="tipografia"></a>
### Tipografia

**Tipografia:** A escolha e o desenho das fontes (letras) utilizadas nas telas. Uma boa tipografia corporativa garante que dados numéricos e horários internacionais fiquem perfeitamente nítidos e fáceis de ler por qualquer pessoa.

<a id="ui"></a>
### UI

**UI (User Interface / Interface do Usuário):** Cuida de toda a parte visual do software, definindo elementos como as cores, as fontes, os botões e o layout das caixinhas com os quais o cliente interage na tela.

<a id="ux"></a>
### UX

**UX (User Experience / Experiência do Usuário):** Planeja como o usuário se sente ao navegar pelo sistema, mapeando a jornada do cliente para garantir que o software seja fácil, lógico, intuitivo e totalmente sem complicações.
</details>
---


