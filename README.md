## ⚠ Repositório dedicado a práticas e estudos com Git.

## O que é o GIT?

<p align="justify">
    O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, usado para gerenciar e rastrear as alterações feitas em arquivos, especialmente em projetos de desenvolvimento de software. <b>Ele permite que equipes colaborem em projetos, rastreiem o histórico de alterações feitas e revertam para versão anteriores</b>, tudo de maneira eficiente e organizada.
</p>

## Conceitos Básicos

> **Repositório**

<p align="justify">
</p>

<br>

**• Repositório Local**

**• Repositório Remoto**

<br>

> **Branch**

<p align="justify">
    "O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, usado para gerenciar e rastrear alterações em arquivos, especialmente em projetos de desenvolvimento de software. <b>Ele permite que equipes colaborem em projetos, rastreiem o histórico de alterações feitas e revertam para versão anteriores</b>, tudo de maneira eficiente e organizada."
</p>

<br>

> **Merge**

<p align="justify">
</p>

<br>

> **Commit**

<p align="justify">
    De maneira simples e direta, o "Commit" se trata do processo de nomear o grupo das alterações que foram realizadas sob um arquivo, e assim salvá-las no histórico de versionamento.
</p>

## Comandos GIT

> **GIT INIT**

<p align="justify">
    O comando "git-init" possibilita com que uma respectiva pasta seja inicializada, ou torne-se um repositório local.
</p>

<p align="justify">
    <b>Observações:</b> Através da utilização do comando é criado uma pasta oculta ".git", nela reside todas as configurações e metadados necessários para o rastreamento de versões.
</p>

<br>

> **GIT STATUS**

<p align="justify">
    O comando "git-status" possibilita com que o usuário verifique a situação atual dos arquivos dentro do repositório local.
</p>

<br>

> <b>GIT ADD (arquivo) | GIT ADD *.(tipo do arquivo) | GIT ADD .</b>

<p align="justify">
    O comando "git add" possibilita com que o usuário informe ao software quais os arquivos que foram modificados e que terão suas alterações salvas para o próximo commit. Ou seja, na prática, ao alterar um arquivo torna-se preciso utilizar o comando para leva-lo a zona de commit, onde será registrado as alterações que foram feitas. Nesse sentido, caso utilize o git add, e posteriormente efetue novas mudanças, será necessário repetir o comando para assim registrar essas novas alterações para serem "commitadas". 
</p>

<p align="justify">
    <b>Observações:</b> Através da utilização do comando os arquivos são enviados ao que se denomina de "Staging Area", ou "Index", cujo se refere a um espaço temporário onde as alterações dos arquivos são registradas antes de serem confirmardas e efetivamente encaminhadas ao respositório remoto, no caso o próprio GitHub.
</p>

<br>

> **GIT COMMIT -m "Descrição do Commit"**

<p align="justify">
    O comando "git commit" possibilita com que o usuário adicione uma descrição as alterações feitas nos arquivos.
</p>

<p align="justify">
    <b>Observações:</b> Para a execução do comando torna-se preciso ter utilizado o "git add" previamente, para assim de fato salvar as modificações feitas no arquivo. Todavia, ao incluir o <b>"-a"</b> na estrutura do comando do commit, este trecho fará com que todos os arquivos que foram modificados sejam levados diretamente a Staging Area. Dessa forma, <b>ao incluir o "-a" torna-se possível fazer mudanças nos arquivos já indexados e fazer o commit direto sem precisar usar o "git add" novamente</b>. Entretanto, é importante ressaltar que este trecho afeta somente aqueles arquivos cujo já foram rastreados previamente pelo Git, ou seja, que já foram adicionados antes com o "git add".
</p>

<br>

> **GIT log**

<p align="justify">
</p>

<br>

> **GIT CONFIG --global user.name "Nome"**

<p align="justify">
</p>

<br>

> **GIT CONFIG --global user.email "Email"**

<p align="justify">
</p>

<br>

> **GIT REMOTE ADD ORIGIN <Link do Repositório>**

<p align="justify">
</p>

<br>

> **GIT CLONE <Link do Repositório>**

<p align="justify">
</p>

<br>

> **GIT PUSH ORIGIN (Nome da Branch)**

<p align="justify">
</p>

<br>