# 📘 Módulo x: Tarefas Agendadas

Como funciona a automação interna
Seleciona-se o modelo “GPT-4o with scheduled tasks” ou o botão Tasks no Grok.

Escreve-se o prompt com o pedido e a cadência (“Todos os dias às 08:00, envia…”).

A IA grava o job; quando chega a hora, executa o prompt e envia o resultado.

A lista completa de tarefas permite pausar, editar ou apagar cada job.

Ambas as plataformas executam o código no back-end – o utilizador pode estar offline e mesmo assim receber o resultado na hora definida.

2. Boas práticas de agentes agendados
Clareza do prompt: inclua objetivo, formato de saída e limite de tamanho para evitar mensagens demasiado longas ou ambíguas.

Logs e histórico: exporte periodicamente as respostas (ex.: para Google Sheets) para auditoria e melhoria contínua.

Notificações seletivas: ative apenas o canal indispensável (push ou email) para evitar sobrecarga.

Segurança: evite incluir chaves ou dados sensíveis no prompt; lembre-se de que as mensagens podem ser utilizadas para treino futuro.

Rotação/limpeza: arquive tarefas antigas para não esgotar o limite de jobs ativos.

3. Exercícios práticos
Exercício 1 – Briefing diário de IA (ChatGPT)
Objetivo: receber às 07:30 um sumário das três notícias mais relevantes sobre inteligência artificial.

Abra um novo chat e escolha GPT-4o with scheduled tasks.

Escreva:

text
Todos os dias às 07:30 cria um sumário em 150 palavras com as 3 notícias de IA mais importantes e envia-me.
Autorize notificações. Verifique em Profile → Tasks se a tarefa foi criada.

Após a primeira execução, analise o texto e ajuste o limite de palavras se necessário.
