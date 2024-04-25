# AulaGit-GitHub
Aula do Básico ao avaçado de Git e GitHub

01 Seção - Introdução e Instalações das dependências

02 Seção - Git Fundamental 

03 Seção - Trabalhando com Branches

04 Seção - Compatilhamento e atualizações de repositórios

05 Seção - Análise e inspeção de repositório 

06 Seção - Administração de repositórios 

07 Seção - Markdown 

08 Seção - GitHub Pages

LINK VISUAL: https://ndpsoftware.com/git-cheatsheet.html#loc=workspace; 

Linkedin do autor: https://www.linkedin.com/in/pedrolins29/ 

===========================================================================

 01 Seção - Introdução e Instalações das dependências: 
 
##O que é GIT? 

  ● O sistema de controle de versão mais utilizado do mundo atualemente;
  
  ● O GIT é baseado em reositírio, que contês todas as versões do código e também as cópias de 
     cada desenvolvedor;
     
  ● Todas as operações do GIT são otimizadas para ter alto desempenho;
  
  ● Todos os objetos do git são protegidos como criptogratia para alterações indevidas e 
     maliciosas;
     
  ● o GIT é im prejeto de código aberto

    https://www.atlassian.com/git
    

    INSTALAÇÃO DO GIT
    
    WINDOWNS: https://git-scm.com/downloads 
    Linux: https://git-scm.com/download/linux 
    MacOS: https://git-scm.com/download/mac 

    
##O que é controle de versão? 

  ● Uma técnica que ajuda a gerenciar o código-fonte de uma aplicação;
  
  ● Registrando todas as modificações de código, podendo também 
  reverter as mesmas;
  
  ● Criar versões de um software em diferentes estágios, podendo alterar 
  facilmente entre elas;
  
  ● Cada membro da equipe pode trabalhar em uma versão diferente;
  
  ● Há ferramentas para trabalhar o controle de versão como: git e SVN
  

=====================================================================


02 Seção - Git Fundamental https://docs.github.com/pt/get-started/using-git/about-git 


##Comandos Fundamentais

O que é um repositório?

  ● É onde o código será armazenado;
  
  ● Na maioria das vezes cada projeto tem um repositório;
  
  ● Quando criamos um repositório estamos iniciando um projeto;
  
  ● O repositório pode ir para servidores que são especializados em 
  gerenciar repos, como: GitHub e Bitbucket;
  
  ● Cada um dos desenvolvedores do time pode baixar o repositório e criar 
  versões diferentes em sua máquina

##O que é o GitHub? https://docs.github.com/pt/get-started/start-your-journey/about-github-and-git 

  ● É um serviço para gerenciar repositórios, gratuito e amplamente 
  utilizado;
  
  ● Podemos enviar nossos projetos para o GitHub e disponibilizá-lo para 
  outros devs;
  
  ● O GitHub é gratuito tanto para projetos públicos como privados;
  
  ● Vamos criar uma conta em:  https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github 


##Criando repositórios https://docs.github.com/pt/repositories/creating-and-managing-repositories/quickstart-for-repositories 

  ● Para criar um repositório utilizamos o comando: git init;
  
  ● Desta maneira o git vai criar os arquivos necessários para inicializá-lo;
  
  ● Que estão na pasta oculta .git;
  
  ● Após este comando o diretório atual será reconhecido pelo git como 
  um projeto e responderá aos seus demais comandos;

##Enviando repositórios para o GitHub https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github 

  ● Podemos facilmente enviar nossos repos para o GitHub;
  
  ● Precisamos criar o projeto no GitHub, inicializar o mesmo no git em 
  nossa máquina, sincronizar com o GitHub e enviar;
  
  ● E esta sequência que parece ser complexa é facilmente executada por 
  poucos comandos;
  
  ● Vale lembrar que só fazemos uma vez por projeto este fluxo;
  
  ● Porém alguns dos comandos utilizados vão ser úteis ao longo do fluxo de trabalho;

##Verificando mudanças do projeto

  ● As mudanças do projeto podem ser verificadas por: git status;
  
  ● Este comando é utilizado muito frequentemente;
  
  ● Aqui serão mapeadas todas as alterações do projeto;
  
  ● Como: arquivos não monitorados e arquivos modificados;
  
  ● Podemos também dizer que é a diferença do que já está enviado ao 
  servidor ou salvo no projeto;

