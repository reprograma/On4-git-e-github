# On4-git-e-github

# T8-javascript-IV
Turma Online 4 | Front-end | 2019 | Semana 3 | Git e Github

Esse conteúdo foi feito com referência nos seguintes materiais:
 - [Turma Online 1 - Github](https://github.com/reprograma/CursoOnline-Aula3-Git-and-Github)
 - [Turma Online 2 - Github](https://github.com/reprograma/On2-git-e-github)
 - [Turma Online 3 - Github](https://github.com/reprograma/On3-git-e-github)
 - [Turma 6 - Github](https://github.com/reprograma/github)

## [Aula 1 - 09/11/2019](#aula-1)
### Resumo
Nessa aula veremos? 
* [Git](#git)
* [Linha de comando](#linha-de-comando)
* [Github](#github)

## Aula 1
### Git 
* [O que é ?](#o-que-é-?)
* [Instalação](#instalação)
* [Git Bash](#git-bash)
* [Github](#github)

#### O que é ?
<img src="./imgs/git.png" height="150" />

    Git é um sistema de controle de versões, criado pelo mesmo desenvolvedor do linux(Linus Torvalds), usado principalmente no desenvolvimento de software para versionar código e registrar o histórico de edições dos arquivos.
    Com ele conseguimos desenvolver projetos colaborativos, no qual muitas pessoas podem trabalhar simultaneamente no mesmo código, adicionando e removendo conteúdos e novos arquivos. Também podemos a opção de consultar o histórico do que e quando foi modificado e até restaurar versões anteriores. 
    Para fazer uma comparação com ferramentas que já utilizamos no dia a dia, ele é muito semelhante ao Google Drive/Docs, onde muitas pessoas podem editar arquivos e editar documentos.

    
Vantagens:
 - **Trabalho em equipe**: Diversos desenvolvedores trabalhando no mesmo projeto sem perder o que cada um fez
 - **Organização** : O Git cria uma timeline com todas as modificações contendo detalhado que arquivos foram modificados de versão para versão,  height="150"
 #### Instalação
  - Para Linux/Unix: https://git-scm.com/download/linux
  - Para Mac: https://git-scm.com/download/mac
  - Para Windows: https://git-scm.com/download/win
<img src="./imgs/git-page.png" />

- Seguindo os passos para windows:
    - Instalar o arquivo .exe baixado:

    <img src="./imgs/git-exe.png" />
    
    - Abrir o Git Bash

    <img src="./imgs/bash-here.png" />

#### Git Bash
  <img src="./imgs/gitbash.png" width="200"/>

  É um software para utilizar as linhas de comando do Git além de alguns comandos Unix, necessário principalmente no Windows, já que inicialmente o Git foi desenvolvido para o Linux.

### Linha de comando 
* [O que é ?](#o-que-é-linha-de-comando-?)
* [Comandos básicos](#comandos-básicos-do-terminal)

#### O que é linha de comando ?
  <img src="./imgs/terminal.png"/>

  É aquela tela preta que aparece nos filmes, normalmente com alguém hackeando algum sistema. Mexer com o terminal assusta um pouco porque ele não é nem um pouco visual. Mas é muito simples mexer nele. Sabe quando a gente arrasta arquivos para uma pasta ou cria uma pasta nova? No terminal você faz tudo isso também, mas sem interface gráfica. A gente insere comandos, e ele executa.
  
  Na linha de comando você controla melhor o que está rolando com o seu computador - inclusive o versionamento. O git é sempre usado através de linha de comando. (Existem outras ferramentas visuais para uso do Git, mas é importante saber se virar pela linha de comando no dia-a-dia)
```
ls - Listar (ele traz uma lista de tudo o que está naquela pasta - documentos, outras pastas, etc)
pwd - Present working directory (onde estou?) Ele traz todo o caminho onde você está (em que pasta e onde essa pasta fica)
mkdir nome-da-pasta - cria uma pasta
cd - change directory (use para se locomover entre as pastas)
cd ~ - volta para a pasta raiz
cd .. - volta uma pasta
cd nome-da-pasta - para entrar em uma pasta específica (você precisa conseguir enxergar ela quando listar os arquivos)
rm arquivo - remove, deleta um arquivo.
rm -f ou rm --recursive pasta: deleta uma pasta
whoami - "quem sou eu?" identifica o usuário que está mexendo no sistema.
```
#### Github
GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que programadores ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. É a partir dele que hospedaremos nosso repositório local para um online.
GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com projetos.

Vamos nos cadastrar para conseguirmos subir nossos códigos para um repositório online.

Após o cadastro configuraremos nosso usuário no gitbash para definir a autoria das nossas modificações:
Para adicionar usuário:
```
git config --global user.name "Natalya Peixoto"
git config --global user.email “natalya_peixoto@hotmail.com” 
```

```
git config --list
```

Para remover usuário:
```
git config --global --unset user.name "Natalya Peixoto"
git config --global --unset user.email “natalya_peixoto@hotmail.com” 
```
