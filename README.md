# 📘 Miniguia de Estudos com NotebookLM: Benjamin Graham e os Fundamentos do Value Investing

Projeto desenvolvido para o Desafio de Projeto da DIO: **"Explorando o NotebookLM como Ferramenta de Aprendizagem Ativa"**.

O objetivo deste repositório é documentar todo o processo de construção de um Caderno Temático no NotebookLM — da escolha do assunto e curadoria de fontes até a engenharia de prompts e a entrega final de um miniguia de estudo reutilizável.

---

## 1. Contexto e Objetivos

### Por que Benjamin Graham?

Escolhi estudar **Benjamin Graham (1894–1976)**, considerado o "pai do value investing" (investimento em valor) e autor de *Security Analysis* (1934, com David Dodd) e *The Intelligent Investor* (1949). Graham foi professor na Columbia Business School e mentor de Warren Buffett, tendo desenvolvido conceitos que até hoje sustentam a análise fundamentalista de investimentos.

O tema tem relação direta com meus estudos em **Ciências Contábeis**, já que os métodos de Graham partem da leitura de demonstrações financeiras (balanço patrimonial, DRE) para estimar o valor intrínseco de uma empresa — conectando teoria contábil e prática de mercado. A escolha também foi motivada por uma aula do **prof. Felipe Aguiar**, que usou Benjamin Graham como exemplo.

### Objetivos de estudo

- Compreender os **princípios centrais** do value investing: valor intrínseco e margem de segurança.
- Entender **os critérios quantitativos de Graham** (os 7 critérios do investidor defensivo, o Graham Number e a estratégia NCAV) para tomar decisões de investimento, relacionando com o que estudo em Contabilidade (leitura de balanço patrimonial e DRE).
- Construir um **vocabulário técnico** (glossário) sobre análise de investimentos.
- Testar o NotebookLM como ferramenta de **aprendizagem ativa**, avaliando seus limites e seus pontos fortes na síntese de fontes longas.
- Produzir um **material de revisão reutilizável** para consultas futuras (ex.: antes de estudar ações, fundos ou provas relacionadas a finanças/contabilidade).

---

## 2. Curadoria de Fontes

Para este Caderno Temático, fui além do mínimo pedido (3 a 5 fontes) e reuni um conjunto mais amplo de fontes abertas — artigos, verbetes da Wikipédia e vídeos — cobrindo desde a biografia de Graham até seus critérios práticos de seleção de ações. Parte delas foi carregada diretamente no NotebookLM; outra parte foi gerada pelo próprio Deep Research da ferramenta, a partir de buscas sobre os temas abaixo.

**Biografia e visão geral**

| Fonte | Tipo | Link |
|---|---|---|
| Benjamin Graham | Verbete (Wikipédia) | https://en.wikipedia.org/wiki/Benjamin_Graham |
| Intelligent Investor Benjamin Graham | Artigo/resumo | *fonte gerada pelo Deep Research do NotebookLM* |
| O Investidor Inteligente: entenda a obra de Benjamin Graham | Artigo (pt-BR) | https://www.suno.com.br/artigos/o-investidor-inteligente-entenda-a-obra-de-benjamin-graham/ |
| Um portal para aprender tudo sobre o mercado | Artigo (pt-BR) | https://content.btgpactual.com/blog/investimentos/5-ensinamentos-do-investidor-benjamin-graham |

**Critérios e método de seleção de ações (7 critérios de Graham)**

| Fonte | Tipo | Link |
|---|---|---|
| Benjamin Graham's 7 Criteria for Picking Value Stocks | Artigo | https://www.cabotwealth.com/daily/value-stocks/benjamin-grahams-value-stock-criteria |
| Benjamin Graham's 7 criteria to select value stocks | Artigo | https://www.winvesta.in/blog/investors/benjamin-grahams-7-ways-to-select-high-value-stocks |
| Benjamin Graham's Basic Tenets for Being a Successful Investor | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Benjamin Graham's Investment Method: Meaning | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Explained: Benjamin Graham's 7 Stock Criteria | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| O Método de Benjamin Graham para Ações de Valor | Artigo | https://www.ivalor.com.br/aprenda/o-metodo-de-benjamin-graham-para-acoes-de-valor/ |
| O Investidor Inteligente Benjamin Graham Audiobook | Vídeo (pt-BR) | https://www.youtube.com/watch?v=fMo_xntieUo |

