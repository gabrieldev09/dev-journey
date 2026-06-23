## Git — comandos aprendidos

- git init — cria repositório
- git status — mostra estado atual
- git add — move pra staging area
- git commit — salva no histórico
- git push — sobe pro GitHub
- git log — histórico de commits
- git diff — mostra o que mudou
- git restore — descarta alteração

Branch é como se fosse rascunho

Comandos usados:
git checkout -b feature/... cria o rascunho
git checkout main -> volta pro original
git merge feature/... passa o rascunho a limpo no original
git branch -d feature/... joga o rascunho fora

## Comandos terminal Linux

- touch - criar arquivo vazio
- echo "texto" > arquivo - escreve no arquivo
- cat - lê o conteúdo do arquivo
- cp origem destino - copia arquivo
- mv origem destino - move ou renomeia
- rm arquivo - deleta arquivo
- ps aux - mostra processos rodando no meu sistema

--- Variaveis de ambiente

- export - dura só na sessão atual
- .bashrc - permanente, carrega toda vez que abre o terminal
- source ~/.bashrc - recarrega arquivo sem fechar o terminal
- nano - editor de texto no terminal 
"No mundo real você nunca vai colocar senhas diretamente no .bashrc do servidor - vai usar arquivos .env que o Spring Boot lê automaticamente. Mas o conceito é o mesmo: separar segredos de código.

--- Permissões 

- chmod - muda permissões
- grep - busca texto em arquivo
- > vs >> sobrescreve vs adiciona 
- find - busca arquivos 