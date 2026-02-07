# 🎙️ Assistente Virtual com Python (Whisper + gTTS)

Este projeto foi desenvolvido como parte do Desafio de Projeto da **DIO (Digital Innovation One)**. O objetivo foi criar uma ferramenta capaz de ouvir (Speech-to-Text), processar inteligência (AI) e falar a resposta (Text-to-Speech).

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **OpenAI Whisper:** Para transcrever o áudio do usuário.
* **OpenAI API (GPT):** Para gerar a resposta inteligente.
* **gTTS (Google Text-to-Speech):** Para sintetizar a voz da resposta.

## 🚀 Como Executar

Este projeto foi otimizado para rodar no **Google Colab**.

1.  Clone este repositório ou baixe o arquivo `.ipynb`.
2.  Abra no Google Colab.
3.  Instale as dependências indicadas no início do código.
4.  Faça upload de um arquivo de áudio nomeado `pergunta.mp3`.
5.  Execute as células.

## ⚠️ Nota sobre a API Key (Modo Simulação)

Por padrão, o código está configurado no **"Modo Simulação Gratuito"**.
Isso significa que ele responderá a perguntas pré-definidas sem consumir créditos da OpenAI.

Para usar a inteligência real do ChatGPT:
1.  Edite a função `consultar_chatgpt`.
2.  Insira uma API Key válida com créditos ativos.
3.  Altere a lógica para usar o `client.chat.completions.create`.

## 👨‍💻 Autor

Desenvolvido por [Seu Nome Aqui]