**Conceitos técnicos (Wikipédia)**

| Fonte | Tipo | Link |
|---|---|---|
| Graham number - Wikipedia | Verbete (Wikipédia) | https://en.wikipedia.org/wiki/Graham_number |
| Net current asset value - Wikipedia | Verbete (Wikipédia) | https://en.wikipedia.org/wiki/Net_current_asset_value |
| Security Analysis (book) - Wikipedia | Verbete (Wikipédia) | https://en.wikipedia.org/wiki/Security_Analysis_(book) |
| The Graham Number: A Classic Tool for Value Investing | Artigo | https://www.investing.com/academy/analysis/what-is-the-graham-number/ |
| Mastering Net Net Working Capital (NNWC) & Net-Net investing | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Why and how to implement a net-net investment strategy | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |

**Aplicação prática e cálculo do valor intrínseco**

| Fonte | Tipo | Link |
|---|---|---|
| Como calcular o valor intrínseco de uma ação | Vídeo (pt-BR) | https://www.youtube.com/watch?v=gxjG5seS4KE |
| O Valor das Ações pela lógica da Fórmula de Benjamin Graham | Vídeo (pt-BR) | https://www.youtube.com/watch?v=ap8XmWadSss |
| How to Use the Graham Number to Value Stocks | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Relatório do Deep Research: Metodologia de Investimento | Relatório | *fonte gerada pelo Deep Research do NotebookLM* |
| Defensive Investors: Rules from the Classic Book | Artigo/trecho | *fonte gerada pelo Deep Research do NotebookLM* |
| Intelligent Investor: Stock Selection for the Defensive Investor | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| The Enterprising Investor - The Intelligent Investor | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |

**Contexto, herança e outras obras**

| Fonte | Tipo | Link |
|---|---|---|
| Estratégias sistemáticas: Benjamin Graham, muito mais que um investidor inteligente | Texto de orientação | https://www.constanciainvest.com.br/noticias/estrategias-sistematicas-benjamin-graham-muito-mais-que-um-investidor-inteligente/ |
| Graham's Disciples: Value Investing - Wiley/Montier | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Security Analysis & The Intelligent Investor - Wyckoff | Artigo | *fonte gerada pelo Deep Research do NotebookLM* |
| Security Analysis By Benjamin Graham | Resumo/PDF | *fonte gerada pelo Deep Research do NotebookLM* |
| The Intelligent Investor Book Summary - You Exec | Resumo | *fonte gerada pelo Deep Research do NotebookLM* |
| Comporte-se como um segundo cérebro baseado... | Texto de orientação | *fonte carregada no NotebookLM de minha autoria* |

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Como as fontes carregadas são majoritariamente **práticas e quantitativas** (critérios de seleção, fórmulas, estratégias de valuation), os prompts foram direcionados para extrair método e cálculo, não só biografia. Aqui documento os testes, o raciocínio por trás deles e as dificuldades encontradas.

### 3.1 Prompt exploratório inicial

**Prompt:**
> "Com base nas fontes carregadas, quais são os 7 critérios de Benjamin Graham para selecionar ações de valor? Liste em ordem, com uma frase explicando cada um."

**Resultado:** boa resposta, mas as diferentes fontes (Cabot Wealth, Winvesta e as demais sobre os critérios) numeram e descrevem os 7 critérios com pequenas variações — o NotebookLM juntou tudo em uma lista só, sem indicar que havia divergência entre as fontes.

**Ajuste (v2):**
> "Compare como cada fonte descreve os 7 critérios de Graham. Existem diferenças na ordem, nos limites numéricos (ex: dívida, current ratio) ou na forma de calcular? Aponte por fonte."

**Aprendizado:** quando o tema tem **variações numéricas entre fontes** (ex: um artigo diz P/B < 1,5 e outro ajusta para inflação), é essencial pedir explicitamente uma comparação "fonte a fonte" — senão o modelo tende a apresentar uma média ou só a versão mais citada, escondendo a divergência.

### 3.2 Prompt sobre a fórmula do Graham Number

**Prompt:**
> "Explique o que é o Graham Number, mostre a fórmula e resolva um exemplo numérico simples."

