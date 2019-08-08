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
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	text.txt

nothing added to commit but untracked files present (use "git add" to track)
```

Com a resposta podemos notar X coisas:

1. Estamos no "branch" principal (master).
1. Há um arquivo modificado ou recém adicionado chamado `Text.txt`.
1. Alguns comandos para podermos atualizarmos o repositório.

Quando temos um *Untracked File* significa que este arquivo não está sendo gerenciado pelo Git, e para adicionarmos ele dentro do nosso repositório Git devemos fazer o uso de um dos seguintes comandos:

```console
    user@user-pc:~/Documents/Folder$ git add Text.txt 
    user@user-pc:~/Documents/Folder$ git add .
    user@user-pc:~/Documents/Folder$ git add -A
```
1. `git add 'file_name.format'` - Adiciona apenas o arquivo digitado
2. `git add . ` - Adiciona todos os arquivos e novas alterações
3. `git add -A` - Adiciona todas as mudanças feitas (seja modificações, alterações e até remoções e arquivos)