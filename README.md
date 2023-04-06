# Curso-frontend2

#urso C-frontend02


### EBAC

# GIT
## conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução continua

Arquivo A / Versão 1 / Versão 2
Arquivo B / Versão 1 / Versão 2

## Instalação do Git

## Criar conta no GitHub

## Clonar o projeto
git clone https://github.com/LuccasWoody/Curso-frontend2.git
## Clonar  

## Commits
Informação de alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"
- git push (enviar alteracoes para o repositorio GitHub)
- git pull (puxar / trazer alteracoes feitas no repositorio GitHub para sua maq) 

## Gitflow
Fluxo do Git


### Branchs
 são ramificações / versões paralelas do código
 - mais/master
 - develop (usa como ambiente de desenvolvimento e testes, um ambiente separado e quando estiver tudo testado, tudo ok, enviar para a branch master.)
 - DOD= Definition of Done: critério de aceite
 - versionamento 1.0.0

 git checkout -b dev (cria uma branch)
 git checkout master (mudar de branch)


 ### Merge
 Mescla de branchs.
 Você pode precisar resolver conflitos manualmente

 git merge main


 ### Pull Requests
 mescla de branchs no repositótio
 permite code review
 O repositório resolve os conflitos automaticamente


 ### Configura o  GitFlow
 git flow init
 git flow feature start melhoria-html {nome-da-feature}
