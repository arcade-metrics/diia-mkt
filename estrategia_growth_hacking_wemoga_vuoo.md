# Estratégia de Growth Hacking

Mudança 1

## Arquitetura e plano de implementação para WEMOGA e VUOO

**Versão:** 1.0\
**Data:** 11 de novembro de 2026\
**Horizonte inicial:** 30 dias para MVP operacional; 90 dias para
consolidação\
**Modelo operacional:** cloud, com Claude e OpenAI\
**Escopo:** inteligência de mercado, posicionamento, conteúdo, aquisição
B2B, campanhas, CRM, analytics e experimentação.

------------------------------------------------------------------------

# 1. Resumo executivo

Este documento propõe a implantação de uma operação de Growth Hacking
apoiada por agentes de IA para duas marcas: WEMOGA e VUOO.

A estratégia parte de uma decisão arquitetural central: **duas operações
comerciais independentes, apoiadas por uma infraestrutura compartilhada
de inteligência, agentes, skills, dados e automação**.

WEMOGA e VUOO têm públicos, propostas de valor, ciclos comerciais e
mensagens diferentes. Portanto, não devem compartilhar campanhas, ICPs
ou bases de leads indiscriminadamente. Podem, entretanto, compartilhar
componentes técnicos, padrões de pesquisa, ferramentas, governança,
analytics e conhecimento operacional.

O objetivo não é produzir conteúdo em escala por si só. É construir um
sistema capaz de:

1.  Identificar mercados, organizações, decisores e oportunidades.
2.  Transformar conhecimento técnico e experiência em posicionamento e
    autoridade.
3.  Produzir e distribuir conteúdo relevante em diferentes canais.
4.  Gerar leads e preparar abordagens comerciais contextualizadas.
5.  Apoiar o processo comercial e manter o CRM atualizado.
6.  Medir resultados e executar experimentos contínuos.
7.  Aprender com os dados e realocar esforços para os canais que geram
    oportunidades reais.

A primeira versão deve ser deliberadamente enxuta. Recomenda-se iniciar
com três agentes centrais --- Market Research, Content e Lead Generation
--- e acrescentar os demais após validar os fluxos.

## 1.1 Resultados esperados

Ao final dos primeiros 30 dias, espera-se ter:

-   Repositório Git versionado para a operação de Growth.
-   Contexto institucional e comercial separado para cada marca.
-   Skills de marketing selecionadas e instaladas.
-   Ambiente de trabalho com Claude e OpenAI.
-   Agente de pesquisa de mercado e concorrência.
-   Agente de produção e adaptação de conteúdo.
-   Agente de identificação e qualificação de leads.
-   Processo de aprovação humana para publicações e contatos externos.
-   CRM e métricas mínimas definidos.
-   Backlog inicial de experimentos de Growth.

As metas numéricas apresentadas neste documento são hipóteses de
partida, não previsões. Devem ser recalibradas após a primeira linha de
base.

------------------------------------------------------------------------

# 2. Princípios estratégicos

## 2.1 Duas marcas, duas operações

**WEMOGA** deve comunicar competência em desenvolvimento de software,
inteligência artificial, saúde, jogos, pesquisa aplicada e soluções
digitais. Sua aquisição é orientada a oportunidades de projetos,
contratos, parcerias e inovação.

**VUOO** deve comunicar uma proposta de valor específica para educação:
uma plataforma que apoia experiências pedagógicas adaptativas e
inclusivas, com IA e autoria docente. Sua aquisição é orientada a
escolas, redes de ensino, mantenedores, gestores e parceiros
educacionais.

A infraestrutura pode ser compartilhada, mas cada marca precisa ter:

-   ICP próprio.
-   Proposta de valor própria.
-   Mensagens e provas próprias.
-   Jornada comercial própria.
-   Pipeline próprio no CRM.
-   Calendário editorial próprio.
-   Métricas de aquisição e conversão próprias.

## 2.2 Growth não é apenas produção de conteúdo

A operação deve conectar pesquisa, distribuição, aquisição, conversão e
aprendizagem. Um conteúdo só é considerado bem-sucedido quando contribui
para um objetivo definido: descoberta, autoridade, tráfego qualificado,
geração de lead, reunião, demonstração, proposta ou venda.

## 2.3 Agentes especializados, com limites claros

Cada agente deve ter uma responsabilidade delimitada, entradas
conhecidas, ferramentas autorizadas e formato de saída padronizado. Um
agente não deve assumir que pode publicar, enviar mensagens, alterar
campanhas ou comprometer orçamento sem autorização.

## 2.4 Evidência e rastreabilidade

Pesquisas de mercado, afirmações sobre concorrentes, estatísticas,
referências científicas e alegações comerciais devem conter fonte, data
de consulta e nível de confiança. A IA não deve inventar dados,
clientes, resultados, depoimentos ou funcionalidades.

## 2.5 Aprovação humana nos pontos de risco

No MVP, os agentes podem pesquisar, analisar, redigir, classificar e
recomendar. A publicação, o envio de mensagens, a alteração de
orçamento, a importação de listas e qualquer ação externa devem depender
de aprovação humana.

------------------------------------------------------------------------

# 3. Objetivos e posicionamento por marca

## 3.1 WEMOGA

### Objetivo de negócio

Gerar oportunidades qualificadas para projetos de tecnologia,
desenvolvimento de software, IA, saúde digital, jogos, pesquisa aplicada
e soluções sob medida.

### Posicionamento de trabalho

Empresa de tecnologia que combina engenharia de software, inteligência
artificial e pesquisa aplicada para desenvolver soluções digitais
especializadas.

Esse posicionamento deve ser validado com o portfólio, os casos
autorizados, as competências atuais e os segmentos que a empresa deseja
priorizar.

### Públicos prioritários

-   Empresas que precisam desenvolver ou modernizar produtos digitais.
-   Organizações de saúde interessadas em soluções digitais.
-   Empresas com desafios de integração, automação ou IA aplicada.
-   Instituições de pesquisa e inovação.
-   Organizações que precisam transformar conhecimento especializado em
    software.
-   Parceiros que buscam capacidade técnica para projetos conjuntos.

