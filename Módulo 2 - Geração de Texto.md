# 📘 Módulo 2: Geração de Texto com Inteligência Artificial

## 1. Objetivos do Módulo
- Compreender os fundamentos e aplicações da IA generativa.
- Aprender boas práticas avançadas de **prompt engineering**.
- Caracterizar e utilizar ferramentas líderes (ChatGPT, Gemini, Claude, Jasper, Writesonic, etc.).
- Implementar padrões de segurança, ética e governação (ISO 27001, DAMA‑DMBOK, OWASP).

---

## 2. Fundamentos da IA Generativa

1. **Definição**: Modelos LLM (como GPT‑4, Claude, Gemini) geram texto prevendo a próxima palavra com base em grandes volumes de dados.  
2. **Aplicações típicas**: escrita de e‑mails, artigos, posts, relatórios, propostas, resumos automáticos, apoio à decisão.  
3. **Limitações**: alucinações (respostas erradas com aparente confiança), enviesamentos nos dados, dependência do prompt, riscos de segurança (prompt injection).

---

## 3. Engenharia de Prompts (Prompt Engineering)

### 3.1 Boas Práticas Fundamentais
- **Clareza e especificidade**: indicar o papel do modelo, contexto, objetivo, tom e limites.  
- **Role prompting**: “Assume que és um...”. Define uma persona clara.  
- **Chain-of-Thought (CoT)**: pedir ao modelo que explique o raciocínio passo a passo.  
- **Few-shot prompting**: incluir exemplos no prompt para orientar a estrutura ou estilo da resposta.  
- **Iteração**: ajustar os prompts com base nos resultados obtidos.

### 3.2 Técnicas Avançadas
- **Zero-shot vs Few-shot**: usar nenhum ou poucos exemplos para orientar a geração.  
- **Self-consistency**: gerar múltiplas versões e escolher a mais robusta.  
- **Meta-prompting**: pedir à IA que ajude a melhorar o próprio prompt.  
- **RAG (Retrieval-Augmented Generation)**: aceder a bases de dados externas para fundamentar melhor as respostas.




# Como Criar um Bom Prompt para o ChatGPT: Guia Simples + Dica Oficial da OpenAI

