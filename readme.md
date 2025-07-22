# 🔐 Gerador QR Code & Senhas Aleatoria

Projeto simples em Node.js que permite gerar **QR Codes** e **senhas seguras** diretamente pelo terminal.

> 📦 Repositório: [CMatheus7/gerador-qrcode-password](https://github.com/CMatheus7/gerador-qrcode-password)

---

## ✨ Funcionalidades

- ✅ Gerar QR Code a partir de uma URL ou texto
- ✅ Gerar senha segura com critérios definidos

---

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/CMatheus7/gerador-qrcode-password.git
cd gerador-qrcode-password

▶️ Como usar
Execute o projeto com o comando abaixo:

bash
Copiar
Editar
node index.js
Você verá um prompt com as opções:

1 → Criar QR Code

2 → Gerar Senha Segura

🗂 Estrutura do Projeto
pgsql
Copiar
Editar
gerador-qrcode-password/
├── index.js                        # Arquivo principal
├── prompts-schema/
│   └── prompt-schema-main.js      # Definições dos prompts
├── services/
│   ├── password/
│   │   └── create.js              # Função geradora de senha
│   └── qr-code/
│       └── create.js              # Função geradora de QR Code
📋 Tecnologias
Node.js

prompt

🧑‍💻 Autor
Desenvolvido por Cristian Matheus

