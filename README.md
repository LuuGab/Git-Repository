## ⚠ Repositório dedicado a práticas e estudos com Git.

## O que é o GIT?

<p align="justify">
    O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, usado para gerenciar e rastrear as alterações feitas em arquivos, especialmente em projetos de desenvolvimento de software. <b>Ele permite que equipes colaborem em projetos, rastreiem o histórico de alterações feitas e revertam para versão anteriores</b>, tudo de maneira eficiente e organizada.
</p>

## Conceitos Básicos

> **REPOSITÓRIO**

<p align="justify">
    Em termos gerais, o "Repositório" refere-se a um espaço, seja ele local ou remoto, em que se torna possível armazenar, modificar e gerenciar dados e/ou informações sobre projetos, sistemas e códigos.
</p>

<br>

**• Repositório Local**

<p align=justify>
    O "Repositório Local" trata-se de um espaço dedicado ao gerenciamento de dados que se localiza no seu computador. Nele contém a pasta oculta ".git", em que localiza todos os metadados necessários para o funcionamento adequado do git e o versionamento de arquivos.
</p>

**• Repositório Remoto**

<p align=justify>
    Já o "Repositório Remoto" baseia-se em uma versão do repositório local que é mantido na nuvem através de serviços como o GitHub, GitLab, ou o Bitbucket. Dessa forma, torna-se possível de se fazer backups, compartilhar projetos, ou colaborar em desenvolvimentos em equipe com outras pessoas.
</p>

<br>

> **BRANCH**

<p align="justify">
    As "Branch" referem-se a ramificações separadas de um espaço de desenvolvimento principal. Ou seja, trata-se de um espaço remoto que é criado com base em um referencial, espelhando todos os arquivos e/ou códigos nele contido, possibilitando com que seja possível de se efetuar diversas alterações e modificações sem que afete diretamente a linha principal, que é geralmente denominado de "<b>main</b>" ou "<b>master</b>".
</p>

<br>

> **MERGE**

<p align="justify">
    A princípio o "Merge" refere-se a um trecho que pode ser utilizado com uso do Git para unificar diferentes versões de um respectivo projeto, geralmente sendo aplicado com o intuito de unir as modificações de uma determinada branch do repositório a outra.
</p>

<br>

> **COMMIT**

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

> **GIT LOG**

<p align="justify">
    O comando "git log" possibilita com que o usuário visualize o histórico de alterações realizadas, incluindo o autor e o nome do commit, a data em que foi feito, e o "Hash" daquele respectivo commit.
</p>

<p align="justify">
    <b>Observações:</b> "Hash" refere-se a um identificador único do commit, podendo também ser chamado de "ID". Tal identificador é de suma importância, principalmente para desfazer modificações específicas ou retornar o estado de um arquivo ou código para um ponto especificado.
</p>

<br>

> **GIT RESTORE (nome do arquivo)**

<p align="justify">
    O comando "git restore" permite ao usuário retomar o arquivo ao estado anterior previamente as mudanças realizadas. Ou seja, caso uma determinada modificação tenha sido feita de maneira indevida, através do comando torna-se possível de reverter aquelas respectivas alterações. 
</p>

<p align="justify">
    <b>Observações:</b> Através da inserção do trecho "--source=&gt;commit&lt;" antes do nome do arquivo torna-se possível restaurar o arquivo para o estado em que estava em um commit específico. Nesse caso, troca-se o "commit" pelo identificador Hash do commit desejado.
</p>

<br>

> **GIT CHECKOUT -B (nome da nova branch)**

<p align="justify">
    O comando "git checkout -b" permite ao usuário criar uma nova branch a partir da que está no momento.
</p>

<br>

> **GIT CHECKOUT (nome da branch)**

<p align="justify">
    O comando "git checkout" permite ao usuário alterar para uma branch específica preexistente.
</p>

<br>

> **GIT MERGE (nome da branch referência)**

<p align="justify">
    O comando "git merge" permite ao usuário copiar e mesclar as alterações feitas de uma branch referência na branch em que designa atualmente.
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