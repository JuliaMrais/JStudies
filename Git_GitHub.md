# Git

O Git é um Sistema de Versionamento de Arquivos, ou seja, é um sistema que gerencia o estado e as mudanças que ocorrem em qualquer tipo de arquivo.

## Começando com o Git

Para que um repositório(Pasta) seja gerenciado pelo Git é necessário que iniciemos um "respositório Git", então para iniciarmos o Git, devemos abrir nosso terminal e usar o comando:
```console
    user@user-pc:~/Documents/Folder$ git init 
```
Após iniciarmos um repositório git, todos os arquivos naquela pasta começam a ser monitorados pelo git. 
Para vermos o estado de determinados arquivo usamos: 

```console
    user@user-pc:~/Documents/Folder$ git status 
```
Com a checagem de estado, temos a seguinte resposta: 

```console
    On branch master
        Changes not staged for commit:
        (use "git add <file>..." to update what will be     
        committed)
        (use "git checkout -- <file>..." to discard changes 
        in working directory)

            modified:   Git_GitHub.md

        no changes added to commit (use "git add" and/or 
        "git commit -a")

```