*Fonte: [André Rebello](https://andrerebello.com.br/2025/06/04/como-criar-um-bom-prompt-para-o-chatgpt-guia-simples-dica-oficial-da-openai/)*

A inteligência artificial está cada vez mais presente no nosso dia a dia, seja para agilizar o trabalho, criar conteúdos ou solucionar dúvidas. E uma das ferramentas mais famosas atualmente é o **ChatGPT**.

Se você quer aproveitar melhor essa tecnologia, precisa dominar um conceito básico, mas muito poderoso: **prompt**.

## O que é um Prompt?

Um **prompt** é **a pergunta ou comando que você escreve para conversar com o ChatGPT**.  
Pense assim: o prompt é como se fosse a "instrução" que você dá para a inteligência artificial trabalhar.

**Quanto mais claro e bem estruturado for o seu prompt, melhor será a resposta que você receberá.**

---

## O que é o ChatGPT (em poucas palavras)?

O ChatGPT é uma ferramenta criada pela OpenAI que simula conversas humanas. Ele entende o que você escreve e gera respostas inteligentes para tarefas como:

- Criar textos
- Responder dúvidas
- Dar sugestões
- Resolver problemas de diversas áreas

Mas tudo começa com um bom prompt!

---

## A Estrutura de um Bom Prompt

Um prompt eficaz normalmente segue este esquema simples:

1. **Objetivo claro** → O que você quer que o ChatGPT faça?
2. **Contexto** → Para quem é? Qual a situação?
3. **Detalhes específicos** → Informações que a IA deve considerar.
4. **Formato esperado** → Como você gostaria de receber a resposta (texto, lista, tabela, passo a passo).


Uma **dica oficial do presidente da [OpenAI](https://openai.com/)**, Greg Brockman, publicada na [Exame](https://exame.com/inteligencia-artificial/prompt-perfeito-presidente-da-openai-ensina-como-extrair-o-maximo-do-chatgpt/), é adicionar no seu prompt o pedido:

> **"Pense passo a passo."**

Essa frase mágica faz o ChatGPT **raciocinar com mais calma** e gerar respostas **muito mais organizadas e profundas**.

---

## Exemplo Prático: Criando um Prompt Passo a Passo

Imagine que você trabalha com marketing e quer gerar **ideias de posts para Instagram sobre cuidados com a pele**.

### 🔹 Passo 1 – Defina o objetivo:

> Quero ideias de posts para Instagram sobre cuidados com a pele.

### 🔹 Passo 2 – Dê o contexto:

> Trabalho com uma marca de cosméticos para mulheres de 25 a 45 anos, focada em saúde e bem-estar.

### 🔹 Passo 3 – Adicione detalhes:

> Quero posts com linguagem leve, dicas práticas e sugestões de legenda.

### 🔹 Passo 4 – Formato desejado:

> Preciso de 5 ideias, cada uma com título, texto e sugestão de imagem.

### 🔹 Passo 5 – Aplique a dica "pense passo a passo":

> No final do prompt, adicione: "Pense passo a passo".

---

## ✅ Prompt final para enviar ao ChatGPT:

Crie 5 ideias de posts para Instagram sobre cuidados com a pele. A marca é focada em mulheres entre 25 e 45 anos, com interesse em saúde e bem-estar. O tom deve ser leve, prático e incluir dicas aplicáveis ao dia a dia. Para cada ideia, forneça título, texto e sugestão de imagem. Pense passo a passo.


**Resultado:**  
Você receberá respostas muito mais bem pensadas, organizadas e úteis!

---









---

## Dicas Extras para Criar Prompts Ainda Melhores

- **Seja claro:** Especifique o que você quer.
- **Dê exemplos:** Se quiser algo em um estilo específico, diga.
- **Peça revisões:** Se o primeiro resultado não ficou perfeito, refine o prompt e tente novamente.
- **Use "Pense passo a passo":** Isso incentiva o ChatGPT a estruturar melhor o raciocínio.

---

## Conclusão

Criar um bom prompt é como fazer o pedido certo a um chefe de cozinha: quanto mais claro você for sobre o que deseja, melhor será o prato servido!

Aproveite a dica dos especialistas: peça para o ChatGPT **"pensar passo a passo"** e veja suas respostas subirem de nível!






---

## 4. Fluxo de Trabalho Recomendado

1. Definir o objetivo (tipo de texto, público-alvo, contexto).  
2. Selecionar a ferramenta mais adequada (ChatGPT, Claude, Gemini, etc.).  
3. Construir o prompt com as melhores práticas de clareza, estrutura e persona.  
4. Executar o prompt e analisar a resposta gerada.  
5. Iterar, reformular ou afinar conforme necessário.  
6. Validar com revisão humana: verificar factualidade, tom e formato.  
7. Documentar os prompts eficazes para uso repetido e institucionalização.

---

## 5. Ferramentas Recomendadas (2025)

- **ChatGPT (OpenAI)**: altamente versátil para criação de conteúdo, resumos, brainstormings, emails, etc.  
- **Gemini (Google)**: forte integração com Gmail, Docs e outras apps Google.  
- **Claude (Anthropic)**: excelente para raciocínio complexo, documentos longos e revisões.  
- **Jasper**: orientado para marketing, geração de conteúdos SEO e copywriting.  
- **Writesonic e Copy.ai**: especializados em textos comerciais, anúncios e landing pages.

---

## 6. Exercícios Práticos

### 6.1 E‑mail Institucional
```text
Tu és gestor municipal. Gera um e‑mail a um cidadão para agradecer feedback após intervenção.
Tom: formal, até 150 palavras. Incluir convite para reunião.
```

### 6.2 Resumo Estratégico
```text
Resume o relatório sobre inovação digital em 5 bullet points: desafios, soluções e impacto municipal.
```

### 6.3 Chain-of-Thought
```text
Tens três projetos com dados A, B, C. Avalia e prioriza conforme impacto, custo, alinhamento. Explica passo a passo.
```

### 6.4 Integração com RAG
```text
Implementa um sistema baseado em RAG que aceda a documentos municipais e permita responder a perguntas sobre processos internos.
```

---

## 7. Segurança, Ética e Governação

- **Segurança da informação**: não inserir dados pessoais ou confidenciais nos prompts.  
- **Proteção contra prompt injection**: sanitização de entrada e utilização de guardrails.  
- **Governança**: criar políticas internas sobre uso de IA (baseadas na ISO 27001, DAMA-DMBOK).  
- **Mitigação de viés**: revisão humana, uso de fontes diversas e teste de neutralidade nos outputs.  
- **Transparência**: comunicar ao público sempre que conteúdos forem assistidos ou gerados por IA.

---

## 8. Recursos Recomendados

- [Guia de Prompt Engineering da OpenAI](https://platform.openai.com/docs/guides/gpt-best-practices)  
- [Lakera AI – Guia Prático](https://www.lakera.ai/blog/prompt-engineering-guide)  
- [Tom’s Guide – Dicas Profissionais](https://www.tomsguide.com/ai/i-test-chatgpt-for-a-living-7-secrets-to-instantly-up-your-prompt-game)  
- [ArXiv – Catálogo de Técnicas](https://arxiv.org/abs/2302.11382)  
- [Google Cloud – Aplicações RAG](https://cloud.google.com/ai/docs/rag-overview)

---

## 9. Quadro-Resumo

| Etapa               | Ação Recomendável                                                           |
|---------------------|-----------------------------------------------------------------------------|
| Objetivo            | Definir claramente o tipo de conteúdo e o público-alvo                     |
| Ferramenta          | Selecionar a IA mais adequada ao tipo de tarefa                            |
| Prompt              | Usar persona, contexto, formato, tom e limite de palavras                  |
| Técnicas            | Aplicar Role Prompting, CoT, Few-shot, Meta-prompting                      |
| Validação           | Rever sempre os outputs com espírito crítico e técnico                     |
| Documentação        | Guardar e refinar prompts eficazes como boas práticas internas             |

---

## 10. Conclusão

Este módulo fornece aos formandos:

- Competência técnica na utilização de ferramentas de geração de texto com IA.  
- Capacidade de desenhar prompts eficazes, éticos e ajustados ao contexto.  
- Conhecimento prático das ferramentas mais relevantes para o setor público e empresarial.  
- Instrumentos para a integração responsável e segura da IA na produção de conteúdos e na administração digital.








### 🎯 Casos de Uso

1. **Writing & Conteúdo**  
   Produção de artigos, guias, posts sociais, emails, descrições de produto e scripts :contentReference[oaicite:7]{index=7}.

2. **Marketing & Vendas**  
   Geração de copy otimizado para conversão, SEO e materiais promocionais :contentReference[oaicite:8]{index=8}.

3. **Educação & Investigação**  
   Resumos acadêmicos, planos de aula, ensaios e revisão de literatura :contentReference[oaicite:9]{index=9}.

4. **Empreendedorismo & PMEs**  
   Criação de conteúdos para websites, newsletters, relatórios e suporte ao cliente :contentReference[oaicite:10]{index=10}.

5. **Produtividade Profissional**  
   Automatização de emails, resumos de reuniões, relatórios e comunicações bilingues :contentReference[oaicite:11]{index=11}.

6. **Uso Pessoal**  
   Planeamento, escrita criativa, receitas, eventos e suportes de hobbies :contentReference[oaicite:12]{index=12}.

---

### 🔍 Como Escolher a Ferramenta Adequada

- **Tipo de texto**: marketing, longo-formato, académico, criativo, resumo.
- **Precisão linguística**: suporte multilingue, estilo, plágio.
- **Integração & Interface**: API, templates, interface intuitiva.
- **Segurança de dados**: essencial em contexto público.
- **Escalabilidade e custo** :contentReference[oaicite:13]{index=13}.

---

### 📈 Tendências em 2025

- IA capaz de personalização contextual.
- Integração multimodal: texto, imagem, vídeo e áudio.
- Ferramentas interativas: redline, rastreio iterativo, debugging de prompt.
- Preocupação ética: deteção de vieses, transparência, confidencialidade :contentReference[oaicite:14]{index=14}.

---

### ✍️ Exemplos de Prompt

Escreve um post de blog (500‑600 palavras) sobre transformação digital no setor público, dirigido a gestores municipais. Tom: profissional, inspirador, com 3 tópicos principais e CTA no final.





## 🧪 Exercício 1 – Escrever um E-mail com o ChatGPT

### 🔹 Passos:
1. Acede a [chat.openai.com](https://chat.openai.com/) e inicia sessão
2. Escreve no campo de mensagem:

   ```
   "És um assistente de apoio ao cliente da empresa XYZ. Queres pedir feedback a um cliente após uma interação recente. Escreve um e-mail cordial a solicitar essa opinião."
   ```

3. Lê a resposta, copia o texto gerado e adapta-o, se necessário

### 🧩 Experimenta também:

- Pedir uma reunião com um professor
- Fazer o seguimento de uma candidatura de emprego
- Criar um convite para um evento da empresa
- Enviar uma mensagem a relembrar um prazo

> 📝 Nota: avalia sempre o conteúdo gerado antes de o utilizar. Verifica gramática, tom e exatidão.

---

## 🧪 Exercício 2 – Conversão de Unidades com o ChatGPT

### 🔹 Exemplo:

> "Tenho uma receita com 500g de farinha, mas a balança mede em onças. Converte os 500g para onças."

### ✍️ Tenta também:
- Calcular a área de um triângulo com base e altura
- Calcular a média de cinco números
- Calcular juros simples para um capital de 1.000€, taxa de 4% e prazo de 1 ano

---

## 🧪 [Opcional] Exercício 3 – Resumo de Texto com Gemini

1. Acede a [gemini.google.com](https://gemini.google.com/?hl=pt-PT) e entra com uma conta Google
2. Introduz um pedido, como:

   ```
   "Resume o artigo 'O assistente IBM watsonx transforma conteúdos em respostas conversacionais com IA generativa'."
   ```

3. Compara os rascunhos gerados, escolhe o melhor e copia o resultado

> 💡 Usa Gemini para resumir artigos, blogs, relatórios ou atas de reuniões.

---