##Adicionando arquivos ao projeto https://docs.github.com/pt/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

  ● Para adicionar arquivos novos a um projeto utilizamos: git add
  
  ● Podemos adicionar um arquivo específico como também diversos de 
  uma vez só;
  
  ● Somente adicionando arquivos eles serão monitorados pelo git;
  
  ● Ou seja, se não adicionar ele não estará no controle de versão;
  
  ● É interessante utilizar este comando de tempos em tempos para não 
  perder algo por descuido

##Salvando alterações do projeto https://github.com/git-guides/git-commit 

  ● As alterações salvas do projeto são realizadas por: git commit;
  
  ● Podemos commitar arquivos específicos ou vários de uma vez com a 
  flag -a
  
  ● É uma boa prática enviar uma mensagem a cada commit, com as 
  alterações que foram feitas;
  
  ● A mensagem pode ser adicionada com a flag -m

##Enviando código ao repo remoto https://docs.github.com/pt/get-started/using-git/pushing-commits-to-a-remote-repository 

  ● Quando finalizamos uma funcionalidade nova, enviamos o código ao 
  repositório remoto, que é código-fonte;
  
  ● Esta ação é feita pelo git push
  
  ● Após esta ação o código do servidor será atualizado baseando-se 
  no código local enviado;

##Recebendo as mudanças https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request 

  ● É comum também ter que sincronizar o local com as mudanças do 
  remoto;
  
  ● Esta ação é feita pelo git pull
  
  ● Após o comando serão buscadas atualizações, se encontradas elas 
  serão unidas ao código atual existente na nossa máquina;

##Clonando repositórios https://docs.github.com/pt/get-started/using-git/getting-changes-from-a-remote-repository

  ● O ato de baixar um repositório de um servidor remoto é chamado de 
  clonar repositório;
  
  ● Para esta ação utilizamos git clone
  
  ● Passando a referência do repositório remoto;
  
  ● Este comando é utilizado quando entramos em um novo projeto, por 
  exemplo;
  
##Removendo arquivos do repositório https://docs.github.com/pt/repositories/working-with-files/managing-files/deleting-files-in-a-repository

  ● Os arquivos podem ser deletados da monitoração do git
  ● O comando para deletar é git rm
  
  ● Após deletar um arquivo do git ele não terá mais suas atualizações 
  consideradas pelo git;
  
  ● Apenas quando for adicionando novamente pelo git add

##Histórico de alterações https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Vendo-o-hist%C3%B3rico-de-Commits

  ● Podemos acessar um log de modificações feitas no projeto;
  
  ● O comando para este recurso é git log
  
  ● Você receberá uma informação dos commits realizados no projeto até 
  então;
  

##Renomeando arquivos https://docs.github.com/pt/enterprise-cloud@latest/repositories/working-with-files/managing-files/renaming-a-file

  ● Com o comando git mv podemos renomear um arquivo;
  
  ● O mesmo também pode ser movido para outra pasta;
  
  ● E isso fará com que este novo arquivo seja monitorado pelo git;
  
  ● O arquivo anterior é excluído;
  

##Desfazendo alterações https://git-scm.com/book/pt-pt/v2/No%C3%A7%C3%B5es-B%C3%A1sicas-do-Git-Desfazer-Coisas 

  ● O arquivo modificado pode ser retornado ao estado original;
  
  ● O comando utilizado é o git checkout;
  
  ● Após a utilização do mesmo o arquivo sai do staging;
  
  ● Caso seja feita uma próxima alteração, ele entra em staging novamente;
  
  
##Ignorando arquivos no projeto https://docs.github.com/pt/get-started/getting-started-with-git/ignoring-files

  ● Uma técnica muito utilizada é ignorar arquivos do projeto;
  
  ● Devemos inserir um arquivo chamado .gitignore na raiz do projeto;
  
  ● Nele podemos inserir todos os arquivos que não devem entrar no 
  versionamento;
  
  ● Isso é útil para arquivos gerados automaticamente ou arquivos que 
  contêm informações sensíveis;

##Desfazendo todas as alterações

  ● Com o comando git reset podemos resetar as mudanças feitas
  
  ● Geralmente é utilizado com a flag --hard
  
  ● Todas as alterações commitadas e também as pendentes serão 
  excluídas;

===================================================================

03 Seção - Trabalhando com Branches https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

