# Tutorial Github por PyLadies Goiânia
<img src= "https://user-images.githubusercontent.com/53278878/71999188-b88f5e80-321f-11ea-937d-123ba0adfa13.gif" height="90">

## O que é esse tal de Git e GitHub?
**Git** é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

E o **GitHub** é um serviço web onde é possível trabalhar em equipe e compartilhar códigos. O github oferece diversas funcionalidades extras aplicadas ao git. Foi responsável pelo crescimento do open source. 

**Todo mundo usa essa plataforma.**

## O Workflow
No git, utilizamos os conceitos de **commits**, **branches** e **merges** para trabalhar com as versões de código.

![workflow](https://user-images.githubusercontent.com/53278878/72151359-c57a9200-3386-11ea-9326-d9d6e43316ae.png)

Um **commit** é um pacote de alterações feitas no repositório. Cada commit possui arquivos alterados, autor e uma mensagem de resumo.

O **branche** é um galho da árvore de desenvolvimento. É um cópia de um certo ponto do "galho" principal (master) que é utilizado para a aplicação de mudanças no código, preservando a integridade do código no branch principal. É comum chamarmos o branch de versão de trabalho. **Não é recomendado muitas branches em um projeto**

O **merge** é a ação de fundir duas branches, adicionando todo o código de uma branch a outra branch por meio do git. Merges podem funcionar perfeitamente, mas algumas vezes o git pode ficar confuso e gerar um conflito quando tenta fazer um merge. 


## Como instalar o Git
Linux
> sudo apt-get install git

Windows
> clique neste [link](https://gitforwindows.org/)

## Como configurar o Git
>git config --global user.name "YOUR NAME"

>git config --global user.email "YOUR EMAIL ADDRESS"

## Principais comandos

### Criar um repositório
> git init

### Clonar um repositório
> git clone URL DO REPOSITORIO

### Adicionando um arquivo/diretório no repositório
Arquivo
> git add meu_arquivo.txt

Diretório
> git add meu_diretorio

Adicionar tudo
> git add .

### Commits
Exibe o status do seu repositório atual
> git status

> git commit -m "algum comentário/nome do commit"

### Mandando de volta para o GitHub
> git push origin [nome do branch]

### Atualizando o repositório local
> git pull

## Links de referência

* [Git - Guia Prático](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
* [Site Oficial do Git](https://git-scm.com/)
* [Tudo o que você precisa saber sobre Git e Github](https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)
* [Git, primeiros passos](https://brorlandi.github.io/2017/03/12/Git-primeiros-passos/)
