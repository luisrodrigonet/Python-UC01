
# **Tarefa 01: Criando um repositório local 🚀🐙**  

## 🎯 **Objetivo**: 
Aprender e praticar as principais funcionalidades do **Git**, focando na criação de um repositório local.  

## 📌 **Pré-requisitos**:  

✅ **Git instalado**: Se ainda não instalou, baixe  [aqui](https://git-scm.com/).
✅ **Conta no GitHub**  (ou GitLab/Bitbucket, se preferir).
✅ Conhecimento básico de uso de  **terminal**  (Prompt de Comando, PowerShell ou Terminal Linux/Mac).

## **🔹 Passo 1: Configurar o Git**
Antes de mais nada, vamos garantir que o Git reconheça sua identidade! No terminal, digite o seguinte comando:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Agora, verifique se deu certo:  

```bash
git config --list
```

## **🔹 Passo 2: Criando um Repositório Git**

Vamos criar nosso primeiro repositório!

1️⃣ **Crie uma pasta para o projeto**

```bash

mkdir projeto_python_uc1

cd projeto_python_uc1

```

2️⃣ **Inicie o Git dentro da pasta**

```bash

git init

```

Pronto! Agora essa pasta é um repositório Git! 🎉

3️⃣ **Crie um arquivo de teste**

```bash

echo "Olá, Git!" > README.txt

```

4️⃣ **Verifique o status do repositório**

```bash

git status

```

➡️ O Git vai mostrar que há um arquivo não rastreado.