##O que é um branch?

  ● Branch é a forma que o git separa as versões dos projetos;
  
  ● Quando um projeto é criado ele inicia na branch master, estamos 
  trabalhando nela até este ponto do curso;
  
  ● Geralmente cada nova feature de um projeto fica em um branch 
  separado;
  
  ● Após a finalização das alterações os branchs são unidos para ter o 
  código-fonte final;

##Criando e visualizando os branches https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository

  ● Para visualizar os branchs disponíveis basta digitar git branch;
  
  ● Para criar um branch você precisa utilizar o comando git branch 
  <nome>;
  
  ● Estas duas operações são muito utilizadas no dia a dia de um dev;
  
##Deletando branches

  ● Podemos deletar um branch com a flag -d ou --delete
  
  ● Não é comum deletar um branch, normalmente guardamos o histórico 
  do trabalho;
  
  ● Geralmente se usa o delete quando o branch foi criado errado

##Mudando de branch https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-base-branch-of-a-pull-request

  ● Podemos mudar para outro branch utilizando o comando git checkout 
  -b <nome>
  
  ● Este comando também é utilizado para dispensar mudanças de um 
  arquivo;
  
  ● Alterando o branch podemos levar alterações que não foram 
  commitadas junto, tome cuidado!

##Unindo branches https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts

  ● O código de dois branches distintos pode ser unido pelo comando git 
  merge <nome>
  
  ● Outro comando para a lista dos mais utilizados;
  
  ● Normalmente é por meio dele que recebemos as atualizações de outros 
  devs;

##Stash https://git-scm.com/docs/git-stash 

  ● Podemos salvar as modificações atuais para prosseguir com uma 
  outra abordagem de solução e não perder o código;
  
  ● O comando para esta ação é o git stash;
  
  ● Após o comando o branch será resetado para a sua versão de acordo 
  com o repositório;

##Recuperando stash

  ● Podemos verificar as stashs criadas pelo comando git stash list
  
  ● E também podemos recuperar a stash com o comando git stash 
  <nome>
  
  ● Desta maneira podemos continuar de onde paramos com os arquivos 
  adicionados a stash;

##Removendo a stash

  ● Para limpar totalmente as stash de um branch podemos utilizar o 
  comando git stash clear
  
  ● Caso seja necessário deletar uma stash específica podemos utilizar git 
  stash drop <nome>

##Utilizando tags https://docs.github.com/en/desktop/managing-commits/managing-tags-in-github-desktop

  ● Podemos criar tags nos branches por meio do comando git tag -a 
  <nome> -m “<msg>”
  
  ● A tag é diferente do stash, serve como um checkpoint de um branch;
  
  ● É utilizada para demarcar estágios do desenvolvimento de algum 
  recurso;

##Verificando e alterando tags

  ● Podemos verificar uma tag com o comando git show <nome>
  
  ● Podemos trocar de tags com o comando git checkout <nome>
  
  ● Desta maneira podemos retroceder ou avançar em checkpoints de um 
  branch

##Enviando e compartilhando tags

  ● As tags podem ser enviadas para o repositório de código, sendo 
  compartilhada entre os devs;
  
  ● O comando é git push origin <nome>
  
  ● Ou se você quiser enviar mais tags git push origin --tags

  ==================================================================

04 Seção - Compatilhamento e atualizações de repositórios


##Encontrando branches

  ● Branches novos são criados a todo tempo e o seu git pode não estar 
  mapeando eles;
  
  ● Com o comando git fetch você é atualizado de todos os branchs e tags 
  que ainda não estão reconhecidos por você;
  
  ● Este comando é útil para utilizar o branch de algum outro dev do time, 
  por exemplo;
  

##Recebendo alterações

  ● O comando git pull serve para recebermos atualizações do repositório 
  remoto;
  
  ● Cada branch pode ser atualizado com o git pull;
  
  ● Utilizamos para atualizar a master do repo como também quando 
  trabalhamos em conjunto e queremos receber as atualizações de um 
  dev;

##Enviando alterações

  ● O comando git push faz o inverso do pull, ele envia as alterações para o 
  repo remoto;
  
  ● Serve também para enviar as atualizações de um branch específico
  para um outro dev;
  
  ● Ou quando terminamos uma tarefa e precisamos enviar ao repositório;

===================================================================

05 Seção - Análise e inspeção de repositório  https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-security-and-analysis-settings-for-your-repository

