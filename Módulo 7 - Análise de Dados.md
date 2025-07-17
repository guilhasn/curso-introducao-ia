# 🎯 Módulo 7: Análise de Dados Excel com IA Generativa

**Formato:** Sessão prática e demonstrativa  
**Duração:** 45 minutos  
**Público:** Iniciantes sem experiência técnica avançada  
**Foco:** Resultados práticos imediatos

## 🎯 Objetivos do Módulo
Ao final desta sessão, os participantes serão capazes de:

- ✅ Preparar dados Excel para análise com ferramentas de IA
- ✅ Utilizar pelo menos 3 ferramentas de IA generativa para análise de dados
- ✅ Obter insights automáticos dos seus dados em minutos
- ✅ Comparar resultados entre diferentes ferramentas de IA
- ✅ Identificar a melhor ferramenta para cada tipo de análise
- ✅ Usar funcionalidades avançadas como gráficos interativos e código Python

## 📊 Datasets Criados para os Exercícios

### 📈 Dataset 1: Vendas Portugal (1000 registos)
**Ficheiro:** `vendas_portugal_1000.xlsx`

**Descrição:** Dados de vendas de uma empresa portuguesa de material de escritório  
**Colunas:**  
Data, Produto, Categoria, Preço_Unitário, Quantidade, Vendas_Total, Região, Vendedor, Cliente, Desconto, Lucro  
**Características:**
- 41 produtos diferentes (Material Escritório, Tecnologia, Mobiliário, Equipamento)
- 12 regiões portuguesas (Lisboa, Porto, Braga, Coimbra, etc.)
- 20 vendedores com nomes portugueses
- 36 clientes empresariais realistas
- Dados de 2023-2024 com sazonalidade
- Preços realistas em euros
- Anomalias interessantes para descobrir

### 👥 Dataset 2: Recursos Humanos (1000 registos)
**Ficheiro:** `recursos_humanos_1000.xlsx`

**Descrição:** Dados de funcionários de uma empresa portuguesa  
**Colunas:**  
ID_Funcionário, Nome, Departamento, Cargo, Salário, Idade, Antiguidade, Localização, Género, Avaliação_Performance, Formação_Horas, Ausências_Dias  
**Características:**
- 6 departamentos (IT, Vendas, Marketing, Finanças, RH, Operações)
- Hierarquia realista de cargos por departamento
- Salários realistas portugueses (€15k-€99k)
- 20 cidades portuguesas
- Correlações realistas entre idade, cargo e salário
- Métricas de performance e formação

## 📋 Preparação dos Dados Excel

### 🔧 Boas Práticas do OpenAI para ChatGPT

#### ✅ FAZER:
- Incluir cabeçalhos descritivos na primeira linha
- Usar linguagem simples nos cabeçalhos, evitar siglas e jargão
- Usar uma linha por registo
- Dados organizados em formato tabular
- Ficheiros até 512MB (CSV até 50MB)

#### ❌ NÃO FAZER:
- Múltiplas seções/tabelas numa só folha
- Linhas ou colunas vazias
- Imagens com informação crítica
- Formatação excessiva ou células mescladas

### 📊 Tipos de Ficheiro Suportados:
- Excel: `.xls` / `.xlsx`
- CSV: `.csv` (recomendado para datasets grandes)
- PDF: `.pdf`
- JSON: `.json`
- Integração: Google Drive, OneDrive, SharePoint

### 🛠️ Métodos de Carregamento:

**Método 1: Upload Direto (Recomendado)**
- Descarregar dataset fornecido
- Fazer upload diretamente na ferramenta de IA
- Aguardar processamento automático
- Verificar tabela interativa gerada

**Método 2: Cópia e Colagem**
- Abrir Excel com dados
- Selecionar dados (incluindo cabeçalhos)
- Copiar (Ctrl+C) e colar no chat
- Contextualizar os dados

**Método 3: Conexão Cloud**
- Guardar ficheiro no Google Drive/OneDrive
- Partilhar link ou conectar diretamente
- Análise em tempo real

## 🛠️ Comparação Detalhada das Ferramentas

### 🤖 ChatGPT (OpenAI) - ⭐⭐⭐⭐⭐  
**Acesso:** https://chat.openai.com/

