# 📊 Roadmap Smart Investing

Caderno Temático construído no **NotebookLM** sobre **investimentos para iniciantes**, desenvolvido como parte do Bootcamp DIO/Santander. O projeto une curadoria de fontes, engenharia de prompts e organização do conhecimento para criar um material de estudo reutilizável.

🔗 **Notebook original:** [Investing for Beginners — NotebookLM](https://notebook.google.com/notebook/2c4a617c-8b53-49d0-a7df-2a859b5561c0)

---

## 🎯 Contexto e Objetivos

### Assunto escolhido
Investimentos financeiros para iniciantes, com foco em duas frentes complementares:
- Os fundamentos práticos de **renda fixa vs. renda variável**, segurança (FGC), liquidez e prazos.
- A filosofia de **investimento passivo de longo prazo** de John C. Bogle (fundos de índice, diversificação, custos e juros compostos).

### Perfil do estudo
- Estudante universitário, 22 anos
- Aporte mensal disponível: R$ 1.000,00
- Perfil de risco: conservador no início da jornada

### Objetivos de estudo
- Entender a diferença entre renda fixa e renda variável e quando cada uma faz sentido.
- Perder o medo de termos técnicos e do funcionamento das plataformas de investimento.
- Construir um roteiro prático e realista para começar a investir sem travar em decisões que, no início, não são as mais importantes (como "qual a melhor plataforma").
- Aprender a filosofia de Bogle como base para decisões de longo prazo.

---

## 🏆 Resultados Obtidos

A partir das fontes carregadas no NotebookLM, foi construído um **planejamento de investimentos totalmente personalizado**, elaborado com base no perfil real do investidor (22 anos, estudante, aporte mensal de R$ 1.000,00, perfil conservador). O plano inclui:

- Comparativo de 3 plataformas de investimento para iniciantes (vantagens, desvantagens e indicação de uso de cada uma).
- Explicação simplificada das categorias de investimento (Renda Fixa e Renda Variável), com seus respectivos produtos, garantias e regras de resgate.
- Um roteiro prático de alocação de capital dividido em 4 fases ao longo de 12 meses, desde a familiarização com as plataformas até a formação de uma reserva de emergência e a introdução gradual à renda variável via ETFs.
- Um resumo final consolidando cada recomendação, sua justificativa financeira e a fonte específica em que se baseia.

Esse plano foi transformado em três materiais concretos, disponíveis na pasta [`Results/`](./Results):

- **Mapa mental** (`Mapa-mental-investimentos.png`) — visão geral estruturada de todos os conceitos abordados no caderno temático (categorias de investimento, filosofia de Bogle, perfis de investidor, fatores estratégicos e passos práticos).
- **Apresentação de slides** (`Plano-investimentos.pptx`) — versão resumida e visual do plano de ação em formato de apresentação.
- **Relatório em PDF** (`Plano-investimentos-detalhado.pdf`) — versão final e mais completa do plano, com tabelas comparativas de plataformas e categorias de investimento, o roteiro de 12 meses, e uma simulação gráfica projetando a evolução do patrimônio (Poupança vs. Conta Digital/CDI) mês a mês ao longo de um ano.

---

## 📚 Curadoria de Fontes

Foram selecionadas e carregadas no NotebookLM fontes abertas em texto, PDF e vídeo. O detalhamento completo de cada uma (com explicação do motivo da escolha) está disponível em [`Sources/fontes.pdf`](./Sources/fontes.pdf).

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | Coursera Help Center — "O que é o Coursera?" | Artigo (texto) | [link](https://learner.coursera.help/hc/articles/209818553) |
| 2 | "AULA COMPLETA para INICIANTES que NÃO SABEM POR ONDE COMEÇAR a INVESTIR" — Primo Pobre | Vídeo (YouTube) | [link](https://www.youtube.com/watch?v=Q6x0xnI0uCg) |
| 3 | Vídeo complementar do canal Primo Pobre | Vídeo (YouTube) | [link](https://www.youtube.com/watch?v=u-dGopzxDXM) |
| 4 | *O Investidor de Bom Senso* — John C. Bogle | Livro (Google Books) | [link](https://books.google.com/books/about/O_investidor_de_bom_senso.html?id=Ll_wDwAAQBAJ) |
| 5 | *O Pequeno Livro do Investimento de Bom Senso* — resenha | Artigo (texto) | [link](https://www.investidorfrugal.com/o-pequeno-livro-do-investimento/#content) |

> **Nota:** os itens 2 e 3 são vídeos do YouTube, usados como fontes primárias práticas dentro do NotebookLM. Como o desafio pede fontes em texto/PDF, os itens 1, 4 e 5 atendem diretamente esse critério — os vídeos foram mantidos como material complementar por terem fundamentado boa parte das recomendações práticas do miniguia.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Documentação do processo de interação com a IA dentro do NotebookLM: os prompts elaborados, o raciocínio por trás deles, e as dificuldades encontradas no caminho.

### Prompt 1 — Instruções iniciais de investimento
```
Objetivo: Eu quero aprender a investir. Lhe mandei algumas fontes confiáveis e até
um curso que eu to fazendo, um livro que eu li e uma pessoa que eu acredito que
combine com uma pessoa que está começando a investir pra que vc me de instruções
de como eu posso fazer pra começar a investir.

O que me complica hoje - Eu fico na dúvida de coisas que eu acredito que não
sejam tão importantes pra quem ta começando como se preocupar com a plataforma
que estou começando e tal, só por não ter um norte.
```
**Resultado:** a IA devolveu um roteiro em 4 etapas (começar pela renda fixa, definir prazos/liquidez, entender a mentalidade de longo prazo de Bogle, e a "regra de ouro" de nunca investir no que não se entende), com base direta nas fontes carregadas.
**Referências usadas pela IA:** canal Primo Pobre e livro de John Bogle.

### Prompt 2 — Glossário de termos técnicos
```
Antes de tudo isso, queria que vc fizesse um resumo estruturado de termos
técnicos que aparecem nas fontes que eu lhe mandei e que podem dificultar o
entendimento de uma pessoa que não entende do assunto. Ao fazer, quero que vc
deixe ao lado o seu respectivo nome em inglês (termo/termo em ingles, seguido
da expicação)
```
**Raciocínio:** antes de pedir recomendações práticas, era necessário nivelar o vocabulário técnico, já que termos como "liquidez diária" ou "FGC" não são intuitivos para quem nunca investiu.
**Resultado:** lista estruturada com mais de 15 termos técnicos, cada um com nome em português, tradução em inglês e explicação — usada como base direta para o glossário deste miniguia (seção abaixo).

### Prompt 3 — Renda fixa vs. variável: existe contradição entre as fontes?
```
Agora, baseado nas minhas fontes, me diga como elas recomendam que eu comece
os meus investimentos, por renda fixa ou variada, isso depende do tipo de
pessoa que eu sou / da minha situação atual? As fontes se contradizem? Qual
fonte diz o que e qual o motivo que ela relata para ter essa resposta?
```
**Raciocínio:** um prompt de checagem crítica — em vez de aceitar a recomendação anterior sem questionar, o objetivo foi confrontar as duas fontes principais (Primo Pobre e Bogle) para entender se havia divergência real ou apenas foco em momentos diferentes da jornada do investidor.
**Resultado:** a IA identificou que as fontes **não se contradizem**, mas se complementam — o Primo Pobre foca no início absoluto (100% renda fixa), enquanto Bogle foca na construção de patrimônio de longo prazo usando uma regra de alocação por idade (110 − idade = % em renda variável).

### Prompt 4 — Plano de ação personalizado
Prompt mais longo e estruturado, fornecendo contexto pessoal (idade, aporte mensal, perfil de risco, nível de conhecimento) e pedindo explicitamente: tabela comparativa de 3 plataformas no início, e um resumo final com recomendação + justificativa + fonte.
**Raciocínio:** esse foi o prompt mais elaborado do processo — em vez de pedir uma resposta genérica, foram especificados o formato de saída (tabela + resumo final) e os critérios de avaliação, técnica de **prompt estruturado com entregáveis explícitos**.
**Resultado:** plano de ação completo dividido em fases mensais (Mês 1 → Ano 2), com tabela de plataformas e quadro final de recomendação + justificativa + fonte.

### Prompt 5 — Geração de slides
```
Ainda não, quero que vc monte slides apresentando esse plano de investimentos
que vc montou pra mim
```
**Resultado:** geração da apresentação de slides consolidando o plano de investimentos dentro do Studio do NotebookLM.

**Ajuste feito:** em seguida, o prompt pediu um formato complementar ao já gerado:
```
Além da apresentação de slides, quero que vc gere também um pdf que tenha
relatórios e tabela de dados dentro dele, ele não precisa ser muito grande,
apenas bem explicado.
```
**Raciocínio:** ter o mesmo conteúdo em dois formatos diferentes (slides + relatório em PDF) permite usos distintos — a apresentação como visão resumida e visual, e o PDF como material de consulta mais detalhado, com tabelas e simulação numérica.
**Resultado:** o PDF `plano-investimentos-bom-senso.pdf` foi gerado com sucesso, incluindo tabelas comparativas e uma simulação gráfica de poupança vs. conta digital.

### Prompt 6 — Simulações numéricas de acompanhamento
```
Simule para mim 1 ano na poupança vs conta digital
O que acontece se eu precisar do dinheiro antes do CDB vencer?
```
**Raciocínio:** prompts de aprofundamento para validar números concretos (a simulação já constava no PDF gerado) e entender um risco prático específico (resgate antecipado de CDB), fechando pontas em aberto do plano.

---

## 📘 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado

**1. As duas classes de investimento**
- **Renda Fixa:** você empresta dinheiro (a um banco, ao governo ou ao setor imobiliário/agro) e já conhece as regras de rendimento antecipadamente. Exemplos: CDB, Tesouro Direto, LCI/LCA. Ideal para quem busca segurança e para a reserva de emergência.
- **Renda Variável:** a rentabilidade oscila e não há garantias. Exemplos: ações, fundos imobiliários (FIIs), ETFs. Maior potencial de ganho, maior risco — exige tempo de maturação e mais conhecimento.

**2. Proteção e segurança**
O **FGC (Fundo Garantidor de Crédito)** cobre até R$ 250 mil por instituição em caso de quebra do banco/corretora, para produtos como poupança, contas digitais, CDBs e LCIs. A renda variável **não** possui essa proteção.

**3. Prazo e liquidez definem onde investir**
- Dinheiro que pode ser necessário a qualquer momento → produtos com **liquidez diária** (contas digitais, Tesouro Selic).
- Dinheiro com data definida para uso → pode ir para produtos de **prazo fechado**, que rendem mais, mas penalizam o resgate antecipado.

**4. A filosofia Bogle para o longo prazo**
Em vez de tentar "acertar" ações individuais (o que as fontes comparam a "procurar uma agulha no palheiro"), Bogle defende comprar **fundos de índice de baixo custo**, que replicam o mercado inteiro de forma diversificada e passiva. A regra prática de alocação sugerida é: **110 (ou 120) − sua idade = % em renda variável**, com o restante em renda fixa.

**5. Roteiro prático em 4 fases (para o perfil estudado: 22 anos, R$1.000/mês, conservador)**
| Fase | Ação | Objetivo |
|------|------|----------|
| Mês 1 | Abrir conta em 2 plataformas gratuitas, sem investir ainda | Familiarização com a interface |
| Meses 2–6 | 100% do aporte em renda fixa com liquidez diária | Formar reserva de emergência de R$ 5.000 |
| Meses 7–12 | Dividir aporte entre liquidez diária e prazo fechado | Aumentar rentabilidade com segurança |
| Ano 2+ | Iniciar pequenos aportes (5–10%) em ETF de índice global | Introdução gradual à renda variável |

**6. A regra de ouro**
Nunca investir em algo que você não entende como funciona — o maior erro do iniciante é o desespero por ganhos rápidos.

---

### Glossário

| Termo (PT) | Termo (EN) | Explicação |
|---|---|---|
| Renda Fixa | Fixed Income | Investimento com regras de rendimento conhecidas previamente. |
| Renda Variável | Variable Income | Investimento cuja rentabilidade oscila e não é garantida. |
| Rentabilidade (ou Retorno) | Yield (or Return) | Ganho (ou perda) obtido sobre o valor investido, geralmente em percentual. |
| Liquidez Diária | Daily Liquidity | Capacidade de resgatar o dinheiro a qualquer momento sem perdas. |
| Diversificação | Diversification | Distribuir o dinheiro em diferentes ativos para reduzir risco. |
| Fundo Garantidor de Crédito (FGC) | Credit Guaranty Fund | Seguro que devolve até R$ 250 mil por instituição em caso de quebra do banco. |
| CDB | Certificate of Deposit (CD) | Título de renda fixa em que você empresta dinheiro a um banco. |
| LCI | Real Estate Credit Note | Título de renda fixa isento de IR, ligado ao financiamento imobiliário. |
| Ações | Stocks (or Shares) | Frações do capital social de uma empresa. |
| Fundos de Índice | Index Funds | Fundos que replicam passivamente um índice de mercado amplo. |
| Fundos de Investimento (Ativos) | Active Mutual Funds | Fundos geridos ativamente por profissionais, com taxas mais altas. |
| ETFs | Exchange Traded Funds | Fundos de índice negociados em bolsa como ações. |
| Custos de Intermediação | Intermediation Costs (Friction Costs) | Conjunto de taxas e impostos que corroem a rentabilidade de longo prazo. |
| Taxa de Administração | Management Fee | Percentual anual cobrado sobre o patrimônio do fundo. |
| Juros Compostos | Compound Interest | Crescimento exponencial do capital via reinvestimento dos rendimentos. |
| Market Timing | Market Timing | Tentativa de prever o momento ideal de compra/venda no mercado. |
| Reversão à Média | Regression to the Mean | Tendência de fundos com retorno extraordinário voltarem à média com o tempo. |

---

### Prompts Reutilizáveis (para futuras revisões)

Modelos de prompt genéricos, prontos para reaplicar em qualquer notebook temático futuro:

```
1. Diagnóstico inicial
"Baseado nas fontes que te enviei, quero aprender sobre [TEMA]. Minha maior
dificuldade hoje é [DIFICULDADE ESPECÍFICA]. Me dê um norte prático de como
avançar, usando apenas o que está nas fontes que te passei."

2. Glossário técnico bilíngue
"Faça um resumo estruturado dos termos técnicos que aparecem nas fontes que
te enviei. Para cada termo, mostre: nome em português / nome em inglês,
seguido de uma explicação simples."

3. Checagem de contradições entre fontes
"As minhas fontes concordam ou se contradizem sobre [PERGUNTA CENTRAL]?
Detalhe o que cada fonte diz especificamente e o motivo/lógica por trás de
cada posição."

4. Plano de ação personalizado (com formato definido)
"Monte um plano de ação sobre [TEMA] considerando este contexto: [DADOS
PESSOAIS RELEVANTES]. No início, quero [FORMATO ESPECÍFICO, ex: tabela
comparativa]. No fim, quero um resumo com o que foi recomendado, por que, e
em qual fonte você se baseou."

5. Revisão futura rápida
"Baseado no que já discutimos sobre [TEMA], me dê um resumo rápido dos 3
pontos mais importantes que eu preciso lembrar antes de tomar uma decisão
sobre [SITUAÇÃO ATUAL]."
```

---

## 🗂️ Estrutura do Repositório

```
.
├── README.md              # Este arquivo — documentação completa do desafio
├── Sources/                # Fontes utilizadas no NotebookLM
│   └── fontes.pdf          # Curadoria detalhada das 5 fontes (links + explicações)
└── Results/                # Materiais gerados a partir do caderno temático
    ├── Mapa-mental-investimentos.png
    ├── Plano-investimentos.pptx
    └── Plano-investimentos-detalhado.pdf
```

---

## 🏁 Sobre o Desafio

Projeto desenvolvido como parte do **Bootcamp Santander via DIO (Digital Innovation One)**, no desafio "Construindo um Caderno Temático com NotebookLM".
