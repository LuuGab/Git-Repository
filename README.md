## ⚠ Repositório dedicado a práticas e estudos com Git.

<p align="justify">
    "O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, usado para gerenciar e rastrear alterações em arquivos, especialmente em projetos de desenvolvimento de software. <b>Ele permite que equipes colaborem em projetos, rastreiem o histórico de alterações e revertam para versão anteriores</b>, tudo de forma eficiente e organizada."
</p>

## Comandos GIT

##### **`• git init`**
	O comando "git-init" possibilita com que uma respectiva pasta seja inicializada, ou torne-se um repositório local.

> **Observação(es):** Através da utilização do comando é criado uma pasta oculta ".git", nela reside todas as configurações e metadados necessários para o rastreamento de versões.

<br>

##### **`• git status`**
    O comando "git-status" possibilita com que o usuário verifique a situação atual dos arquivos dentro do repositório local.

<br>

##### **`• git add (arquivo) || git add . || git add *.(tipo do arquivo)`**
    O comando "git add" possibilita com que o usuário informe quais arquivos serão modificados a partir do próximo commit.

> **Observação(es):** Através da utilização do comando os arquivos são enviados ao que se denomina de "Staging Area", ou "Index", cujo se refere a um espaço temporário onde as alterações dos arquivos são feitas antes de serem confirmardas e efetivamente encaminhadas ao respositório remoto, no caso o próprio GitHub.

<br>

##### **`• git commit -a -m "Descrição do Commit"`**
    O comando "git commit" possibilita com que o usuário adicione uma descrição as alterações feitas no(s) arquivo(s).

<br>

##### **`• git config --global user.name "Nome"`**

<br>

##### **`• git config --global user.email "Email"`**

<br>

##### **`• git remote add origin <Link do Repositório>`**

<br>

##### **`• git clone <Link do Repositório>`**

<br>

##### **`• git push origin master`**