### Linhas editoriais

1.  IA aplicada a problemas reais.
2.  Engenharia e desenvolvimento de produtos digitais.
3.  Saúde digital e tecnologia.
4.  Jogos, interação e tecnologias imersivas.
5.  Pesquisa aplicada e inovação.
6.  Estudos de caso e demonstrações técnicas.
7.  Bastidores de engenharia, arquitetura e experimentação.

### Canais prioritários

-   LinkedIn institucional e perfis profissionais.
-   Website e páginas de soluções.
-   SEO e GEO.
-   Prospecção B2B direcionada.
-   Eventos, comunidades e parcerias.
-   E-mail comercial individualizado, respeitando a legislação e as
    políticas dos canais.

### Conversões desejadas

-   Solicitação de conversa técnica.
-   Reunião de descoberta.
-   Briefing de projeto.
-   Pedido de proposta.
-   Parceria ou colaboração.
-   Demonstração de capacidade técnica.

## 3.2 VUOO

### Objetivo de negócio

Gerar interesse qualificado, demonstrações e pilotos com escolas e redes
de ensino, além de construir autoridade no setor educacional.

### Posicionamento de trabalho

VUOO é um ecossistema para escolas e redes de ensino que combina
experiências pedagógicas, microjogos, adaptação e IA. Seu posicionamento
deve destacar a autoria docente: professores passam progressivamente de
consumidores de ferramentas de IA a autores de experiências pedagógicas.

A comunicação deve explicar o valor para a escola e para o professor sem
reduzir o produto a uma coleção de jogos ou a um chatbot.

### Públicos prioritários

-   Mantenedores e proprietários de escolas.
-   Diretores e gestores de redes de ensino.
-   Coordenadores pedagógicos.
-   Lideranças de inovação e tecnologia educacional.
-   Professores influenciadores e formadores.
-   Parceiros de conteúdo, pesquisa e distribuição.

### Linhas editoriais

1.  Professor como autor de experiências pedagógicas com IA.
2.  Inclusão, acessibilidade e desenho universal para aprendizagem.
3.  Aprendizagem adaptativa e personalização.
4.  Microjogos e experiências curtas de aprendizagem.
5.  BNCC e habilidades funcionais.
6.  Uso responsável de IA na escola.
7.  Dados educacionais e acompanhamento pedagógico.
8.  Demonstrações práticas da plataforma.
9.  Estudos, evidências e fundamentos pedagógicos.

### Canais prioritários

-   LinkedIn para gestores, mantenedores e parceiros.
-   Conteúdo e comunidade para professores.
-   Website e landing pages para escolas.
-   Webinars, demonstrações e eventos.
-   Parcerias com instituições e especialistas.
-   Prospecção direcionada de redes e escolas.

### Conversões desejadas

-   Solicitação de demonstração.
-   Inscrição em webinar.
-   Diagnóstico institucional.
-   Reunião com gestor.
-   Escola interessada em piloto.
-   Parceria institucional.

### Ativo de aquisição recomendado

Criar um diagnóstico de maturidade digital, autoria docente e inclusão
pedagógica para escolas. O diagnóstico deve ser útil por si só, coletar
apenas os dados necessários e gerar um relatório de recomendações. Não
deve prometer avaliação clínica ou substituir avaliação profissional.

------------------------------------------------------------------------

# 4. Segmentação e ICP

ICP significa Ideal Customer Profile: o perfil de organização com maior
probabilidade de obter valor da solução e avançar no processo comercial.

## 4.1 ICP inicial da WEMOGA

Construir uma matriz de segmentação com:

-   Setor e porte da organização.
-   Problema tecnológico aparente.
-   Evidência pública de investimento ou transformação digital.
-   Compatibilidade com as competências da WEMOGA.
-   Acesso a decisores.
-   Potencial de orçamento.
-   Urgência e janela de contratação.
-   Possibilidade de recorrência ou expansão.
-   Potencial de parceria ou referência.

Classificação sugerida:

-   **A:** forte aderência, problema identificável, decisor acessível e
    oportunidade plausível.
-   **B:** aderência razoável, mas falta evidência de urgência,
    orçamento ou acesso.
-   **C:** aderência fraca ou oportunidade ainda especulativa.

## 4.2 ICP inicial da VUOO

Segmentar escolas e redes considerando:

-   Número de unidades e estudantes.
-   Etapas de ensino atendidas.
-   Estrutura de coordenação pedagógica.
-   Maturidade digital.
-   Iniciativas de inclusão e acessibilidade.
-   Interesse em IA e inovação pedagógica.
-   Capacidade de realizar piloto.
-   Processo de decisão e calendário escolar.
-   Potencial de expansão para outras unidades.

Priorizar organizações nas quais seja possível identificar uma
necessidade concreta e um responsável pelo processo de decisão.

## 4.3 Personas e comitê de compra

Não tratar uma organização como se tivesse um único decisor. Mapear,
conforme o caso:

-   Decisor econômico: aprova orçamento e contratação.
-   Decisor técnico: avalia integração, segurança e infraestrutura.
-   Decisor funcional: responde pelo problema ou processo.
-   Influenciador: recomenda, testa ou valida a solução.
-   Usuário: utilizará a solução no cotidiano.

Para VUOO, por exemplo, mantenedor, diretor, coordenador pedagógico e
professor podem ter necessidades e objeções diferentes. A mensagem deve
variar conforme o papel.

------------------------------------------------------------------------

# 5. Arquitetura tecnológica

## 5.1 Visão geral

A arquitetura terá seis camadas:

1.  Interface de trabalho e desenvolvimento.
2.  Modelos de linguagem.
3.  Skills e agentes.
4.  Orquestração e workflows.
5.  Dados, CRM e fontes externas.
6.  Observabilidade, segurança e governança.

### Diagrama lógico

