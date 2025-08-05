 # GUIA DEFINITIVO SOBRE GIT E GITHUB

 ## Preparação inicial de versionamento
 
 - 1º Passo - Instalar o Git ==> Software de Versionamento
 
 - 2º Passo - Configurar o Git
    - git config --global user.name "MeuUserName"
    - git config --global user.email "meu@email.com"

 - 3º Passo - Iniciar o Repositorio dentro do projeto (.git)
    - git init

 - 4º Passo - Sincronizar o Git com o GitHub
    - Criar um repositorio no GitHub
    - git remote add origin "endereço de Repositório"

 - 5º Passo - Adicionar Arquivos ao Repositório Local (GIT)
    - git add . (vai adicionar todos os arquivos ao repositório)

 - 6º Passo - Criar a Versão Local
    - git comit -m "meu texto"

 - 7º Passo - Enviar para o GitHub (nuvem)
    - git push -u origin main

 - 8º Passo - Atualizar repositorio local com arquivos da Nuvem
    - git pull

 - 9º Passo - Clonar meu Repositorio da Nuvem
    - git clone "endereço do meu repositorio online"