**Pontos Fortes:**
- Análise de Dados Avançada: Usa pandas e matplotlib automaticamente
- Gráficos Interativos: Barras, pizza, scatter e linha
- Código Python: Mostra código gerado, permite cópia
- Tabelas Interativas: Navegação pelos dados completa
- Uploads Múltiplos: Até 10 ficheiros por conversa

**Funcionalidades Únicas:**
- "View Analysis" - Mostra código Python usado
- "Always show details" - Análise automática visível
- "Switch Interactive/Static" - Alterna entre tipos de gráfico
- Reasoning Models - Regressões, simulações, métricas complexas

**Limitações:**
- Versão gratuita limitada (uploads mensais)
- Pode perder contexto em conversas muito longas
- Dependente da qualidade do prompt

**Melhor para:** Análise exploratória completa, visualizações profissionais

### 🧠 Claude (Anthropic) - ⭐⭐⭐⭐⭐  
**Acesso:** https://claude.ai/

**Pontos Fortes:**
- Análise Profunda: Respostas estruturadas e detalhadas
- Ficheiros Grandes: Até 5MB por ficheiro
- Contexto Extenso: Mantém contexto em conversas longas
- Relatórios Estruturados: Formato profissional automático

**Limitações:**
- Menos visual que ChatGPT
- Sem gráficos interativos nativos
- Disponibilidade regional limitada

**Melhor para:** Análise detalhada, relatórios executivos, insights complexos

### ⚡ Gemini (Google) - ⭐⭐⭐⭐  
**Acesso:** https://gemini.google.com/

**Pontos Fortes:**
- Integração Google: Sheets, Drive, Workspace
- Análise Visual: Bom para gráficos e imagens
- Acesso Gratuito: Funcionalidades robustas sem pagamento
- Multimodal: Texto, imagem, vídeo

**Limitações:**
- Interface menos estável
- Respostas menos consistentes
- Funcionalidades em desenvolvimento

**Melhor para:** Integração com Google Workspace, análise rápida

### 🔍 Perplexity - ⭐⭐⭐  
**Acesso:** https://www.perplexity.ai/

**Pontos Fortes:**
- Contextualização: Liga dados a informações externas
- Fontes Citadas: Referências automáticas
- Pesquisa Integrada: Combina análise com web search

**Limitações:**
- Foco mais em pesquisa que análise
- Limitações na versão gratuita
- Menos especializado em dados

**Melhor para:** Contextualizar dados, benchmarking, pesquisa

### 🚀 Grok (X) - ⭐⭐  
**Acesso:** https://x.com/ (X Premium necessário)

**Pontos Fortes:**
- Linguagem Casual: Comunicação direta
- Dados Tempo Real: Integração com X/Twitter
- Análise Social: Tendências e sentimentos

**Limitações:**
- Pago: Requer X Premium (€8/mês)
- Menos maduro para análise de dados
- Capacidades limitadas

**Melhor para:** Análise de tendências sociais, dados de redes sociais

### 🔬 DeepSeek - ⭐⭐⭐  
**Acesso:** https://chat.deepseek.com/

**Pontos Fortes:**
- Gratuito: Sem limitações de uso
- Análise Técnica: Foco em cálculos complexos
- Open Source: Transparência no modelo

**Limitações:**
- Menos conhecido/testado
- Comunidade menor
- Interface básica

**Melhor para:** Análise técnica, cálculos estatísticos, prototipagem

## 📊 Exemplos Práticos com Datasets Reais

### 🎯 Exemplo 1: Análise de Vendas (Dataset Vendas)
**Contexto:** Análise de performance de vendas para reunião executiva

**Prompt Optimizado:**
```txt
Sou director comercial e preciso analisar a performance de vendas da minha empresa para uma reunião executiva. Analisa estes dados e responde:

1. Quais são os TOP 5 produtos mais vendidos?
2. Que região tem melhor performance em vendas totais?
3. Qual vendedor tem melhor performance?
4. Existe sazonalidade nas vendas ao longo do ano?
5. Qual é a margem de lucro média por categoria?
6. Cria um gráfico que mostre a evolução das vendas mensais
7. Identifica 3 oportunidades de crescimento
8. Sugere 2 ações concretas para aumentar vendas
````

### 🎯 Exemplo 2: Análise de RH (Dataset Recursos Humanos)

**Contexto:** Análise de capital humano para estratégia de RH

**Prompt Optimizado:**

```txt
Sou director de RH e preciso analisar a situação dos nossos recursos humanos. Com base nestes dados, preciso de:

