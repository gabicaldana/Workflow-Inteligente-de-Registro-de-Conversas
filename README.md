# 🤖 Integração entre IA conversacional e Google Sheets com n8n

Para por em prática meus conhecimentos, criei um workflow de automação com n8n, integrando IA conversacional e Google Sheets. 

## 🧠 Objetivo
Automatizar o registro de conversas e respostas inteligentes em tempo real, simulando um agente de suporte capaz de responder com empatia, humor e emojis.

## ⚙️ Funcionalidades
- Recebe mensagens via chat trigger do n8n  
- Registra automaticamente o `id` da conversa e o conteúdo no Google Sheets  
- Processa a mensagem com um Agente de IA (Groq)
- Mantém memória de contexto entre interações  
- Consulta a Wikipedia e realiza cálculos automáticos quando necessário  

## 🛠️ Tecnologias Utilizadas
- [n8n.io](https://n8n.io/)  
- LangChain  
- Groq API (modelo Llama 3.3 70B)  
- Google Sheets API  

## 📊 Fluxo resumido
1. Trigger de mensagem →  
2. Captura e armazenamento em planilha →  
3. Processamento por IA →  
4. Resposta automatizada humanizada  

## 🚀 Resultado
Um chatbot automatizado que combina IA generativa + automação de planilhas, ideal para testes de integração, suporte inteligente ou coleta de dados conversacionais.

## 📥 Como usar
1. Baixe o arquivo `Automacao_Inteligente_de_Conversas.json`
2. Acesse sua instância do [n8n](https://n8n.io)
3. Clique em *Importar workflow* e envie o arquivo
4. Configure suas credenciais (Google Sheets e Groq API)
5. Execute o fluxo para testar


---

👩‍💻 Projeto desenvolvido para estudos e aprimoramento de habilidades em automação e inteligência artificial aplicada.
