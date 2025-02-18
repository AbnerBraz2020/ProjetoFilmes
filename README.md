 # MANUAL DE UTILIZAÇÃO DO SISTEMA/SITE
## - DOWNLOAD E INSTALAÇÃO DO GITHUB
Acesse o site do Github para fazer o download do Github.
Quando acessar o site, faça o download do programa (no lugar indicado na imagem).

<p align="center">
    <a href="https://git-scm.com/downloads" target="_blank">
        <img src="Docs/Imagens/Site Github.png" width="400"> 
    </a>
</p>

Faça o download da versão que é correspondente ao sistema operacional do seu computador. (32-bit ou 64-bit)

<p align="center">
    <a href="https://git-scm.com/downloads/win" target="_blank">
        <img src="Docs/Imagens/Download Git.png" width="400"> 
    </a>
</p>

Para saber se seu computador é 32 ou 64 bits, siga os passos a seguir.

Vá em Iniciar > Configurações > Sistema > Sobre

<p align="center">
        <img src="Docs/Imagens/Requisitos de sistema.png" width="400"> 
</p>

## - CONFIGURAÇÃO INICIAL
Tutorial de instalação do GIT

 <p align="justify">
    Realize a busca do termo [Instalar GIT](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) para Windows.
</p>

 <p align="center">
    <a href="https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git" target="_blank">
        <img src="Docs/Imagens/Git.png" width="400"> 
    </a>
</p>

## - CONFIGURANDO A CONTA GIT PELO TERMINAL
Para acessar o Terminal, vá em Inicial > Pesquisar > Pesquiser por Windows Power Shell.

<p align="center">
    <img src="Docs/Imagens/Terminal.png" width="400"> 
</p>

Precisa fazer alguns comandos no Terminal do Windows para configurar o git.

- git --version (Para saber qual versão do git está no seu computador).
- git config --global user.name "Fulano de Tal" (Use o Nome que no Perfil da sua conta do git).
- git config --global user.email fulanodetal@exemplo.br (Use o email que você criou a conta do git).

<p align="center">
    <img src="Docs/Imagens/Print 3.png" width="400"> 
</p>

- ssh-keygen (Comando que gera a chave publica e privada, também irá pedir a criação de uma senha).

<p align="center">
    <img src="Docs/Imagens/Print 4.png" width="400"> 
</p>

Entre na pasta .ssh/

E use o comando "cat"

## - CONFIGURANDO GIT
Ao extrair a chave no Terminal, você precisa gravar sua chave no git.
Profile > Setting > SSH and GPG Keys > New SSH Key

<p align="center">
    <img src="Docs/Imagens/Key.png" width="400"> 
</p>

## - CRIAÇÃO DO REPOSITORIO
Para criar um repositorio no github.
Vá na Página Inicial > New > Create repository

<p align="center">
    <img src="Docs/Imagens/Repositorio.png" width="400"> 
</p>

Pelo Terminal entre na pasta do projeto e realize os comandos abaixo.

<p align="center">
    <img src="Docs/Imagens/Init.png" width="400"> 
</p>

- git init
- git remote add origin
- Utilize o comando: code . (Para executar o vscode)                          
No Terminal do Vscode, crie uma branch:
- git branch -M master
- git push -u origin master

<p align="center">
    <img src="Docs/Imagens/Repositorio 2.png" width="400"> 
</p>

Esses comandos servem para que o projeto seja linkado com o github e concluindo o repositorio.

## - EXECUTANDO VSCODE

Após linkar o projeto com o github, precisamos executar o VScode para que o projeto possa ser iniciado.

Use o comando mostrado na imagem para executar o projeto no VScode, lembrando que precisa estar dentro da pasta do projeto.

<p align="center">
    <img src="Docs/Imagens/vscode.png" width="400"> 
</p>

## - INSTALAR EXTENSÕES

Quando executar o vscode, você precisa instalar algumas extensões:
- GitHub Copilot
- GitHub Pull Request 

<p align="center">
    <img src="Docs/Imagens/Extensões.png" width="400"> 
</p>

## - CRIAR PASTAS DENTRO DO PROJETO

<p align="center">
    <img src="Docs/Imagens/Criar pastas dentro do Projeto.png" width="400"> 
</p>

## - CRIE UMA NOVA BRANCH

Para que você possa saber as branchs existentes, use o comando:
- git branch

Para criar uma nova branch, use o comando:
- git branch master, main ou develop
Essas são as branchs mais usadas.

<p align="center">
    <img src="Docs/Imagens/Criação de brach.png" width="400">
</p>

## - MUDANDO DE BRANCH

Caso queira mudar de branch para colocar outros projetos.
Use o comando: git checkout NomeDaBranch

<p align="center">
    <img src="Docs/Imagens/Mudança de branch.png" width="400"> 
</p>

## - PUXAR ARQUIVOS

Caso queira transferir os projetos de uma branch para outra branch, use o comando: git pull origin master

<p align="center">
    <img src="Docs/Imagens/Puxar arquivos.png" width="400"> 
</p>

## - COMANDOS ADMINISTRATIVOS DO GIT NO TERMINAL DO VSCODE

No Terminal do VScode execute os comandos abaixo:

- git status
- git add .
- git commit -m "Mensagem de desenvolvedor" ex: git commit -m "File update"
- git push -u origion master or main

<p align="center">
    <img src="Docs/Imagens/Terminal VScode.png" width="400"> 
</p>

Esses comandos servem para você enviar seu projeto para o github e salva-lo. 

## - CLONAR PROJETO DO GITHUB
Caso você queira seu projeto em outro computador, utilize esse comando:

- git clone (+ link do projeto no git e dentro do diretorio)

<p align="center">
    <img src="Docs/Imagens/Clone.png" width="400"> 
</p>