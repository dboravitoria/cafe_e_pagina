# 🌿 Guia rápido de Git

## 1. Antes de começar

Sempre atualize sua branch:

git checkout main
git pull origin main

## 2. Crie sua branch

git checkout -b feat/nome-da-tarefa

Exemplo:

git checkout -b feat/cardapio

## 3. Faça suas alterações

Edite os arquivos normalmente.

## 4. Confira o que mudou

git status

## 5. Adicione as alterações

git add .

## 6. Crie o commit

git commit -m "feat: cria estrutura do cardápio"

## 7. Envie para o GitHub

git push -u origin feat/cardapio

## 8. Abra um Pull Request

No GitHub, abra um Pull Request da sua branch
para a branch main.

## ⚠️ Importante

Não faça alterações diretamente na main.

Não use `git push --force`.

Antes de começar uma nova tarefa, atualize o projeto.