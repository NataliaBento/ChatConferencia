
# 💻 Assistente de Eventos de Tecnologia da Informação

Este projeto é um assistente virtual desenvolvido com foco em eventos de Tecnologia da Informação (TI). Ele utiliza um backend em Node.js para receber perguntas dos usuários, consulta uma API de IA (OpenRouter) e retorna respostas contextualizadas sobre conferências, congressos, feiras e encontros da área de tecnologia.

O assistente fornece informações sobre datas, temas, como participar, oportunidades de networking, comunidades envolvidas e muito mais — de forma clara, atualizada e acessível tanto para estudantes quanto profissionais da área.

[screen-capture.webm](https://github.com/user-attachments/assets/2d7bdd4f-4784-40c1-94f6-8905a6803bc1)

---

## 🛠️ Construído com

<div style="display: inline-block"><br/>
  <img align="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img align="center" alt="css3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img align="center" alt="js" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img align="center" alt="nodejs" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /> 
</div><br/>

---

## 👨🏽‍💻 Versão das Tecnologias

- HTML5  
- CSS3  
- JavaScript ECMAScript 6 (ES6)  
- Node.js v22.12.0  

---

## ✒️ Autor(a)

**Natalia Bento**  
[🔗 LinkedIn](https://www.linkedin.com/in/natalia-bento-364b2b235/)

---

## 🚀 Guia de Como Baixar e Rodar o Projeto

### 📦 Pré-requisitos

Antes de começar, você vai precisar ter instalado na sua máquina:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/pt-br)

É recomendado usar um editor como o [VSCode](https://code.visualstudio.com/) para trabalhar com o código.

---

### 🛠️ Como rodar o projeto

#### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

#### 2. Acesse a pasta do backend

```bash
cd seu-repositorio/backend
```

#### 3. Instale as dependências do backend

```bash
npm install
```

#### 4. Gere uma chave de API gratuita na OpenRouter

1. Acesse: https://openrouter.ai/keys  
2. Crie sua conta ou faça login  
3. Clique em "Create new key"  
4. Copie a chave gerada

#### 5. Crie o arquivo `.env` com a chave da API

Dentro da pasta `backend`, crie um arquivo chamado `.env` e adicione:

```env
OPENROUTER_API_KEY=SUA_CHAVE_AQUI
PORT=3000
```

#### 6. Inicie o backend

```bash
npm start
```

#### 7. Rode o frontend

Abra o arquivo `frontend/index.html` no navegador para utilizar o assistente.


