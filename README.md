# 🧠 People Analytics Second Brain com NotebookLM

Projeto desenvolvido durante o desafio **Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM**, da DIO.

A proposta foi desenvolver um caderno temático capaz de funcionar como um segundo cérebro especializado em People Analytics, reunindo fontes selecionadas e utilizando inteligência artificial para apoiar a aprendizagem e a tomada de decisões em gestão de pessoas.

## 🎯 Contexto e Objetivo

O People Analytics conecta gestão de pessoas, dados e tecnologia para apoiar decisões organizacionais baseadas em evidências.

O objetivo deste projeto foi utilizar o NotebookLM para construir uma base de conhecimento especializada em People Analytics, tendo Erik van Vulpen como principal referência conceitual.

## 🤖 Segundo Cérebro

O NotebookLM foi configurado a partir da seguinte orientação:

> Atue como um segundo cérebro especializado em People Analytics, tendo como principal referência os princípios e ensinamentos de Erik van Vulpen. Sua função é transformar dados e informações sobre pessoas em insights claros e aplicáveis, apoiando gestores na análise de indicadores, identificação de problemas, compreensão de tendências e tomada de decisões estratégicas em gestão de pessoas.

## 📚 Curadoria de Fontes

Para construir a base de conhecimento do NotebookLM, foram selecionadas fontes em vídeo e texto relacionadas a People Analytics, indicadores de RH e tomada de decisão orientada por dados.

A curadoria buscou combinar conteúdos introdutórios, aplicações práticas e materiais voltados à análise de indicadores e problemas organizacionais.

Erik van Vulpen foi utilizado como principal referência conceitual do projeto, complementado por conteúdos em português para ampliar a aplicação dos conceitos ao contexto de gestão de pessoas.

### 📄 Artigos

1. **What is HR Analytics? All You Need to Know to Get Started — Erik van Vulpen / AIHR**  
   Fonte utilizada como principal referência conceitual sobre HR Analytics e People Analytics.

2. **People Analytics no RH: como usar dados para decisões estratégicas — ADP**  
   Conteúdo sobre aplicação de dados e indicadores na gestão de pessoas.

3. **People Analytics — Observatório de Pessoal do Governo Federal**  
   Material institucional relacionado ao uso de dados para decisões baseadas em evidências.

4. **Guia de People Analytics: como usar dados e indicadores de RH — Alura**  
   Conteúdo sobre conceitos, indicadores, ferramentas e aplicação de People Analytics.

5. **People Analytics e People Data: o que são e como aplicar no RH — Senior**  
   Fonte complementar sobre utilização de dados de pessoas para geração de insights.

### 🎥 Vídeos

Foram selecionados cinco conteúdos em vídeo sobre os fundamentos e a aplicação de People Analytics, abordando temas como:

- conceitos e fundamentos de People Analytics;
- transformação do RH por meio de dados;
- utilização prática de indicadores;
- implementação de People Analytics nas organizações;
- tomada de decisão orientada por dados.

## 🧪 Engenharia de Prompts e Cicatrizes

Para avaliar se o NotebookLM realmente poderia funcionar como um segundo cérebro especializado em People Analytics, foram realizados testes com diferentes níveis de contexto e complexidade.

### Teste 1 — Pergunta ampla

**Prompt utilizado:**

> Quais são os principais indicadores de People Analytics?

**Resultado:**  
A resposta apresentou uma visão geral dos principais indicadores, organizando-os em categorias como recrutamento e seleção, retenção e clima organizacional, desempenho e desenvolvimento e impacto financeiro.

**Cicatriz / aprendizado:**  
Embora a resposta tenha sido correta e organizada, ela permaneceu predominantemente conceitual. Como o prompt não apresentava um problema de negócio ou objetivo específico, o Notebook retornou uma lista ampla de indicadores.

**Aprendizado:**  
Perguntas abertas são úteis para compreender conceitos, mas geram respostas menos direcionadas para a tomada de decisão.

---

### Teste 2 — Aplicação a um problema de turnover

**Prompt utilizado:**

> Considere uma empresa que apresenta aumento no turnover nos últimos seis meses. Com base nas fontes deste Notebook, quais indicadores de People Analytics deveriam ser analisados para investigar o problema? Explique o que cada indicador pode revelar e como eles podem apoiar a tomada de decisão.

