# Passos iniciais para rodar o Git :smile:

## Para começar o processo para criar repositorios no Git/GitHub, devemos criar uma conta no GitHub pelo link https://github.com/. Após isso baixar o Git para o seu computador pelo link https://git-scm.com/

## Após ter configurado a sua conta no GitHub e ter instalado o Git. VocÊ deverá criar uma pasta de trabalho no C: do seu computador. E dentra dessa pasta irá clicar com o botão direito e selecionar a opção Git Bash Here, para abrir o CLI do Git já com o diretório selecionado.

### Vamos agora aos comandos básicos do CLI:

1. Para habilitar o Git na pasta criada devemos começar com comando:
    - git init (irá inicializar e acrescentar a palavra **MASTER** no caminho do diretório)
2. Após precisa utilizar aglum editor de texto pode ser o padrao Windows ou outros editores para extensão MD TYpora e até mesmo o **Visual Studio Code**, bastando acrescentar um leitor para o MD e até mesmo usar a opção para visualizar na tela o arquivo Markdown sendo editado em tempo real;
3. Iremos para o site do GitHub, e criaremos o primeiro repositório, indo na opção: *New* escolhendo um nome para o seu repositório.
4. Após criar o repositório copie o *link* do mesmo, para ser utilziado no Git Bash.
5. Voltando iremos utilziar o editor de texto ou *VsCode*, para acessar a pasta criada e criar o arquivo de **README.md** para colocar informações básicas do repositório.
6. Após a criação do *Readme* podemos criar uma nova pasta e nela colocar os arquivos do repositório em questão. Feita todas as atualziações necessárias para os arquivos. Iremos voltar ao *Git Bash*.
7.  Agora no git bash, podemos comandar com o *git status* e iremos ver que temos arquivos a serem adicionados pois estão **untracked** iremos dar um git add. ou -A para adicionar todos os arquivos e pastas criados.
8.  Apos o add, rodmeos os status novamente, para verificar que estão prontos para o *commit*.
9.  Iremos dar um *commit* git commit -m "*menssagem em relação a mudança ou ao arquivo*" no readme e na pasta criada.
10. Após iremos ver que não tem mais nenhuma ação para ser feita pelo git status, sugerindo somente para fazer o *git push*, restando somente fazer o *push* para o GitHub
11. Vamos utilizar o comando: **git remote add origin (endereço do repositório no GitHub que foi copiado)**
12. Após carregar o repositório no Git falta somente mais um comando para carregar o arquivo no GitHub. Vamos utilizar o comando: **git push origin master**