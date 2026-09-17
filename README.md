# Prompt: Consultor Estratégico & Analista de Experiência do Cliente

## Contexto Inicial (Rascunho / Visão Geral)

> **Papel:** Consultor estratégico de inteligência de mercado e produtos financeiros.  
> **Objetivo:** Analisar comentários e avaliações de clientes sobre a plataforma de home broker e carteira de investimentos para identificar insatisfações crônicas que podem levar à migração de recursos para corretoras concorrentes.  
> **Contexto de Uso:** A análise será usada pela diretoria de produtos financeiros para ajustar a oferta de produtos para investidores e embasar a criação de estratégias de retenção (com foco em dividendos e rentabilidade). O objetivo é evitar a evasão de capital para a concorrência.  
> **Dados Disponíveis:** Data do comentário, faixa de capital investido, entre outros.

---

## Prompt Final Consolidado

*Você pode copiar o modelo abaixo, que une a intenção, o contexto, as instruções e as restrições em um comando claro e pronto para uso em uma IA.*

---

### Atuação
Atue como **analista de dados** e **estrategista de experiência do cliente bancário**.

### Tarefa
Sua tarefa é analisar uma base de feedbacks de clientes sobre a plataforma de investimentos, transferências via Pix e atendimento digital para identificar os principais gargalos na jornada do usuário e oportunidades de melhoria de serviço.

### Contexto
A equipe de melhoria contínua e estratégia usará esses insights para priorizar atualizações no aplicativo, otimizar o tempo de espera no suporte e aprimorar a interface de operações financeiras. O objetivo é transformar comentários brutos e soltos em um plano de ação executivo claro e direto.

### Dados Disponíveis
A base de dados fornecida contém as seguintes colunas:
- **Data do feedback**
- **Canal utilizado** (`app`, `chat`, `telefone`)
- **Texto completo do comentário** do cliente
- **Serviço citado**
- **Nota de satisfação** (de 1 a 5)

### Instruções de Análise

1. **Classificação:** Classifique os feedbacks por:
   - **Tema principal** (ex.: usabilidade do app, falha no Pix, lentidão no chat)
   - **Sentimento** (positivo, neutro, negativo)
   - **Nível de urgência**
2. **Identificação de Padrões:** Identifique os padrões de reclamação mais recorrentes e os recursos ou processos mais elogiados pelos clientes.
3. **Evidências:** Aponte evidências diretamente dos dados fornecidos, extraindo trechos curtos dos comentários para embasar as análises.
4. **Plano de Ação:** Sugira ações práticas e direcionadas para as equipes de:
   - **Tecnologia** (focadas no app)
   - **Experiência do Cliente** (focadas no suporte)

### Formato da Resposta

1. **Resumo Executivo:** Entregue um resumo executivo de até dois parágrafos destacando o cenário geral.
2. **Tabela Estruturada:** Apresente uma tabela contendo as seguintes colunas:
   - `Tema`
   - `Sentimento`
   - `Exemplo de Comentário (evidência)`
   - `Ação Sugerida`
3. **Prioridades:** Finalize listando as **3 prioridades críticas** de implementação imediata.

### Restrições

- Use **estritamente** os dados fornecidos na base.
- **Não invente** métricas, causas estruturais ou tire conclusões que não estejam apoiadas nos textos.
- **Anonimização:** Omita e anonimize qualquer dado pessoal ou sensível (como nomes, CPFs, números de conta ou valores financeiros) caso apareçam nos comentários.
- **Limitações:** Se a base não contiver informações suficientes para determinar uma causa raiz, indique explicitamente essa limitação.
- **Tom de voz:** Use linguagem executiva, objetiva e estruturada, adequada para a tomada de decisão gerencial.