**Resultado:**  
O Notebook passou a relacionar indicadores ao problema apresentado, sugerindo a análise de turnover precoce, desempenho e potencial, tempo desde a última promoção, absenteísmo, engajamento, rotatividade por gestor ou departamento e qualidade da contratação.

**Cicatriz / aprendizado:**  
A inclusão de contexto tornou a resposta mais analítica. O Notebook deixou de apenas listar métricas e passou a explicar como cada indicador poderia ajudar a investigar possíveis causas da rotatividade.

**Aprendizado:**  
Inserir contexto, problema e objetivo no prompt aumenta a aplicabilidade da resposta.

---

### Teste 3 — Investigação diagnóstica

**Prompt utilizado:**

> Atue como um consultor de People Analytics. Um gestor identificou aumento simultâneo de absenteísmo, turnover e queda na produtividade de uma equipe. Com base exclusivamente nas fontes deste Notebook, proponha um processo de investigação indicando: quais dados analisar, quais relações investigar, quais hipóteses podem ser levantadas e quais informações adicionais seriam necessárias antes de tomar uma decisão.

**Resultado:**  
A resposta foi estruturada em quatro etapas:

1. dados a serem analisados;
2. relações e correlações a investigar;
3. hipóteses possíveis;
4. informações adicionais necessárias antes da tomada de decisão.

O Notebook relacionou indicadores de absenteísmo, turnover, produtividade, desempenho, carreira, engajamento e liderança.

**Cicatriz / aprendizado:**  
Esse foi o prompt que produziu a resposta mais próxima do comportamento esperado para um segundo cérebro especializado.

**Aprendizado:**  
Combinar persona, contexto, problema, estrutura desejada e restrição às fontes torna a resposta mais profunda, organizada e aplicável.

---

### Evolução dos Prompts

| Teste | Estrutura do Prompt | Resultado |
|---|---|---|
| Teste 1 | Pergunta genérica | Resposta conceitual e abrangente |
| Teste 2 | Problema + contexto | Resposta mais diagnóstica |
| Teste 3 | Persona + problema + estrutura + fontes | Resposta estratégica e aplicável |

### Principal aprendizado

Durante os testes, ficou evidente que a qualidade da resposta está diretamente relacionada à qualidade do contexto fornecido no prompt.

Uma pergunta genérica é útil para compreender conceitos, enquanto um prompt estruturado permite utilizar o NotebookLM como ferramenta de apoio à investigação e à tomada de decisão.

## 📖 Miniguia de People Analytics

### O que é People Analytics?

People Analytics é uma abordagem que utiliza dados relacionados às pessoas para apoiar a compreensão de problemas organizacionais e a tomada de decisões em gestão de pessoas.

Mais do que simplesmente acompanhar indicadores de RH, a proposta é relacionar diferentes informações para compreender o que está acontecendo, investigar possíveis causas e apoiar decisões baseadas em evidências.

Uma forma de compreender essa lógica é:

**Problema → Dados → Indicadores → Relações → Hipóteses → Investigação → Decisão**

---

### Principais grupos de indicadores

Durante o estudo, os indicadores foram organizados em quatro grandes grupos:

| Área | Exemplos de Indicadores |
|---|---|
| Recrutamento e Seleção | Time to Hire, Cost per Hire, Quality of Hire |
| Retenção e Clima | Turnover, Early Turnover, Absenteísmo, eNPS |
| Desempenho e Desenvolvimento | Desempenho, potencial, treinamento e tempo desde a última promoção |
| Impacto no Negócio | Receita por colaborador, produtividade e custos de RH |

O principal aprendizado foi perceber que não é necessário acompanhar todos os indicadores ao mesmo tempo. A escolha das métricas deve estar relacionada ao problema que se deseja investigar.

---

### Da métrica à decisão

Um indicador isolado mostra apenas parte da situação.

Por exemplo, identificar que o turnover aumentou mostra **o que aconteceu**, mas não explica necessariamente **por que aconteceu**.

Para investigar o problema, outros dados podem ser relacionados, como:

- turnover precoce;
- absenteísmo;
- engajamento;
- desempenho;
- tempo desde a última promoção;
- qualidade da contratação;
- liderança;
- área ou departamento.

A análise conjunta desses indicadores permite formular hipóteses e investigar possíveis causas antes de propor uma ação.

---