1. Distribuição de funcionários por departamento
2. Análise salarial: médias por departamento e equidade
3. Relação entre idade, antiguidade e salário
4. Performance vs investimento em formação
5. Identificar padrões de absentismo
6. Análise de equidade de género por departamento
7. Cria um dashboard com os KPIs principais
8. Identifica 3 problemas críticos de RH
9. Sugere 3 ações para melhorar satisfação
```

## ✏️ Exercício Prático Completo (20 minutos)

### 🎯 Exercício 1: Análise de Vendas Multi-Ferramenta

**Objetivo:** Comparar capacidades de análise entre ferramentas

**Dataset:** Vendas Portugal (1000 registos)

**Divisão de Grupos:**

* Grupo 1: ChatGPT + Claude
* Grupo 2: Gemini + Perplexity
* Grupo 3: DeepSeek + ChatGPT

**Perguntas Padronizadas:**

* "Qual categoria de produto tem maior lucro?"
* "Que região tem crescimento mais consistente?"
* "Identifica o vendedor com melhor ROI"
* "Sugere estratégia para aumentar vendas 15%"
* "Cria visualização para apresentação executiva"

### 🎯 Exercício 2: Análise de RH Individual

**Objetivo:** Prática individual com dataset complexo

**Dataset:** Recursos Humanos (1000 registos)

**Tarefa:** Cada participante escolhe uma ferramenta e responde:

* Análise Salarial: Existe equidade salarial na empresa?
* Performance: Que fatores influenciam a avaliação?
* Retenção: Perfil de funcionários com maior risco de saída?
* Desenvolvimento: Como otimizar investimento em formação?
* Dashboard: Criar painel executivo de RH

## 📝 Template de Prompt Otimizado

```txt
CONTEXTO: [Sou gestor de uma empresa portuguesa]
OBJETIVO: [Preciso analisar performance e tomar decisões estratégicas]
DADOS: [Anexo ficheiro Excel com 1000 registos]

ANÁLISE SOLICITADA:
1. [Pergunta específica com contexto]
2. [Pergunta específica com contexto]
3. [Pergunta específica com contexto]
4. [Pergunta específica com contexto]
5. [Pergunta específica com contexto]

FORMATO DE RESPOSTA:
- Executivo e prático
- Números específicos e percentagens
- Insights acionáveis
- Visualização recomendada
- Próximos passos sugeridos

PRAZO: [Preciso para reunião amanhã]
```

## 🏆 Critérios de Avaliação

* Precisão: Respostas corretas e consistentes
* Usabilidade: Facilidade de uso da ferramenta
* Visualização: Qualidade dos gráficos gerados
* Insights: Valor das descobertas
* Velocidade: Tempo para obter resultados

## 📖 Recursos Complementares

### 🔗 Links Essenciais:

* [ChatGPT](https://chat.openai.com/)
* [Claude](https://claude.ai/)
* [Gemini](https://gemini.google.com/)
* [Perplexity](https://www.perplexity.ai/)
* [DeepSeek](https://chat.deepseek.com/)
* [Guia OpenAI: Data Analysis](https://help.openai.com/en/articles/8437071-data-analysis-with-chatgpt)

### 💡 Prompts Testados nos Datasets:

**Para Vendas:**

> "Analisa as vendas como um consultor McKinsey. Identifica os 3 drivers principais de crescimento e sugere estratégia para aumentar receita 20% no próximo trimestre."

**Para RH:**

> "Sou CHRO e preciso apresentar análise de capital humano ao CEO. Cria executive summary com 5 KPIs críticos, 3 riscos identificados e 2 recomendações estratégicas."

**Para Visualizações:**

> "Cria dashboard executivo interativo com os 4 gráficos mais relevantes. Explica que história cada gráfico conta e como usar em apresentação."

```
```