``` text
USUÁRIO / EQUIPE
       |
       v
Claude Code / Codex / Interfaces internas
       |
       v
CAMADA DE MODELOS
Claude API | OpenAI API
       |
       v
ORQUESTRADOR
OpenAI Agents SDK / n8n
       |
       +-------------------------------+
       |               |               |
       v               v               v
  RESEARCH          CONTENT           LEADS
  AGENTS            AGENTS            AGENTS
       |               |               |
       +---------------+---------------+
                       |
                       v
              SERVIÇOS E FERRAMENTAS
        MCP | Search | CRM | Analytics | CMS
                       |
                       v
                 DADOS CENTRAIS
        PostgreSQL | Arquivos | Base de fontes
                       |
             +---------+---------+
             |                   |
             v                   v
          WEMOGA               VUOO
       Contexto/ICP         Contexto/ICP
       Pipeline             Pipeline
       Campanhas            Campanhas
       Métricas             Métricas
```

## 5.2 Modelos e responsabilidades

### Claude

Usos recomendados:

-   Pesquisa e síntese de mercado.
-   Análise de concorrentes.
-   Estratégia e posicionamento.
-   Análise de documentos extensos.
-   Planejamento editorial.
-   Revisão crítica de materiais.
-   Produção de conteúdo técnico e institucional.

### OpenAI

Usos recomendados:

-   Agentes operacionais com ferramentas.
-   Classificação e extração estruturada.
-   Workflows com etapas e handoffs.
-   Integração com serviços e APIs.
-   Avaliação automatizada de saídas.
-   Relatórios e tarefas repetíveis.

Não é necessário fixar permanentemente cada tarefa em um único
fornecedor. O sistema deve permitir trocar o modelo por tarefa, custo,
latência e qualidade.

## 5.3 Agentes de desenvolvimento versus agentes de produção

Claude Code e Codex podem ajudar a construir, testar e manter o projeto.
Não devem ser confundidos com o runtime de marketing em produção.

Para produção, utilizar APIs e serviços controlados, com:

-   Identidade própria para cada agente.
-   Ferramentas autorizadas por função.
-   Limites de custo e execução.
-   Logs e rastreabilidade.
-   Controle de acesso.
-   Avaliação de qualidade.
-   Aprovação humana para ações externas.

## 5.4 Orquestração

Recomendação inicial:

-   OpenAI Agents SDK para fluxos de agentes Python, handoffs,
    ferramentas e rastreamento.
-   n8n para integrações, gatilhos, agendas, notificações e automações
    entre serviços.
-   MCP para disponibilizar ferramentas e fontes de dados de maneira
    padronizada.

Não introduzir LangGraph no primeiro MVP. Avaliar posteriormente caso os
fluxos exijam estado complexo, retomada de execução, ciclos longos ou
controle granular de grafos.

## 5.5 Banco de dados

PostgreSQL deve ser a fonte central de dados operacionais.

Entidades iniciais:

-   Brand
-   ICP
-   Organization
-   Contact
-   Lead
-   Opportunity
-   Competitor
-   Source
-   Research
-   ContentAsset
-   Campaign
-   Channel
-   Experiment
-   Metric
-   AgentRun
-   Approval
-   Activity

Cada registro deve ter marca associada quando aplicável. A separação
lógica entre WEMOGA e VUOO deve ser aplicada nas consultas, permissões e
relatórios.

------------------------------------------------------------------------

# 6. Agentes especializados

A primeira versão deve conter três agentes em operação e os demais como
evolução planejada.

## 6.1 Market Research Agent

**Missão:** encontrar e organizar informações relevantes sobre mercados,
segmentos, organizações, concorrentes e oportunidades.

Entradas:

-   Marca e objetivo da pesquisa.
-   Segmento ou território.
-   ICP.
-   Perguntas de negócio.
-   Fontes autorizadas.

Atividades:

1.  Pesquisar fontes públicas.
2.  Identificar organizações e concorrentes.
3.  Extrair informações relevantes.
4.  Registrar URLs, datas e trechos de evidência.
5.  Diferenciar fatos, inferências e hipóteses.
6.  Avaliar aderência ao ICP.
7.  Produzir relatório com oportunidades e lacunas.

Saída padronizada:

-   Resumo executivo.
-   Oportunidades identificadas.
-   Evidências e fontes.
-   Concorrentes e alternativas.
-   Hipóteses.
-   Nível de confiança.
-   Próximas ações recomendadas.

Restrições:

-   Não inventar informações.
-   Não apresentar inferências como fatos.
-   Não coletar dados pessoais desnecessários.
-   Não realizar contato com organizações.

## 6.2 Growth Strategist Agent

**Missão:** transformar objetivos e dados em prioridades, hipóteses e
experimentos de crescimento.

Atividades:

-   Definir objetivos por marca.
-   Analisar funil e gargalos.
-   Propor canais e campanhas.
-   Priorizar experimentos.
-   Definir métricas e critérios de sucesso.
-   Recomendar alocação de esforço.

Framework recomendado: ICE.

ICE = Impacto × Confiança × Facilidade, com notas de 1 a 10. A fórmula
de priorização pode ser a média dos três valores. Registrar a
justificativa de cada nota.

Saída:

-   Hipótese.
-   Público.
-   Canal.
-   Mudança proposta.
-   Métrica principal.
-   Métricas de proteção.
-   Esforço.
-   Riscos.
-   Critério de decisão.

## 6.3 Content Agent

**Missão:** transformar estratégia, conhecimento e pesquisa em ativos de
conteúdo adequados a cada público e canal.

Etapas:

1.  Receber pauta e objetivo.
2.  Consultar o contexto da marca.
3.  Pesquisar e registrar evidências.
4.  Propor estrutura.
5.  Produzir versão principal.
6.  Adaptar para formatos secundários.
7.  Verificar consistência factual e tom.
8.  Submeter à aprovação.

Formatos:

-   Artigos.
-   Posts para LinkedIn.
-   Newsletters.
-   Roteiros de vídeo.
-   Estudos de caso.
-   Páginas de solução.
-   Materiais para webinars.
-   Apresentações comerciais.

Não gerar variações superficiais em massa. Cada peça deve ter público,
objetivo, argumento central e chamada para ação.

## 6.4 SEO/GEO Agent

**Missão:** melhorar descoberta orgânica nos mecanismos de busca
tradicionais e nos mecanismos de resposta baseados em IA.

