# 🧪 Ficha Prática – Engenharia de Prompt Avançada

## 🎯 Objetivos da sessão

- Utilizar técnicas avançadas de engenharia de prompt
- Trabalhar com estruturação de respostas, formatação e estilo
- Criar prompts compostos, iterativos e multiagente
- Compreender o impacto de temperatura, contexto e exemplos no output

---

## 🧠 Introdução

À medida que ganhamos confiança na utilização de ferramentas como ChatGPT, Gemini ou DeepSeek, torna-se essencial dominar técnicas de prompting mais sofisticadas, para obter resultados mais precisos, formatados e úteis para contextos reais.

Engenharia de prompt avançada permite, por exemplo:
- Gerar relatórios estruturados
- Produzir texto com tom ou estilo específico
- Executar tarefas com vários passos
- Simular múltiplos pontos de vista

---

## 🧩 Conceitos Avançados

| Técnica                        | Descrição                                                                 |
|-------------------------------|--------------------------------------------------------------------------|
| **Zero-shot / Few-shot**      | Pedir a resposta sem exemplo ou com poucos exemplos                       |
| **Role prompting**            | Indicar um papel claro à IA (ex: "És um jurista especialista em RGPD…") |
| **Output formatting**         | Pedir a resposta em formato lista, tabela, JSON, Markdown, etc.          |
| **Multi-turn prompting**      | Prompts sequenciais para aprofundar ou corrigir                          |
| **Simulação multiagente**     | Pedir à IA para representar duas ou mais perspetivas distintas            |
| **Temperatura e precisão**    | Alterar o nível de criatividade/predictabilidade (via interface pro)     |

---

## 🧪 Exercício 1 – Prompt com Formato de Saída Específico

### 🎯 Objetivo:
Gerar um conteúdo com estrutura clara.

Prompt exemplo:
```
"Age como técnico de RH. Cria uma lista de verificação (checklist) em formato Markdown com 5 passos essenciais para conduzir uma entrevista de recrutamento eficaz."
```

> 💡 Experimenta pedir a resposta em formato JSON, tabela, bullet points ou mesmo slide.

---

## 🧪 Exercício 2 – Few-shot Prompting

### 🎯 Objetivo:
Mostrar à IA exemplos para ela seguir o estilo ou padrão.

Prompt exemplo:
```
"Aqui estão dois exemplos de respostas simpáticas a e-mails de reclamação:
1. 'Agradecemos o seu contacto…'
2. 'Compreendemos a sua preocupação…'
Agora escreve uma resposta semelhante para o seguinte caso: o cliente está descontente com o tempo de espera na linha de apoio."
```

> ✅ Adicionar exemplos bem construídos é uma das melhores práticas para controlo de estilo.

---

## 🧪 Exercício 3 – Simulação de Diálogo com Papéis

### 🎯 Objetivo:
Usar a IA para representar duas perspetivas diferentes.

Prompt exemplo:
```
"Simula um diálogo entre um diretor municipal e um fornecedor de software. O tema é a entrega tardia de um módulo crítico. Mostra as posições de ambas as partes, mantendo o tom profissional."
```

> 🧠 Excelente para criar role-play em formações, estudos de caso ou preparação de reuniões.

---

## 🧠 Desafio Final – Construir um Mega Prompt

Escolhe um problema real ou profissional e cria um prompt que:
- Defina o papel da IA (role)
- Inclua 1 ou 2 exemplos (few-shot)
- Especifique o tipo de saída (formato, estilo)
- Peça um raciocínio estruturado (chain-of-thought)

> Exemplo:
> "És um consultor de inovação digital. Com base na descrição abaixo, escreve um relatório em estilo executivo (com bullet points) que identifique riscos, oportunidades e próximos passos."

---

## ✅ Conclusão

Hoje aprofundaste as tuas competências de interação com IA, dominando técnicas como:

- Few-shot prompting
- Role + formato de resposta
- Diálogos multi-perspetiva

> 🧠 Quanto mais clara, rica e bem estruturada for a tua instrução, maior será a utilidade prática da resposta da IA.
