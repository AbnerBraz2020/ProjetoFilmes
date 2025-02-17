 # MANUAL DE UTILIZAÇÃO DO SISTEMA/SITE
## - DOwNLOAD E INSTALAÇÃO DO GITHUB
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
- cat (Extrai a chave publica).

<p align="center">
    <img src="Docs/Imagens/Print 4.png" width="400"> 
</p>

##  - CONFIGURANDO GIT
Ao extrair a chave no Terminal, você precisa gravar sua chave no git.
Profile > Setting > SSH and GPG Keys > New SSH Key

<p align="center">
    <img src="Docs/Imagens/" width="400"> 
</p>

##  - CRIAÇÃO DO REPOSITORIO
Como criar um repositorio.

- git init
- git remote add origin
- git branch -m brain
- git push -u origin main ou master

<p align="center">
    <img src="Docs/Imagens/Repositorio.png" width="400"> 
</p>

## EXECUTANDO VSCODE
<p align="center">
    <img src="Docs/Imagens/vscode.png" width="400"> 
</p>

## - COMANDOS ADMINISTRATIVOS DO GIT NO TERMINAL DO VSCODE

<p align="center">
    <img src="Docs/Imagens/Terminal VScode.png" width="400"> 
</p>

- git status
- git add . or git add index.html
- git commit -m "Mensagem de desenvolvedor" ex: git commit -m "File update"
- git push -u origion master or main

## CLONAR PROJETO DO GITHUB 
git clone (+ link do projeto no git e dentro do diretorio)