Atividades:

-   Pesquisa de palavras-chave e intenção.
-   Auditoria técnica.
-   Estruturação de páginas.
-   Links internos.
-   Dados estruturados.
-   Otimização de títulos e descrições.
-   Identificação de lacunas de conteúdo.
-   Monitoramento de consultas e tráfego.
-   Avaliação de presença em respostas de IA, quando mensurável.

GEO deve ser tratado como uma prática experimental de descoberta e
clareza de conteúdo, não como garantia de posicionamento em respostas de
IA.

## 6.5 Lead Generation Agent

**Missão:** identificar organizações potencialmente aderentes ao ICP e
preparar listas justificadas para revisão comercial.

Atividades:

-   Pesquisar organizações.
-   Identificar evidências de aderência.
-   Identificar cargos e canais profissionais públicos.
-   Classificar prioridade.
-   Registrar fonte e data.
-   Sugerir hipótese de necessidade.
-   Preparar resumo para abordagem.

Não enviar mensagens automaticamente no MVP. Evitar coleta
indiscriminada, scraping incompatível com termos de uso ou
enriquecimento de dados pessoais sem base legal.

## 6.6 Sales Intelligence Agent

**Missão:** apoiar a preparação de reuniões e o avanço de oportunidades.

Atividades:

-   Preparar briefing da organização.
-   Resumir histórico de interações.
-   Identificar possíveis necessidades.
-   Preparar perguntas de descoberta.
-   Sugerir materiais relevantes.
-   Registrar próximos passos após validação humana.

## 6.7 Campaign Agent

**Missão:** planejar campanhas integradas e acompanhar sua execução.

Atividades:

-   Definir objetivo e público.
-   Planejar mensagem e oferta.
-   Preparar landing page e peças.
-   Definir orçamento proposto.
-   Configurar parâmetros de tracking.
-   Monitorar resultados.
-   Recomendar otimizações.

Alterações de orçamento e publicação exigem autorização.

## 6.8 Analytics & CRO Agent

**Missão:** identificar oportunidades de melhoria no funil e avaliar
experimentos.

Atividades:

-   Consolidar métricas.
-   Detectar variações relevantes.
-   Analisar páginas e etapas do funil.
-   Formular hipóteses.
-   Sugerir testes.
-   Documentar resultados.
-   Evitar conclusões causais sem desenho experimental adequado.

------------------------------------------------------------------------

# 7. Skills e repositórios

Skills são instruções e procedimentos reutilizáveis. Elas não são, por
si só, agentes autônomos. Um agente utiliza uma ou mais skills para
executar uma tarefa.

## 7.1 Repositório principal: Marketing Skills

Projeto: https://github.com/coreyhaines31/marketingskills

Prioridade de avaliação:

-   Marketing planning.
-   Product marketing.
-   Customer research.
-   Competitor analysis.
-   Prospecting.
-   Marketing ideas.
-   SEO audit.
-   AI SEO.
-   Content strategy.
-   Copywriting.
-   Social content.
-   CRO.
-   Analytics.
-   RevOps.
-   Sales enablement.

Instalar somente as skills necessárias. Revisar os arquivos antes de
utilizá-los em operações com acesso a dados ou ferramentas.

## 7.2 Repositórios complementares

  -------------------------------------------------------------------------------------
  Repositório                                       Utilização
  ------------------------------------------------- -----------------------------------
  https://github.com/anthropics/skills              Exemplos e padrões de skills

  https://github.com/modelcontextprotocol/servers   Servidores MCP de referência

  https://github.com/openai/openai-agents-python    Construção de agentes Python

  https://github.com/n8n-io/n8n                     Workflows e integrações

  https://github.com/airbytehq/airbyte              Integração de dados, se necessária
  -------------------------------------------------------------------------------------

A adoção de cada projeto deve considerar manutenção, licença, segurança,
compatibilidade e necessidade real. Não instalar todos apenas por
estarem disponíveis.

## 7.3 Política de skills

Toda skill adicionada deve ter:

-   Nome e finalidade.
-   Fonte e versão.
-   Licença.
-   Ferramentas necessárias.
-   Dados acessados.
-   Riscos conhecidos.
-   Agentes autorizados a utilizá-la.
-   Testes mínimos.
-   Responsável pela aprovação.

------------------------------------------------------------------------

# 8. Estrutura do repositório

Nome sugerido: `growth-ai`.

``` text
growth-ai/
│
├── README.md
├── ROADMAP.md
├── ARCHITECTURE.md
├── SECURITY.md
├── .env.example
│
├── brands/
│   ├── wemoga/
│   │   ├── brand.md
│   │   ├── positioning.md
│   │   ├── icp.md
│   │   ├── personas.md
│   │   ├── proof-points.md
│   │   ├── competitors.md
│   │   ├── tone-of-voice.md
│   │   └── campaigns/
│   │
│   └── vuoo/
│       ├── brand.md
│       ├── positioning.md
│       ├── icp.md
│       ├── personas.md
│       ├── proof-points.md
│       ├── competitors.md
│       ├── tone-of-voice.md
│       └── campaigns/
│
├── agents/
│   ├── research/
│   │   ├── agent.md
│   │   └── output-schema.json
│   ├── growth/
│   ├── content/
│   ├── seo-geo/
│   ├── leads/
│   ├── sales/
│   ├── campaigns/
│   └── analytics/
│
├── skills/
│   ├── README.md
│   └── registry.md
│
├── workflows/
│   ├── market-research/
│   ├── content-production/
│   ├── lead-generation/
│   ├── campaign-management/
│   ├── sales-support/
│   └── weekly-report/
│
├── prompts/
│   ├── research/
│   ├── content/
│   ├── sales/
│   └── evaluation/
│
├── schemas/
│   ├── lead.schema.json
│   ├── research.schema.json
│   ├── content.schema.json
│   └── experiment.schema.json
│
├── integrations/
│   ├── crm/
│   ├── analytics/
│   ├── search/
│   └── mcp/
│
├── evaluations/
│   ├── research/
│   ├── content/
│   └── leads/
│
├── data/
│   ├── research/
│   ├── sources/
│   └── exports/
│
└── reports/
    ├── weekly/
    └── monthly/
```