**Dificuldade encontrada:** na primeira resposta, o NotebookLM explicou o conceito corretamente mas **não completou o exemplo numérico**, cortando o cálculo pela metade.

**Ajuste (v2):**
> "Refaça o exemplo do Graham Number até o fim: mostre o LPA (lucro por ação), o VPA (valor patrimonial por ação), a substituição na fórmula √(22,5 × LPA × VPA) e o resultado final em número."

**Aprendizado:** para cálculos passo a passo, é melhor **pedir explicitamente cada etapa numérica** (fórmula → substituição → resultado) em vez de só "resolva um exemplo" — assim o modelo não pula etapas.

### 3.3 Prompt sobre a estratégia Net Current Asset Value (NCAV)

**Prompt:**
> "O que é a estratégia NCAV (net-net) de Graham e qual sua importância prática para um investidor iniciante hoje?"

**Resultado:** resposta consistente, citando corretamente o verbete da Wikipédia sobre Net Current Asset Value e o artigo de Mastering NNWC.

**Dificuldade encontrada:** quando pedi "quais ações brasileiras se encaixam na estratégia NCAV hoje", o NotebookLM **recusou-se a extrapolar** além das fontes carregadas (nenhuma delas cita ações da B3), respondendo que não tinha essa informação nas fontes.

**Aprendizado / cicatriz:** o NotebookLM é ótimo para sintetizar e citar fontes fornecidas, mas **não deve ser usado para gerar informação nova não presente nelas** — para aplicações práticas atuais (ex: screening de ações no mercado brasileiro), é preciso complementar com outra ferramenta (ex: um screener de ações) ou fonte adicional.

### 3.4 Prompt de teste de precisão (fact-checking)

**Prompt:**
> "Qual é a diferença entre 'investidor defensivo' e 'investidor empreendedor' segundo as fontes carregadas? Cite de qual fonte vem cada definição."

**Resultado:** resposta correta e bem distinguida, com citação cruzada entre o material sobre "Defensive Investors" e "The Enterprising Investor".

**Aprendizado:** perguntas de definição/contraste ("diferença entre X e Y") com resposta verificável em múltiplas fontes são um bom "teste de confiança" antes de usar o NotebookLM para perguntas mais interpretativas ou de aplicação.

---

## 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumo estruturado

**Quem foi Benjamin Graham**
Financista, economista e professor nascido em Londres em 1894 e radicado nos EUA. Lecionou na Columbia Business School, onde desenvolveu, com David Dodd, os fundamentos da análise de valor mobiliário (*Security Analysis*, 1934) e, depois, popularizou o tema para o público geral em *The Intelligent Investor* (1949). É considerado o "pai do value investing" e mentor de Warren Buffett.

**Os 7 critérios de Graham para o investidor defensivo**

Segundo as fontes carregadas, Graham propôs um filtro quantitativo para selecionar ações de empresas sólidas e baratas:

1. **Tamanho adequado da empresa:** vendas anuais mínimas, para garantir resiliência em crises.
2. **Boa liquidez financeira:** current ratio (ativo circulante ÷ passivo circulante) acima de 1,5–2.
3. **Estabilidade de lucros:** lucro positivo em todos os últimos 10 anos.
4. **Histórico de dividendos:** pagamento ininterrupto de dividendos por um longo período.
5. **Crescimento de lucros:** crescimento mínimo de lucro por ação ao longo de uma década.
6. **Preço/Lucro (P/L) moderado:** normalmente abaixo de 15x.
7. **Preço/Valor Patrimonial (P/VPA) moderado:** normalmente abaixo de 1,5x — e o produto P/L × P/VPA não deve ultrapassar 22,5.

> As fontes divergem um pouco nos valores exatos (ex: ajuste pela inflação), por isso o miniguia trata esses números como **faixas de referência**, não regras rígidas — ver seção 3.1.

**Ferramentas de valuation derivadas dos critérios**

- **Graham Number (Número de Graham):** fórmula que estima o preço máximo "seguro" para um investidor defensivo pagar por uma ação:
  `Graham Number = √(22,5 × LPA × VPA)`
  onde LPA = lucro por ação e VPA = valor patrimonial por ação. Se o preço de mercado estiver abaixo desse número, a ação pode ter margem de segurança.