### Exemplo prático

Imagine uma equipe que apresente simultaneamente:

**Aumento do absenteísmo + aumento do turnover + queda da produtividade**

Uma decisão baseada apenas em percepção poderia atribuir o problema imediatamente à falta de motivação ou à liderança.

Uma abordagem orientada por People Analytics procura primeiro investigar os dados.

Entre as informações que poderiam ser analisadas estão:

- histórico de absenteísmo;
- turnover voluntário e involuntário;
- produtividade;
- desempenho;
- tempo de empresa;
- tempo desde a última promoção;
- pesquisas de clima;
- engajamento;
- mudanças recentes de liderança.

A partir dessas informações, podem surgir hipóteses como:

- sobrecarga de trabalho;
- problemas de liderança;
- estagnação de carreira;
- desalinhamento na contratação;
- falhas no onboarding.

Essas hipóteses ainda precisam ser investigadas antes da tomada de decisão.

---

### Principal aprendizado do estudo

People Analytics não consiste apenas em acompanhar números.

Seu valor está em transformar dados em perguntas, relações e hipóteses que ajudem os gestores a compreender melhor os problemas relacionados às pessoas antes de tomar decisões.

---

## 📘 Glossário

| Termo | Significado |
|---|---|
| **People Analytics** | Uso estruturado de dados sobre pessoas para apoiar análises e decisões de gestão. |
| **KPI** | Indicador utilizado para acompanhar determinado resultado ou desempenho. |
| **Turnover** | Rotatividade de profissionais dentro de uma organização. |
| **Early Turnover** | Desligamento de profissionais nos primeiros meses ou no primeiro ano de trabalho. |
| **Absenteísmo** | Ausências não planejadas dos colaboradores. |
| **eNPS** | Indicador relacionado à percepção dos colaboradores sobre a organização. |
| **Quality of Hire** | Indicador utilizado para avaliar a qualidade das novas contratações. |
| **Time to Hire** | Tempo necessário para realizar uma contratação. |
| **Análise Descritiva** | Busca compreender o que aconteceu. |
| **Análise Diagnóstica** | Busca investigar por que determinado resultado aconteceu. |
| **Análise Preditiva** | Utiliza dados para estimar possíveis acontecimentos futuros. |
| **Análise Prescritiva** | Apoia a análise das possíveis ações diante de um cenário. |
| **9-Box Grid** | Ferramenta que relaciona desempenho e potencial dos profissionais. |
| **Data-driven** | Abordagem de tomada de decisão orientada por dados e evidências. |

---

## 💬 Prompts Reutilizáveis

Os prompts abaixo podem ser utilizados futuramente para consultar o segundo cérebro e aprofundar análises relacionadas à gestão de pessoas.

### Para compreender um indicador

> Explique o indicador [NOME DO INDICADOR], o que ele mede, como deve ser interpretado e quais outros indicadores deveriam ser analisados em conjunto.

### Para investigar um problema

> Considere o seguinte problema de gestão de pessoas: [PROBLEMA]. Com base nas fontes deste Notebook, quais dados e indicadores de People Analytics deveriam ser analisados antes da tomada de decisão?

### Para relacionar indicadores

> Analise a possível relação entre [INDICADOR 1], [INDICADOR 2] e [INDICADOR 3]. Quais hipóteses poderiam explicar o comportamento desses indicadores?

### Para apoiar uma decisão

> Com base exclusivamente nas fontes deste Notebook, analise o seguinte cenário: [CENÁRIO]. Organize a resposta em dados disponíveis, possíveis relações, hipóteses e informações adicionais necessárias antes de recomendar uma ação.

### Para estudar um conceito

> Explique [CONCEITO] de forma simples, apresente um exemplo aplicado à gestão de pessoas e indique quais fontes deste Notebook sustentam a explicação.

## 💬 Prompts Reutilizáveis

Conjunto de prompts desenvolvidos para futuras consultas ao segundo cérebro.

## 💡 Principais Aprendizados

O projeto permitiu observar como a curadoria de fontes e a engenharia de prompts influenciam a qualidade das respostas geradas por uma inteligência artificial baseada em fontes.

## 🛠️ Ferramentas Utilizadas

- NotebookLM
- GitHub
- Inteligência Artificial Generativa
- Markdown

## 👩‍💻 Autora

Gabriela Vilar