Dados pessoais, credenciais, exports sensíveis e arquivos privados não
devem ser versionados no Git.

------------------------------------------------------------------------

# 9. Instalação e configuração

## 9.1 Pré-requisitos

-   Git.
-   Node.js em versão LTS compatível com as ferramentas.
-   Python em versão suportada pelo Agents SDK.
-   VS Code.
-   Acesso às APIs Claude e OpenAI.
-   Contas e permissões para CRM e analytics.
-   Gerenciador seguro de segredos.

## 9.2 Criar o projeto

``` bash
mkdir growth-ai
cd growth-ai
git init
```

Criar o arquivo `.env.example`:

``` dotenv
ANTHROPIC_API_KEY=
OPENAI_API_KEY=

DATABASE_URL=

HUBSPOT_ACCESS_TOKEN=

GA4_PROPERTY_ID=
GOOGLE_SEARCH_CONSOLE_SITE=

N8N_BASE_URL=
N8N_API_KEY=
```

O arquivo `.env` real deve ficar fora do Git.

## 9.3 Instalar skills

Exemplo de instalação com a CLI do ecossistema Agent Skills:

``` bash
npx skills add coreyhaines31/marketingskills --list
```

Depois, instalar as skills selecionadas conforme a sintaxe e os nomes
apresentados pela versão atual da CLI. Validar os destinos de instalação
para Claude Code e Codex.

Não assumir que todas as skills do repositório são necessárias ou que
seus nomes permanecerão iguais entre versões.

## 9.4 Instalar ambiente Python

``` bash
python -m venv .venv
```

Windows:

``` powershell
.venv\Scripts\activate
```

Instalar o SDK:

``` bash
pip install openai-agents
```

Adicionar somente as dependências efetivamente utilizadas. Fixar versões
em arquivo de dependências após validar o ambiente.

## 9.5 Configurar Claude e OpenAI

-   Configurar credenciais no ambiente de execução.
-   Separar desenvolvimento e produção.
-   Definir limites de custo.
-   Registrar modelo e versão por execução.
-   Criar testes para cada agente.
-   Evitar enviar dados sensíveis desnecessários aos provedores.

## 9.6 Configurar n8n

Executar inicialmente em ambiente de teste. Criar credenciais
específicas para cada integração e conceder somente os escopos
necessários.

Workflows iniciais:

-   Pesquisa semanal.
-   Produção editorial.
-   Revisão e aprovação.
-   Identificação de leads.
-   Relatório semanal.
-   Notificação de tarefas pendentes.

------------------------------------------------------------------------

# 10. Workflows operacionais

## 10.1 Workflow A --- Inteligência de mercado

**Objetivo:** encontrar oportunidades e mudanças relevantes para cada
marca.

Gatilho: execução semanal ou solicitação manual.

Fluxo:

1.  Selecionar marca e segmento.
2.  Carregar ICP e posicionamento.
3.  Pesquisar fontes públicas.
4.  Registrar URL, título, data e evidência.
5.  Extrair fatos e oportunidades.
6.  Comparar com critérios de ICP.
7.  Identificar lacunas e incertezas.
8.  Gerar relatório.
9.  Submeter recomendações à equipe.

Saída:

-   Resumo executivo.
-   Tendências observadas.
-   Organizações relevantes.
-   Concorrentes e alternativas.
-   Oportunidades classificadas.
-   Fontes e confiança.
-   Próximas ações.

## 10.2 Workflow B --- Content Factory

**Objetivo:** produzir conteúdo consistente, verificável e distribuível.

Gatilho: pauta aprovada.

Fluxo:

1.  Definir marca, público, objetivo e canal.
2.  Consultar documentação da marca.
3.  Pesquisar evidências.
4.  Criar briefing.
5.  Aprovar argumento e estrutura.
6.  Redigir conteúdo principal.
7.  Adaptar para outros canais.
8.  Revisar fatos, links e linguagem.
9.  Verificar consistência de marca.
10. Submeter para aprovação.
11. Agendar ou publicar após aprovação.
12. Medir desempenho.

Cada conteúdo deve ter identificador, responsável, versão, status, data
e objetivo.

## 10.3 Workflow C --- Lead Generation

**Objetivo:** montar listas pequenas e justificadas de organizações com
aderência ao ICP.

Gatilho: campanha ou pesquisa de segmento.

Fluxo:

1.  Definir segmento, território e perfil.
2.  Pesquisar organizações.
3.  Registrar evidências públicas.
4.  Classificar aderência.
5.  Identificar possíveis decisores em fontes profissionais apropriadas.
6.  Verificar duplicidade.
7.  Registrar origem e data.
8.  Preparar hipótese de abordagem.
9.  Submeter lista à revisão.
10. Registrar no CRM após aprovação.

Não automatizar envio de mensagens no MVP.

## 10.4 Workflow D --- Sales Intelligence

**Objetivo:** preparar reuniões e apoiar o avanço comercial.

Antes da reunião:

-   Resumo da organização.
-   Contexto do contato.
-   Hipóteses de necessidade.
-   Perguntas de descoberta.
-   Casos e materiais pertinentes.
-   Próximo passo sugerido.

Depois da reunião:

-   Resumo das informações fornecidas.
-   Necessidades identificadas.
-   Objeções.
-   Responsáveis e prazos.
-   Próximas ações propostas.

O agente deve distinguir informações fornecidas pelo cliente de
hipóteses produzidas pela IA.

## 10.5 Workflow E --- Growth Experiments

**Objetivo:** transformar gargalos em experimentos mensuráveis.

Fluxo:

1.  Observar um dado ou problema.
2.  Formular hipótese.
3.  Identificar público e canal.
4.  Definir métrica principal.
5.  Definir métricas de proteção.
6.  Estimar impacto, confiança e esforço.
7.  Aprovar experimento.
8.  Executar.
9.  Medir.
10. Documentar resultado.
11. Decidir: manter, ampliar, ajustar ou encerrar.

Não declarar um teste A/B vencedor sem volume e método compatíveis com a
conclusão.

