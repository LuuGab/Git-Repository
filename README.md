## ⚠ Repositório dedicado a práticas e estudos com Git.

<p align="justify">
    "O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, usado para gerenciar e rastrear alterações em arquivos, especialmente em projetos de desenvolvimento de software. <b>Ele permite que equipes colaborem em projetos, rastreiem o histórico de alterações e revertam para versão anteriores</b>, tudo de forma eficiente e organizada."
</p>

## Comandos GIT

> **GIT INIT**

<p align="justify">
    O comando "git-init" possibilita com que uma respectiva pasta seja inicializada, ou torne-se um repositório local.
</p>

<p align="justify">
    <b>Observação(es):</b> Através da utilização do comando é criado uma pasta oculta ".git", nela reside todas as configurações e metadados necessários para o rastreamento de versões.
</p>

<br>

> **GIT STATUS**

<p align="justify">
    O comando "git-status" possibilita com que o usuário verifique a situação atual dos arquivos dentro do repositório local.
</p>

<br>

> <b>GIT ADD (arquivo) | GIT ADD *.(tipo do arquivo) | GIT ADD .</b>

<p align="justify">
    O comando "git add" possibilita com que o usuário informe quais arquivos serão modificados a partir do próximo commit.
</p>

<p align="justify">
    <b>Observação(es):</b> Através da utilização do comando os arquivos são enviados ao que se denomina de "Staging Area", ou "Index", cujo se refere a um espaço temporário onde as alterações dos arquivos são feitas antes de serem confirmardas e efetivamente encaminhadas ao respositório remoto, no caso o próprio GitHub.
</p>

<br>

> **GIT COMMIT -a -m "Descrição do Commit"**

<p align="justify">
    O comando "git commit" possibilita com que o usuário adicione uma descrição as alterações feitas no(s) arquivo(s).
</p>

<br>

> **GIT CONFIG --global user.name "Nome"**

<br>

> **GIT CONFIG --global user.email "Email"**

<br>

> **GIT REMOTE ADD ORIGIN <Link do Repositório>**

<br>

> **GIT CLONE <Link do Repositório>**

<br>

> **GIT PUSH ORIGIN (Nome da Branch)**