# 🚀 Comandos Git Essenciais

Este guia lista os comandos Git mais usados para ajudar você a trabalhar com repositórios Git e colaborar com outros desenvolvedores. A seção **Comandos Básicos** apresenta operações do dia a dia, enquanto **Branching e Merging** foca em fluxos de trabalho com branches. A seção **Comandos para Repositórios Remotos** abrange operações com repositórios remotos, e **Outros Comandos Úteis** cobre recursos avançados do Git.

## 📋 Comandos Básicos

- `git init`: Inicia um novo repositório Git em uma pasta.
- `git clone <url>`: Clona um repositório remoto para sua máquina local.
- `git status`: Mostra o estado atual do repositório, incluindo mudanças feitas, arquivos não rastreados, etc.
- `git add <arquivo>`: Adiciona um arquivo ao stage para um futuro commit.
- `git add .`: Adiciona todos os arquivos modificados e não rastreados ao stage.
- `git commit -m "<mensagem>"`: Cria um commit com uma mensagem descrevendo as mudanças.
- `git push`: Envia os commits locais para um repositório remoto.
- `git pull`: Baixa e mescla as mudanças de um repositório remoto.
- `git checkout <branch>`: Alterna para um branch específico.
- `git branch`: Lista todos os branches locais.

## 🌳 Comandos para Branching e Merging

- `git branch <nome>`: Cria um novo branch.
- `git checkout -b <nome>`: Cria e alterna para um novo branch ao mesmo tempo.
- `git merge <branch>`: Mescla um branch no branch atual.
- `git rebase <branch>`: Rebaseia o branch atual em outro branch.
- `git branch -d <nome>`: Deleta um branch local.

## 🌐 Comandos para Repositórios Remotos

- `git remote add origin <url>`: Adiciona um repositório remoto ao repositório local.
- `git remote -v`: Lista todos os repositórios remotos configurados.
- `git fetch`: Busca mudanças de um repositório remoto sem mesclar automaticamente.
- `git push origin <branch>`: Envia um branch específico para o repositório remoto.
- `git push origin --delete <branch>`: Deleta um branch remoto.

## 🔧 Outros Comandos Úteis

- `git log`: Exibe o histórico de commits.
- `git diff`: Mostra as diferenças entre arquivos no repositório.
- `git reset --hard <commit>`: Restaura o repositório para um estado específico, descartando mudanças.
- `git stash`: Armazena temporariamente mudanças não commitadas.
- `git stash pop`: Aplica mudanças que foram armazenadas com `git stash`.
- `git tag <nome>`: Adiciona uma tag a um commit específico.
- `git blame <arquivo>`: Mostra quem fez cada linha em um arquivo específico.

## 📝 Notas Finais

Estes comandos cobrem a maioria das situações ao trabalhar com Git. Se precisar de mais informações ou exemplos específicos, sinta-se à vontade para perguntar ou consultar a documentação oficial do Git. Feliz codificação! 😊
