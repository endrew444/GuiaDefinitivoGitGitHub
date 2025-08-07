# Guia Definitivo de Git e GitHub

## Iniciando um Repositório

-1º instalar o Git no computador ( Software de versionamento local)

-2º Passo - Configurar o Software de Versionamento
   -git config --global user.name "UserName"
   - git config --global user.email "Meu@email.com"

-3º Passo - Iniciar o Repositório Local
   - git init (cria o ambiente de versionamento na pasta do Projeto)

-4º Passo - Iniciar o Repositório Online (GitHub) GIT <-> GITHUB
  - git remote add origin + Link_do_repositorio_github 
  - git remote get-url origin(verifica o link)
  - git remote set-url origin +link_do_repositorio_github(modifica o link)

-5º Passo - Adicionar meus arquivos ao Repositorio local
   -git add +nome_do_arquivo
   -git add . (adicionar todos os arquivos de uma única vez)

-6º Passo - Criar o Versionamento Local
  -git commit -m "Sua Mensagem"

-7º Passo - Sincronizar o Repositório Local com o GitHub
  -git push -u origin main

-8º Passo - Clonar um Repositório da Nuvem
 - git clone +Link_do_repositorio_github

- 9º Passo - Atualizar um Repositorio Local
 -git pull origin main

## Criando um repositório colaborativo