##Exibindo informações

  ● O comando git show nos dá diversas informações úteis;
  
  ● Ele nos dá as informações do branch atual e também seus commits;
  
  ● As modificações de arquivos entre cada commit também são exibidas;
  
  ● Podemos exibir as informações de tags também com: git show <tag>
  

##Exibindo diferenças

  ● O comando git diff serve para exibir as diferenças de um branch;
  
  ● Quando utilizado as diferenças do branch atual com o remoto serão 
  exibidas no terminal;
  
  ● Podemos também verificar a diferença entre arquivos: git diff <arquivo> 
  <arquivo_b>

##Log resumido

  ● O comando git shortlog nos dá um log resumido do projeto;
  
  ● Cada commit será unido por nome do autor;
  
  ● Podemos então saber quais commits foram enviados ao projeto e por 
  quem;
  

##Utilizando o describe

  ● Com o comando git describe --tags podemos verificar todas as tags do 
  nosso projeto;
  
  ● Com a opção --all recebemos também a referência das tags;
  

==================================================================

06 Seção - Administração de repositórios 

##Limpando arquivos untracked

  ● O comando git clean vai verificar e limpar arquivos não estão sendo 
  trackeados;
  
  ● Ou seja, todos que você não utilizou git add;
  
  ● Utilizado para arquivos que são gerados automaticamente, por 
  exemplo, e atrapalham a visualização do que é realmente importante

##Otimizando o repositório

  ● O comando git gc é uma abreviação para garbage collector;
  
  ● Ele identifica arquivos que não são mais necessários e os exclui;
  
  ● Isso fará com que o repositório seja otimizado em questões de 
  performance;

##Chegando integridade de arquivos

  ● O comando git fsck é uma abreviação de File System ChecK;
  
  ● Esta instrução verifica a integridade de arquivos e sua conectividade;
  
  ● Verificando assim possíveis corrupções em arquivos;
  
  ● Comando de rotina, utilizado para ver se está tudo certo com nossos 
  arquivos;
  

##Reflog

  ● O git reflog vai mapear todos os seus passos no repositório, até uma 
  mudança de branch é inserida neste log;
  
  ● Já o git log, que vimos anteriormente, apenas armazena os commits de 
  um branch;
  
  ● Os reflogs ficam salvos até expirar, o tempo de expiração padrão é de 
  30 dias

##Recuperando arquivos com reflog

  ● Podemos avançar e também retroceder nas hashs do reflog;
  
  ● Para isso utilizamos o comando git reset --hard <hash>
  
  ● Caso você tenha algo que queira salvar, pode utilizar o git stash antes;
  
  ● Lembrando: o reflog expira com o tempo!
  

##Transformando o repositório para arquivo

  ● Com o comando git archive podemos transformar o repo um arquivo 
  compactado, por exemplo;
  
  ● O comando é git archive --format zip --output master_files.zip master
  
  ● E então a master vai estar zipada no arquivo master_files.zip

====================================================================

07 Seção - Markdown  https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

##O que é Markdown?

  ● O Markdown é uma forma de adicionar estilo a textos na web;
  
  ● O arquivo README.md aceita Markdown;
  
  ● Você vai conseguir exibir: trechos de código, links, imagens e muito 
  mais;
  
  ● Dando uma melhor experiência para o usuário nas suas 
  documentações;
  

======================================================================

08 Seção - GitHub Pages https://pages.github.com/

##A importância do commit

  ● O problema: commits sem sentido atrapalham o projeto;
  
  ● Precisamos padronizar os commits, para que o projeto cresça de forma 
  saudável também no versionamento, isso ajuda em:
  
  ● Review do Pull Request;
  
  ● Melhoria dos log em git log;
  
  ● Manutenção do projeto (voltar código, por exemplo);
  

##Branches com commits ruins

  ● Há uma solução chamada private branches;
  
  ● Onde criamos branches que não serão compartilhados no 
  
  repositório, então podemos colocar qualquer commit;
  
  ● Ao fim da solução do problema podemos fazer um rebase;
  
  ● O comando será: git rebase <atual> <funcionalidade> -i
  
  ● Escolhemos os branches para excluir (squash) e renomear com 
  (reword);
  

##Boas mensagens de commit

  ● Separar assunto do corpo da mensagem;
  
  ● Assunto com no máximo 50 caracteres;
  
  ● Assunto com letra inicial maiúscula;
  
  ● Corpo com no máximo 72 caracteres;
  
  ● Explicar o por que e como do commit, e não como o código foi escrito

























































  