## 10.6 Workflow F --- Relatório semanal

O relatório deve consolidar:

-   Leads novos e qualificados.
-   Reuniões e demonstrações.
-   Oportunidades em andamento.
-   Conteúdos publicados.
-   Tráfego e conversões.
-   Campanhas ativas.
-   Experimentos e resultados.
-   Custos de ferramentas e modelos.
-   Riscos e decisões pendentes.

WEMOGA e VUOO devem ter relatórios separados, além de uma visão
executiva consolidada.

------------------------------------------------------------------------

# 11. CRM, dados e métricas

## 11.1 CRM

HubSpot é uma opção inicial para centralizar contatos, empresas,
negócios e atividades. Antes de contratar ou ampliar o plano, verificar
os recursos e limites disponíveis na modalidade escolhida.

Pipeline sugerido para WEMOGA:

1.  Organização identificada.
2.  Lead qualificado.
3.  Descoberta agendada.
4.  Diagnóstico realizado.
5.  Proposta em elaboração.
6.  Proposta enviada.
7.  Negociação.
8.  Ganho ou perdido.

Pipeline sugerido para VUOO:

1.  Escola/rede identificada.
2.  Interesse qualificado.
3.  Contato com decisor.
4.  Demonstração agendada.
5.  Demonstração realizada.
6.  Avaliação de piloto.
7.  Piloto em andamento.
8.  Proposta comercial.
9.  Contrato ou encerramento.

## 11.2 Métricas de aquisição

-   Visitantes por canal.
-   Sessões qualificadas.
-   Conversão de landing page.
-   Leads gerados.
-   Leads qualificados.
-   Custo por lead.
-   Custo por oportunidade.
-   Reuniões agendadas.
-   Taxa de comparecimento.
-   Conversão entre etapas.
-   Tempo de ciclo comercial.
-   Receita atribuída, quando disponível.

## 11.3 Métricas de conteúdo

-   Conteúdos publicados.
-   Alcance por canal.
-   Cliques.
-   Engajamento qualificado.
-   Tráfego orgânico.
-   Conversões assistidas.
-   Leads originados ou influenciados.
-   Temas com maior resposta do público.

Curtidas e impressões são indicadores auxiliares, não substitutos de
aquisição e conversão.

## 11.4 Metas iniciais para 30 dias

Hipóteses de trabalho:

  Indicador                     WEMOGA   VUOO
  --------------------------- -------- ------
  Leads qualificados                20     20
  Reuniões ou demonstrações          5      5
  Conteúdos publicados               8      8
  Experimentos documentados          2      2

Esses números devem ser revistos após análise de capacidade operacional,
mercado, orçamento e histórico real.

------------------------------------------------------------------------

# 12. Estratégia de canais

## 12.1 LinkedIn

Canal prioritário para as duas marcas, com públicos e mensagens
distintos.

WEMOGA:

-   Conteúdo técnico.
-   Estudos de caso.
-   Aprendizados de engenharia.
-   IA aplicada.
-   Parcerias e inovação.

VUOO:

-   Gestão educacional.
-   Autoria docente.
-   Inclusão e acessibilidade.
-   IA na prática pedagógica.
-   Demonstrações de experiências.

Distribuição recomendada:

-   Publicação institucional.
-   Publicação por especialistas e profissionais autorizados.
-   Participação em discussões relevantes.
-   Conteúdos aprofundados com chamadas para conversas.
-   Mensuração de leads e reuniões, não apenas alcance.

## 12.2 Website e landing pages

Criar páginas específicas por problema e público. Evitar uma página
genérica que tente explicar todas as competências ao mesmo tempo.

WEMOGA:

-   Desenvolvimento de produtos digitais.
-   IA aplicada.
-   Saúde digital.
-   Jogos e tecnologias interativas.
-   Pesquisa e inovação.

VUOO:

-   Visão geral da plataforma.
-   Para gestores e mantenedores.
-   Para coordenação pedagógica.
-   Para professores.
-   Inclusão e aprendizagem adaptativa.
-   Demonstração e piloto.

Cada página deve ter uma ação principal clara.

## 12.3 SEO e GEO

Priorizar:

-   Conteúdo original e útil.
-   Autoria identificável.
-   Referências verificáveis.
-   Páginas com propósito claro.
-   Dados estruturados quando adequados.
-   Boa experiência técnica.
-   Links internos.
-   Atualização de conteúdo.
-   Respostas claras a perguntas reais dos públicos.

Não produzir páginas em massa apenas para capturar palavras-chave.

## 12.4 E-mail e prospecção

Usar comunicação contextualizada, individualizada e relevante. Respeitar
LGPD, regras de marketing, políticas dos provedores e mecanismos de
descadastro.

Evitar:

-   Listas compradas sem avaliação de legitimidade.
-   Disparos massivos não solicitados.
-   Mensagens enganosas.
-   Falsa personalização.
-   Uso de dados sensíveis.
-   Automação que dificulte o descadastro.

------------------------------------------------------------------------

# 13. Governança, segurança e qualidade

## 13.1 Níveis de autonomia

**Nível 0 --- consulta:** agente apenas pesquisa e responde.

**Nível 1 --- preparação:** agente produz rascunhos, listas e
recomendações.

**Nível 2 --- ação aprovada:** agente executa uma ação após aprovação
humana.

**Nível 3 --- automação limitada:** agente executa ações de baixo risco,
com escopo e limites definidos, logs e possibilidade de reversão.

No MVP, operar principalmente nos níveis 0 e 1. Algumas ações de nível 2
podem ser introduzidas depois de testes.

## 13.2 Segurança

-   Segredos fora do repositório.
-   Chaves diferentes para desenvolvimento e produção.
-   Permissões mínimas.
-   Logs de acesso e execução.
-   Limites de custo e chamadas.
-   Validação de entradas.
-   Proteção contra prompt injection em conteúdo externo.
-   Separação entre instruções do sistema e documentos pesquisados.
-   Revisão de dependências e skills.
-   Política de retenção e exclusão de dados.

## 13.3 LGPD

A operação deve documentar finalidade, base legal, necessidade,
retenção, acesso e compartilhamento dos dados pessoais tratados.

