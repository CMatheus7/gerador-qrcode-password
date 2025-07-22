# 🔐 Gerador QR Code & Senhas Aleatórias

Projeto simples em **Node.js** que permite gerar **QR Codes** e **senhas seguras** diretamente pelo terminal.

## ✨ GitHub

> 📦 Repositório: [CMatheus7/gerador-qrcode-password](https://github.com/CMatheus7/gerador-qrcode-password)

---

## ✨ Funcionalidades

- ✅ Gerar QR Code a partir de uma URL ou texto
- ✅ Gerar senha segura com critérios definidos

---

## 📦 Instalação

1. Clone o repositório:

git clone https://github.com/CMatheus7/gerador-qrcode-password.git
cd gerador-qrcode-password

## ▶️ Como usar

Execute o projeto com o comando:

bash
Copiar
Editar
node index.js
Você verá um prompt com as opções:

1 → Criar QR Code

2 → Gerar Senha

## 🗂 Estrutura do Projeto

- gerador-qrcode-password/
- ├── index.js                        # Arquivo principal
- ├── prompts-schema/
- │   └── prompt-schema-main.js      # Definições dos prompts
- ├── services/
- │   ├── password/
- │   │   └── create.js              # Função geradora de senha
- │   └── qr-code/
- │       └── create.js              # Função geradora de QR Code


## ⚙️ Configurações via .env

O arquivo .env, localizado na raiz do projeto, permite personalizar a geração da senha. 
Exemplo:

env
Copiar
Editar
- UPPERCASE_LETTERS=false
- LOWERCASE_LETTERS=false
- NUMBERS=true
- SPECIAL_CHARACTERS=true
- PASSWORD_LENGTH=12
- ⚠️ Altere os valores conforme sua necessidade (true ou false).
  

## 📋 Tecnologias
Node.js

prompt

## 🧑‍💻 Autor
Desenvolvido por Cristian Matheus - Bootcamp DIO (meutudo)

