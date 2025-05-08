# 🤖 Chatbot IA com Node.js + OpenAI

Este é um chatbot simples que utiliza a API da OpenAI (ChatGPT) para responder em linguagem natural. Ele possui uma interface web e um backend seguro em Node.js.

## 🖼️ Demonstração
Acesse a versão online (se implantado): [https://seu-link-render.onrender.com](https://seu-link-render.onrender.com)

## 📦 Tecnologias Usadas

- [x] Node.js + Express
- [x] OpenAI API (GPT-3.5 Turbo)
- [x] HTML + CSS + JavaScript (Frontend)
- [x] Render (Deploy gratuito)

---

## 🚀 Como executar localmente

### 1. Clone o repositório
```bash
git clone https://github.com/seuusuario/chatbot-ai.git
cd chatbot-ai
```

### 2. Instale as dependências
```bash
npm install
```

### 3. Configure sua chave da OpenAI
Crie um arquivo `.env` na raiz com o conteúdo:

```env
OPENAI_API_KEY=sua-chave-aqui
```

### 4. Inicie o servidor
```bash
node server.js
```

Abra no navegador: `http://localhost:3000`

---

## 🌐 Deploy no Render

1. Suba o projeto para o GitHub
2. Acesse [https://render.com](https://render.com)
3. Crie um novo **Web Service**
4. Configure o Build:
   - Build Command: `npm install`
   - Start Command: `node server.js`
5. Adicione a variável de ambiente:
   - `OPENAI_API_KEY` = sua chave

---

## 🛡️ Segurança

- A chave da API está protegida no backend (nunca colocada no frontend).
- Não compartilhe publicamente sua chave OpenAI.

---

## 📄 Licença

Este projeto é livre para uso e modificação. Licença MIT.