Para prospecção B2B, não presumir que qualquer dado profissional público
pode ser utilizado sem limites. Avaliar finalidade, legítimo interesse
quando aplicável, transparência, oposição e demais obrigações
pertinentes.

Dados de estudantes, informações de saúde e dados sensíveis não devem
ser usados em campanhas ou ferramentas de marketing.

## 13.4 Qualidade dos agentes

Criar conjuntos de avaliação com exemplos reais e resultados esperados.

Avaliar:

-   Precisão factual.
-   Qualidade das fontes.
-   Relevância para ICP.
-   Consistência da marca.
-   Clareza.
-   Utilidade comercial.
-   Taxa de retrabalho.
-   Custo por execução.
-   Tempo de execução.

------------------------------------------------------------------------

# 14. Plano de execução

## Fase 1 --- Fundação (dias 1 a 3)

Entregas:

-   Repositório `growth-ai`.
-   Estrutura de pastas.
-   Instalação e avaliação das skills.
-   Configuração de Claude e OpenAI.
-   Política inicial de segurança.
-   Templates de contexto das marcas.

Critério de conclusão: ambiente versionado, credenciais protegidas e
contexto mínimo de cada marca documentado.

## Fase 2 --- Inteligência (dias 4 a 7)

Entregas:

-   ICP inicial da WEMOGA.
-   ICP inicial da VUOO.
-   Mapeamento de concorrentes.
-   Lista inicial de organizações-alvo.
-   Agente Market Research.
-   Formato padronizado de relatório.

Critério de conclusão: relatório de pesquisa rastreável e revisado para
cada marca.

## Fase 3 --- Conteúdo (dias 8 a 17)

Entregas:

-   Content Agent.
-   Calendário editorial.
-   Pautas prioritárias.
-   Conteúdos-piloto.
-   Processo de revisão.
-   Landing pages prioritárias.
-   Primeira auditoria SEO/GEO.

Critério de conclusão: conteúdo aprovado e publicado, com tracking
funcional.

## Fase 4 --- Aquisição (dias 18 a 22)

Entregas:

-   Lead Generation Agent.
-   Critérios de qualificação.
-   Integração inicial com CRM.
-   Listas revisadas.
-   Briefings de abordagem.
-   Processo comercial definido.

Critério de conclusão: leads rastreáveis e aceitos pela equipe
comercial.

## Fase 5 --- Experimentos e análise (dias 23 a 30)

Entregas:

-   Analytics Agent.
-   Dashboard mínimo.
-   Backlog ICE.
-   Quatro experimentos documentados.
-   Relatório executivo.
-   Revisão de custo e qualidade.

Critério de conclusão: primeiro ciclo de Growth concluído e decisões
registradas.

## Fase 6 --- Consolidação (dias 31 a 90)

-   Melhorar a qualificação de leads.
-   Integrar CRM e canais.
-   Automatizar relatórios.
-   Ampliar SEO/GEO.
-   Testar campanhas pagas com orçamento controlado.
-   Criar rotinas de webinar e demonstração para VUOO.
-   Desenvolver estudos de caso para WEMOGA.
-   Avaliar agentes adicionais.
-   Otimizar custo por lead e oportunidade.
-   Criar playbooks comerciais.

------------------------------------------------------------------------

# 15. Backlog priorizado

## P0 --- Obrigatório para o MVP

1.  Repositório Git.
2.  Contexto das duas marcas.
3.  ICP inicial por marca.
4.  Skills essenciais de marketing.
5.  Configuração Claude e OpenAI.
6.  Market Research Agent.
7.  Content Agent.
8.  Lead Generation Agent.
9.  Aprovação humana.
10. CRM e tracking mínimos.

## P1 --- Após validação inicial

1.  SEO/GEO Agent.
2.  Growth Strategist Agent.
3.  Analytics Agent.
4.  Sales Intelligence Agent.
5.  Workflows no n8n.
6.  Dashboard executivo.
7.  Calendário editorial automatizado.
8.  Landing pages segmentadas.
9.  Experimentos A/B.
10. Integração com ferramentas de publicação.

## P2 --- Escala

1.  Campaign Agent com integrações de mídia.
2.  Atribuição multicanal.
3.  Modelos de scoring calibrados com dados históricos.
4.  Personalização de conteúdo por segmento.
5.  Automação limitada de tarefas de baixo risco.
6.  Biblioteca de experimentos reutilizáveis.
7.  Agentes especializados por setor.
8.  Relatórios preditivos, quando houver dados suficientes.

------------------------------------------------------------------------

# 16. Orçamento e controle de custos

Não estabelecer um orçamento fixo antes de medir o uso. Os principais
componentes serão:

-   Consumo de Claude API.
-   Consumo de OpenAI API.
-   Hospedagem de n8n e serviços auxiliares.
-   Banco de dados.
-   CRM.
-   Ferramentas de SEO e pesquisa, se contratadas.
-   Analytics e mídia paga.
-   Eventuais serviços de enriquecimento de dados.

## 16.1 Estratégia de redução de custos

-   Usar modelos menores para classificação e tarefas simples.
-   Reservar modelos mais capazes para pesquisa complexa e decisões
    importantes.
-   Limitar tamanho de contexto.
-   Reutilizar resultados de pesquisa.
-   Armazenar fontes e documentos.
-   Evitar repetir chamadas sem necessidade.
-   Definir limites por agente e workflow.
-   Monitorar custo por lead, conteúdo e oportunidade.

## 16.2 Métricas de custo

Registrar por execução:

-   Marca.
-   Agente.
-   Modelo.
-   Tokens de entrada e saída, quando disponíveis.
-   Custo estimado.
-   Duração.
-   Resultado.
-   Status.
-   Necessidade de revisão humana.

O custo de IA deve ser comparado ao valor operacional e comercial
produzido, não apenas ao número de chamadas.

------------------------------------------------------------------------

# 17. Prompts-base dos agentes

Os prompts abaixo são pontos de partida. Devem ser versionados e
avaliados com exemplos reais.

## 17.1 Market Research Agent

