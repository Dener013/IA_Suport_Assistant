# IA_Suport_Assistant
📌 Breve descrição do projeto

Este projeto consiste no desenvolvimento de um chatbot especialista em suporte a sistemas, utilizando o modelo Gemini 2.5 Flash no Google Colab.

O chatbot foi projetado para simular o atendimento de um analista de suporte, respondendo dúvidas com base em um conjunto fechado de informações sobre um sistema fictício chamado SysControl. Dessa forma, o bot evita alucinações e fornece respostas mais confiáveis e objetivas.

Além disso, o sistema possui uma regra de funcionamento específica: ele responde apenas três perguntas. Após a terceira interação, o chatbot gera automaticamente um resumo do atendimento e encerra a conversa.

▶️ Passo a passo para reprodução

Siga os passos abaixo para executar o projeto:

1. Acessar o ambiente
- Abra o projeto no Google Colab.
- Configure sua chave de API do Google (Gemini) utilizando o userdata.
2. Executar o código
- Execute todas as células do notebook na ordem correta.
- O chatbot será iniciado automaticamente no terminal interativo.
3. Interagir com o chatbot
Utilize as seguintes perguntas (mesmas do vídeo):
* Preciso resetar a senha
* Mas estou sem permissão
* Como posso abrir um chamado

4. Resultado esperado
O chatbot responderá cada pergunta com base na base de conhecimento definida.
Após a terceira pergunta:
- Será gerado um resumo automático do atendimento.
- A conversa será encerrada automaticamente.
