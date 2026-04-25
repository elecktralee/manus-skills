# 🎓 Academic & Research AI Skills Suite (v2.0)

Este repositório apresenta uma coleção de Skills especializadas para o Manus, meticulosamente projetadas para otimizar e aprimorar o fluxo de trabalho acadêmico. Cada skill foi desenvolvida com foco no rigor científico, na precisão metodológica e na eficiência operacional, fornecendo suporte contextualizado e acionável em todas as etapas da pesquisa.

---

## 📑 Índice
- [Academic Data Visualizer](#-academic-data-visualizer-academic-data-visualizer)
- [Academic Document Oracle](#-academic-document-oracle-academic-document-oracle)
- [Academic Methodology Builder](#-academic-methodology-builder-academic-methodology-builder)
- [Academic Network Intelligence](#-academic-network-intelligence-academic-network-intelligence)
- [Academic Researcher](#-academic-researcher-academic-researcher)
- [Academic Theory Analyzer](#-academic-theory-analyzer-academic-theory-analyzer)
- [Scite AI Assistant](#-scite-ai-assistant-scite-ai-assistant)
- [Scientific Writing Reviewer](#-scientific-writing-reviewer-scientific-writing-reviewer)
- [Theory Mapper](#-theory-mapper-theory-mapper)
- [Ethics Committee Assistant](#-ethics-committee-assistant-ethics-committee-assistant)
- [Como Usar](#-como-usar)
- [Diferenciais Técnicos](#-diferenciais-técnicos)
- [Licença](#-licença)

---

## 📊 Academic Data Visualizer (academic-data-visualizer)
Descrição: Esta skill converte dados brutos (CSV, Excel) em visualizações gráficas de alta qualidade, adequadas para publicações acadêmicas, com ênfase em clareza, precisão e personalização estética.

Funcionalidades e Nuances Técnicas: Esta skill opera como um orquestrador de bibliotecas de visualização de dados em Python (matplotlib, seaborn), gerando código específico para cada solicitação. Sua inteligência reside na interpretação semântica do pedido do usuário para selecionar o tipo de gráfico mais apropriado e configurar seus parâmetros de forma academicamente rigorosa.

•Importação e Pré-análise de Dados: Ao receber um comando para importar dados (ex: "Importe o arquivo dados_experimento.csv e mostre as primeiras 5 linhas e um resumo estatístico das variáveis numéricas."), a skill executa um script Python que utiliza pandas para carregar o arquivo. Ela então infere os tipos de dados das colunas e gera um resumo estatístico para variáveis numéricas. A nuance aqui é a capacidade de identificar automaticamente a estrutura do dado e sugerir a melhor abordagem para a visualização subsequente.
•Geração de Gráficos Acadêmicos: Para prompts como "Gere um boxplot do desempenho (variável escore) por grupo (variável condicao), com títulos e rótulos de eixo apropriados.", a skill constrói dinamicamente um script Python. A escolha do tipo de gráfico é guiada por heurísticas baseadas na natureza das variáveis (categóricas vs. contínuas) e no objetivo da visualização (distribuição, relação, comparação).
•Personalização de Visualizações: Solicitações como "Personalize o gráfico de dispersão, adicionando um título 'Relação entre Variável A e Variável B' e alterando a cor dos pontos para azul escuro." são traduzidas em comandos de matplotlib ou seaborn para ajustar elementos visuais. A especificidade reside na manutenção da consistência visual e na aderência a padrões estéticos valorizados em publicações científicas.
•Exportação em Alta Qualidade: Ao receber um prompt como "Exporte o gráfico para um arquivo PNG com 300 DPI.", a skill utiliza parâmetros de resolução e formato que garantem a integridade visual para submissão em periódicos.

---

## 🔮 Academic Document Oracle (academic-document-oracle)
Descrição: Um sistema de Geração Aumentada por Recuperação (RAG) rigoroso, que responde a perguntas exclusivamente com base em documentos fornecidos, minimizando alucinações e gerando resumos com citações ABNT.

Funcionalidades e Nuances Técnicas: O academic-document-oracle opera sob um princípio de restrição contextual rigorosa. A chave para sua eficácia é a proibição explícita de busca externa a menos que seja orquestrada por skills específicas.

•Respostas Baseadas em Documentos (RAG Rigoroso): Quando um prompt como "Qual a principal hipótese apresentada no documento?" é recebido, a skill realiza uma busca semântica dentro do corpus carregado. Se a informação não estiver presente, a skill reporta a ausência, evitando a invenção de dados.
•Geração Automática de Resumos e Tópicos Principais: Para prompts como "Resuma o capítulo 3 e liste seus tópicos principais.", a skill emprega técnicas de sumarização que priorizam conceitos-chave, garantindo que o resumo não introduza informações externas ao texto-fonte.
•Citações ABNT com Notas de Rodapé: Para cada trecho de informação extraído, a skill gera uma nota de rodapé formatada em ABNT, indicando a origem exata (página, parágrafo) dentro do documento. A precisão da citação é fundamental para a verificabilidade e integridade acadêmica.

---

## 🧪 Academic Methodology Builder (academic-methodology-builder)
Descrição: Auxilia na estruturação e descrição da seção de Metodologia, garantindo rigor, reprodutibilidade e conformidade com as normas científicas.

Funcionalidades e Nuances Técnicas: Esta skill atua como um engenheiro de texto para a seção metodológica, baseando-se em templates estruturais e diretrizes de boas práticas de pesquisa.

•Estruturação do Desenho Experimental: Para prompts como "Estruture a seção de desenho experimental para um estudo longitudinal, incluindo critérios de inclusão e exclusão.", a skill gera um esqueleto textual que inclui subseções para tipo de estudo, população, amostra e delineamento.
•Detalhamento de Instrumentos: Ao receber "Descreva as propriedades psicométricas da Escala X, incluindo sua validação para a população brasileira.", a skill gera um parágrafo detalhado com dados de validade e fidedignidade, essenciais para pesquisas empíricas.
•Descrição de Procedimentos: Prompts como "Descreva os procedimentos de coleta de dados sequenciais para este experimento." resultam em uma sequência lógica de passos que permite a replicação do estudo por outros pesquisadores.

---

## 🕸️ Academic Network Intelligence (academic-network-intelligence)
Descrição: Ferramenta para gestão e análise de literatura, permitindo mapeamento visual de pesquisa, descoberta de novos estudos e integração com o Zotero.

Funcionalidades e Nuances Técnicas: Esta skill explora as interconexões da literatura científica através da análise de redes de citação e co-citação.

•Mapeamento Visual de Pesquisa: Para prompts como "Gere um mapa visual da rede de citações para o artigo seminal da área X.", a skill identifica artigos centrais e clusters temáticos, revelando a estrutura subjacente da pesquisa.
•Descoberta de Novos Estudos (Seed Paper Analysis): Ao receber "Sugira artigos similares ao seed paper fornecido.", a skill utiliza algoritmos de similaridade e de rede para identificar literatura relevante que pode não ser óbvia em buscas tradicionais.
•Integração com Zotero: Para prompts como "Exporte a coleção de referências para o formato BibTeX.", a skill gera arquivos compatíveis com gerenciadores bibliográficos, facilitando o fluxo de trabalho do pesquisador.

---

## 🔎 Academic Researcher (academic-researcher)
Descrição: Motor de busca especializado em bases científicas (PubMed, SciELO, Scopus, etc.), capaz de localizar e filtrar literatura de alto impacto.

Funcionalidades e Nuances Técnicas: O academic-researcher incorpora heurísticas de pesquisa avançada, adaptando a sintaxe de busca para cada plataforma específica (ex: operadores booleanos, filtros de data e tipo de documento).

•Busca Multibase: Traduz consultas complexas em sintaxes otimizadas para bases como Google Scholar e Web of Science, maximizando a relevância dos resultados.
•Filtragem de Qualidade: Aplica critérios rigorosos, priorizando artigos revisados por pares e periódicos de alto impacto. Fornece referências completas em ABNT/APA com links DOI.

---

## 🧠 Academic Theory Analyzer (academic-theory-analyzer)
Descrição: Realiza análise acadêmica e mapeamento teórico, relacionando hipóteses de pesquisa com o corpo de evidências científicas existentes.

Funcionalidades e Nuances Técnicas: Esta skill atua como um meta-analista, orquestrando as capacidades de busca e mapeamento para construir uma compreensão profunda da estrutura conceitual de um campo.

•Relação entre Hipóteses e Evidências: Ao receber "Relacione as hipóteses do meu projeto com as evidências científicas mais recentes da área.", a skill realiza uma análise comparativa, identificando convergências e lacunas que fortalecem a fundamentação teórica.

---

## 🔍 Scite AI Assistant (scite-ai-assistant)
Descrição: Especializada em análise de citações contextuais (Smart Citations), classificando estudos como apoiadores, contraditórios ou mencionadores.

Funcionalidades e Nuances Técnicas: Simula a funcionalidade do Scite.ai para avaliar a natureza da interação entre artigos, indo além da mera contagem de citações.

•Smart Citations: Analisa se um trabalho posterior fornece evidências que apoiam ou contradizem o artigo original.
•Verificação de Referências: Avalia a validade de uma lista de referências, alertando sobre possíveis retratações ou controvérsias significativas na literatura.

---

## ✍️ Scientific Writing Reviewer (scientific-writing-reviewer)
Descrição: Revisa textos acadêmicos para emular o estilo pré-2020, eliminando maneirismos de IA e focando em clareza, rigor e variação sintática (burstiness).

Funcionalidades e Nuances Técnicas:
•Anti-Maneirismos de IA: Remove termos genéricos e estruturas repetitivas típicas de modelos de linguagem (ex: "crucial", "mergulhe conosco", listas padronizadas).
•Variação Rítmica: Ajusta o comprimento e a complexidade das frases para garantir uma leitura fluida e autêntica, característica da prosa humana rigorosa.
•Especificidade: Substitui termos vagos por exemplos concretos e exige fundamentação para afirmações amplas.
---

## 🗺️ Theory Mapper (theory-mapper)
Descrição: Mapeia a evolução temporal de conceitos e teorias, identificando pontos de inflexão e o histórico de debates acadêmicos.

Funcionalidades e Nuances Técnicas:
•Mapeamento Temporal: Organiza a literatura cronologicamente para visualizar a genealogia de uma ideia.
•Identificação de Controvérsias: Busca ativamente por estudos de replicação e falhas de replicação, destacando áreas de desacordo científico.

---

## ⚖️ Ethics Committee Assistant (ethics-committee-assistant)
Descrição: Auxilia na elaboração de documentos éticos (TCLE, Folha de Rosto) conforme as regulamentações vigentes (CNS/Plataforma Brasil).

Funcionalidades e Nuances Técnicas:
•Geração de TCLE: Cria rascunhos com linguagem adaptada ao público-alvo, garantindo que todos os requisitos éticos (riscos, benefícios, confidencialidade) sejam abordados de forma clara.
---

## 🚀 Como Usar
- **Instalação:** importe os arquivos `.skill` para o ambiente Manus.  
- **Invocação:** use comandos diretos como `Use o academic-researcher para buscar...` ou aplique o `scientific-writing-reviewer` para revisar textos.

---

## 📌 Diferenciais Técnicos
- **Anti-Alucinação:** foco em RAG rigoroso e validação cruzada.  
- **Rigor Normativo:** suporte nativo para ABNT, APA e regulamentações éticas.  
- **Combate a Vícios de IA:** filtros estilísticos para garantir voz acadêmica autêntica.  

---

## 📜 Licença
Este projeto está licenciado sob a [Apache License 2.0](LICENSE).  
Qualquer pessoa pode usar, copiar, modificar e distribuir os arquivos, inclusive em projetos comerciais, desde que mantenha os créditos originais e respeite os termos da licença.