``` text
Você é um analista de inteligência de mercado.

Sua tarefa é pesquisar oportunidades para a marca indicada.
Utilize o contexto de marca e ICP fornecido.

Regras:
1. Pesquise fontes públicas e identificáveis.
2. Registre URL e data de consulta.
3. Separe fatos, inferências e hipóteses.
4. Não invente dados ou declarações.
5. Avalie aderência ao ICP.
6. Informe lacunas e incertezas.
7. Recomende ações comerciais concretas.

Entregue:
- Resumo executivo
- Evidências
- Organizações relevantes
- Concorrentes
- Oportunidades
- Riscos
- Próximas ações
```

## 17.2 Content Agent

``` text
Você é um estrategista e produtor de conteúdo B2B.

Produza conteúdo para a marca e público indicados.
Consulte posicionamento, ICP, tom de voz e provas disponíveis.

Regras:
1. Não invente funcionalidades, clientes ou resultados.
2. Não transforme hipótese em fato.
3. Utilize fontes verificáveis quando necessário.
4. Evite linguagem genérica e promessas exageradas.
5. Defina objetivo e chamada para ação.
6. Adapte o conteúdo ao canal.
7. Submeta a versão final à aprovação humana.

Entregue:
- Objetivo
- Público
- Argumento central
- Texto
- Fontes
- CTA
- Variações de distribuição
```

## 17.3 Lead Generation Agent

``` text
Você é um analista de prospecção B2B.

Identifique organizações compatíveis com o ICP indicado.

Regras:
1. Priorize aderência e evidência, não volume.
2. Registre fontes públicas e data.
3. Não invente contatos ou cargos.
4. Não colete dados pessoais desnecessários.
5. Não envie mensagens.
6. Classifique A, B ou C e justifique.

Entregue:
- Organização
- Segmento
- Evidências de aderência
- Necessidade potencial
- Papel decisor relevante
- Fonte
- Confiança
- Próxima ação sugerida
```

## 17.4 Growth Strategist Agent

``` text
Você é um estrategista de Growth B2B.

Analise objetivo, funil, público e dados disponíveis.

Formule hipóteses testáveis e priorize por:
- Impacto
- Confiança
- Facilidade

Para cada experimento, informe:
- Problema
- Hipótese
- Público
- Canal
- Mudança
- Métrica principal
- Métricas de proteção
- Esforço
- Critério de decisão

Não apresente estimativas como resultados comprovados.
```

------------------------------------------------------------------------

# 18. Critérios de sucesso

A operação estará pronta para avançar quando:

1.  WEMOGA e VUOO estiverem claramente separadas em contexto, ICP,
    campanhas e métricas.
2.  Os agentes conseguirem produzir pesquisas com fontes verificáveis.
3.  O conteúdo respeitar posicionamento e evidências.
4.  Leads forem qualificados com critérios consistentes.
5.  O CRM registrar origem e estágio.
6.  A equipe conseguir revisar e aprovar ações externas.
7.  Os custos de IA forem rastreados.
8.  Os experimentos gerarem decisões documentadas.
9.  Os workflows puderem ser executados novamente sem depender de
    procedimentos manuais não documentados.

------------------------------------------------------------------------

# 19. Decisões recomendadas

  Tema               Decisão inicial
  ------------------ ---------------------------------------
  Marcas             Operações independentes
  Infraestrutura     Compartilhada
  Modelos            Claude + OpenAI
  Skills             Marketing Skills como base
  Agentes iniciais   Research, Content, Leads
  Orquestração       OpenAI Agents SDK + n8n
  Integração         MCP quando necessário
  Banco              PostgreSQL
  CRM                HubSpot, sujeito à avaliação do plano
  Analytics          GA4 + Search Console
  Autonomia          Aprovação humana no MVP
  Prazo              30 dias para MVP
  Consolidação       90 dias

## 19.1 O que não fazer agora

-   Não instalar dezenas de skills sem avaliação.
-   Não construir um framework próprio antes de validar o processo.
-   Não criar um agente monolítico.
-   Não misturar leads e campanhas das marcas.
-   Não automatizar disparos comerciais em massa.
-   Não investir em mídia paga antes de validar mensagem e conversão.
-   Não criar dashboards complexos sem dados confiáveis.
-   Não usar métricas de vaidade como principal critério de sucesso.

------------------------------------------------------------------------

# 20. Próximos passos imediatos

A sequência operacional recomendada é:

1.  Criar o repositório privado `growth-ai`.
2.  Criar `brands/wemoga/` e `brands/vuoo/`.
3.  Documentar posicionamento, ICP, personas e provas de cada marca.
4.  Instalar e revisar as skills prioritárias de Marketing Skills.
5.  Configurar as credenciais Claude e OpenAI.
6.  Implementar Market Research Agent.
7.  Validar o agente com uma pesquisa para cada marca.
8.  Implementar Content Agent e produzir os primeiros conteúdos.
9.  Implementar Lead Generation Agent.
10. Conectar o CRM após validar os critérios de qualificação.

**Primeira entrega operacional:** um relatório de inteligência de
mercado para WEMOGA, outro para VUOO, uma lista revisada de
oportunidades por marca e um primeiro conjunto de conteúdos com
aprovação humana.

------------------------------------------------------------------------

# Referências técnicas

-   Marketing Skills: https://github.com/coreyhaines31/marketingskills
-   Anthropic Skills: https://github.com/anthropics/skills
-   OpenAI Agents SDK: https://github.com/openai/openai-agents-python
-   Model Context Protocol Servers:
    https://github.com/modelcontextprotocol/servers
-   n8n: https://github.com/n8n-io/n8n
-   HubSpot: https://www.hubspot.com/
-   Google Analytics: https://analytics.google.com/
-   Google Search Console: https://search.google.com/search-console/
-   Anthropic API: https://docs.anthropic.com/
-   OpenAI API: https://platform.openai.com/docs/

------------------------------------------------------------------------

**Documento de trabalho.** A arquitetura e as metas devem ser revisadas
após a primeira semana de implantação, quando houver dados sobre ICP,
ferramentas, custos, capacidade operacional e qualidade dos agentes.