- **NCAV / estratégia "net-net":** compara o valor de liquidação de curto prazo da empresa (ativo circulante − passivo total) com seu valor de mercado. Se o NCAV for maior que o valor de mercado, a ação é considerada muito descontada — a chamada estratégia de "cigar-butt investing".

**Princípios centrais da filosofia de Graham**

1. **Valor intrínseco:** toda ação tem um valor "justo", baseado em ativos, lucros, dividendos e perspectivas da empresa — que pode ser diferente do preço de mercado.
2. **Margem de segurança:** comprar um ativo por um preço bem abaixo do seu valor intrínseco (ou do Graham Number), criando uma "almofada" contra erros de análise.
3. **Investidor defensivo vs. investidor empreendedor:** o defensivo busca segurança e simplicidade com baixo envolvimento; o empreendedor está disposto a dedicar mais tempo e análise em busca de retornos acima da média.
4. **Investimento vs. especulação:** investir exige análise fundamentada e segurança do principal; especular é apostar em movimentos de preço sem essa base.

### 4.2 Glossário

| Termo | Definição |
|---|---|
| **Value Investing** | Estratégia de investimento baseada em comprar ativos abaixo do seu valor intrínseco. |
| **Valor intrínseco** | Valor "real" de uma empresa, estimado a partir de seus fundamentos (ativos, lucros, dividendos), independente do preço de mercado. |
| **Margem de segurança** | Diferença entre o valor intrínseco estimado (ou o Graham Number) e o preço pago, usada como proteção contra erros de análise. |
| **Graham Number** | Fórmula `√(22,5 × LPA × VPA)` que estima o preço máximo que um investidor defensivo deveria pagar por uma ação. |
| **NCAV (Net Current Asset Value)** | Ativo circulante menos passivo total; usado para achar ações negociadas abaixo do seu valor de liquidação de curto prazo. |
| **Current Ratio** | Ativo circulante dividido pelo passivo circulante; mede a liquidez de curto prazo de uma empresa. |
| **P/L (Preço/Lucro)** | Preço da ação dividido pelo lucro por ação; um dos filtros dos 7 critérios de Graham. |
| **P/VPA (Preço/Valor Patrimonial)** | Preço da ação dividido pelo valor patrimonial por ação; outro filtro dos 7 critérios. |
| **Análise fundamentalista** | Método de avaliação de investimentos baseado em demonstrações financeiras e dados econômicos da empresa. |
| **Especulação** | Operação baseada em previsão de movimento de preços, sem análise profunda do valor do ativo. |
| **Investidor defensivo** | Perfil de investidor descrito por Graham que busca segurança e simplicidade, com baixo envolvimento ativo. |
| **Investidor empreendedor** | Perfil de investidor descrito por Graham disposto a dedicar tempo e esforço extra para buscar retornos acima da média. |

### 4.3 Prompts reutilizáveis para revisão futura

```
1. "Com base nas fontes carregadas, faça um resumo de [conceito] em até 5 frases,
   citando de qual fonte cada informação vem."

2. "Explique [conceito técnico] como se eu estivesse aprendendo pela primeira vez,
   evite jargão sem explicação e use uma analogia do dia a dia."

3. "Cruze as informações de todas as fontes sobre [assunto] e aponte se há
   divergências ou complementos entre elas."

4. "Crie 5 perguntas de múltipla escolha sobre [tema] com base apenas nas fontes
   carregadas, indicando a resposta correta e a fonte."

5. "Monte uma linha do tempo dos principais eventos/conceitos relacionados a
   [tema], citando a fonte de cada item."

6. "Resuma [tema] em formato de flashcards: pergunta de um lado, resposta do outro,
   baseado apenas no conteúdo das fontes."
```

---

## 5. Ferramentas utilizadas

- [NotebookLM](https://notebooklm.google.com/) — criação do caderno temático e testes de prompt.
- Fontes abertas listadas na seção 2.
- GitHub — versionamento e publicação do material.

---

## 6. Considerações finais

Este projeto mostrou que o NotebookLM é uma ferramenta forte para **síntese fiel a fontes fornecidas** e **citação rastreável**, mas exige prompts bem construídos para não gerar respostas rasas — e não deve ser usado para extrapolar além do material carregado. A combinação de uma curadoria cuidadosa de fontes com prompts iterativos foi o que mais elevou a qualidade das respostas.
