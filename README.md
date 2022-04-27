## :page_facing_up:Repositório para BootCamp Philips da DIO

Criado para acompanhar o avanço e manter as atividades criadas durante do BootCamp atualizadas.



#### :mag:Links Úteis

[Sintaxe Markdown](https://www.markdownguide.org/basic-synt)

[Downloads GitHub](https://git-scm.com/downloads)

[Site GitHub](https://github.com/)

[Download Editor de Texto Markdown Typora](https://typora.io/)

[Download Editor de Texto Notepad++](https://notepad-plus-plus.org/downloads/)



#### :pencil2:Informações Sobre Editor De Texto Markdown(.md) Que Utilizei

- Editor de Texto Markdown Typora solicita exige licença ou é utilizado como trial durante 15 dias.

- Editor de Texto Notepad++ e gratuito, no entanto deve ser baixando o plugin para edição Markdowne Visualição inline.

- Lista de  [emoticons](https://gist.github.com/rxaviers/7360908)

  

#### :bulb:Informações Úteis

1. Baixar e instalar o GitHub no equipamento que irá utlizar, a instalação é padrão, após instalado procura pela aplicação GIT Bash, ela e linha de comando como o CMD do Windows.

2. Criar um perfil no site do GitHub, após criado procure onde cria um repositorio se for o caso já o crie, lembrando que ele pode ser Público ou Privado, dependo do projeto pode ser criando sem o README ou com ele.

3. Comandos Básicos no CMD que tmbém são utilizados no GIT Bash, lembarndo que estou utilizando um equipamento Windows:

   - **cd** - navega entre as pastas, variantes **cd..** que retorna pastas
   - **dir** ou **ls** - lista os arquivos nas pastas, variante **ls -a** que lista também os arquvios ocultos
   - **Ctrl+L** - limpa a tela do prompt de comando
   - **mkdir** - cria uma pasta
   - **rmdir** - deleta pasta
   - **echo** - retorno o que é inserido, serve para criar arquivos exemplo: echo hello > hello.txt em que hello e o texto escrito dentro do arquivo que foi criado hello.txt
   - **pwd** - mostra o diretorio que você está

4. Configurando o Git/GitHub com chave SSH:

   - Comando para gerar a chave SSH, e criado duas chaves publica(.pub) e privada a chave publica e que utilizaremos, no momento da criação e solicitado a criação de senha não esquecer ela.

     > ssh-keygen -t ed25519 -C "e-mail de preferencia o mesmo do GITHub"

   - Navegue até o diretorio que foi criado as duas chaves e use o comando abaixo para ler o conteudo da chave para depois ser colado no site do GIHub nas configurações SSH e add no campo key

     > cat id_ed25519.pub

   - Agora devemos executar o agente no GitBash

     > eval $(ssh-agent -s)

   - Após execução do agente devemos executar o privada será solicitado a senha que foi criada

     > ssh-add id_ed25519

   - Com essa configuração não será necessário  entrar com autenticação do GITHub todo o tempo

5. Comandos do Git para tratar os arquivos

   - **git init** - inicia o versionamento de todos os arquivos dentro da pasta que está sendo executado
   - **git config --global user.email "emaildo@github"** - configura os arquivos com o e-mail do usuário
   - **git config --global unset user.email** - se necessário limpa a configuração de e-mail acima podendo ser inserido um novo e-mail na configuração
   - **git config --global user.name "NomeDoPerfilGitHub"** - configura os arquivos com o nome do usuário
   - **git config --global unset user.name** - se necessário limpa a configuração de nome acima podendo ser inserido um novo nome na configuração
   - **git config --list** - mostra as configurações que foram setadas, para sair use a tecla ***q***
   - **git add * ** - adiciona todos os arquivos para stage onde pode ser commitado
   - **git status** - mostra a situação dos arquivos, Untracked, Tracked, Stage
   - **git commit -m "Informação para deixar documentado"** - assina os arquivos, sempre commitar antes de subir para o repositorio na nuvem do GitHub
   - **git remote add origin mais link do repositorio no GitHub** - caso o repositorio esteja vazio será populado, ou seja, será enviado para a nuvem
   - **git remote -v** - mostra a lista de repositorios que tem cadastrado
   - **git push origin master** - se o repositorio está criando e populado somente este comando para fazer o updade do local para o remoto
   - **git clone mais url do repositorio** - clona o repositorio da nuvem para o local, trazendo todas as configurações
   - **git pull origin master** - faz o download da nuvem para o local, sendo que o local já está confingurado
   - Utilizei esse sequencia de comandos e deu certo



#### :walking:Trilha Do BootCamp

- [x] Boas Vindas ao Bootcamp Philips Fullstack Developer You Are You
- [x] Mentoria #1: Aula Inaugural - Philips Fullstack Developer You Are You
- [x] Lógica de Progamação Essencial
- [x] Pensamento Computacional
- [x] Introdução ao Git e ao GitHub
- [x] Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso
- [ ] Introdução a Criação de Websites com HTML5 e CSS3
- [ ] Construindo Páginas Para Internet Com Bootstrap
- [ ] Posicionando Elementos com Flexbox em CSS
- [ ] Sintaxe Básica em JavaScript
- [ ] Sintaxe e Operadores
- [ ] Variáveis e Tipos
- [ ] Trabalhando com Módulos em JavaScript
- [ ] Funções
- [ ] Coleções
- [ ] Debugging e Error Handling
- [ ] Orientação a Objetos
- [ ] JavaScript Assíncrono
- [ ] Desafios de Código Iniciais  JS
- [ ] Recriando o Famoso Jogo do Dinossauor sem Internet
- [ ] Introdução ao TypeSript: Explorando Classes. Tipos e Interfaces
- [ ] Introdução ao Angular 8
- [ ] A Arquitetura de Componentes e a Gestão da Complexidade no Front-End
- [ ] Explorando Diretivas com Angular
- [ ] Trabalhando com Páginas SPA com Angular
- [ ] Implementando Serviços e Injeçao de Dependêmcias com Angular
- [ ] Introdução a SErviços Assíncronos no Angular
- [ ] O Poder do Data Binding no Angular
- [ ] Trabalando com Componentes em Angular
- [ ] Criação de Pipes com Angular
- [ ] Desafios de Código Intermediaários JS
- [ ] Como criar um front-end de um e-commerce utlizando Angular
- [ ] SQL SERVER Criando suas primeiras consultas
- [ ] Modelando um banco de dados na prática com SQL SERVER
- [ ] SQL SERVER Boas práticas em bancos relacionais
- [ ] Dominaod IDEs Java
- [ ] Introdução ao Ecossistema e Documentação Java
- [ ] Configurando Ambiente de DesenvolvimentoJava no Linux
- [ ] Resolvendo Desafios de Códgo em Java
- [ ] Desafios de Código Iniciais Java
- [ ] Variáveis, Tipos de Dados e Operadores Matematicos em Java
- [ ] Entendo Métodos Java
- [ ] Lógica Condicional e Controle de Fluxos em Java
- [ ] Estruturas de REpetição e Arryas em Java
- [ ] Praticando Orientação a Objetos com Java
- [ ] Criando um Banco Digital com Java e Orientação a Objetos
- [ ] Debugging Java
- [ ] Tratamento de Exceções em java
- [ ] Desagios de Código Intermediários Java
- [ ] Abstraindo um Bootcamp Usando Orientação a Objetos em Java
- [ ] Introdução ao Spring Framework
- [ ] Introdução ao Framework Spring Boot
- [ ] Simplificando Projetos Java com o Spring Boot
- [ ] Imersão no Spring FrameWrok com Spring Boot
- [ ] Praticando Orientação a Objetos com Java

:thumbsup: 

