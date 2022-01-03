# Git e GitHub

## Aula 01 - Git e GitHub

Git: software de versionamento de código;

GitHub: repositório online;

## Aula 02 - Navegação básica no terminal e instalação

Commnad Line Interface (CLI)

Windows > “cmd” > Prompt de  Comando

- Listar: “dir”
- change directory (navegar entre as pastas): “cd”
- Voltar (navegar): “cd ..”
- limpar a tela: “cls”
- criar uma pasta (make directory): “mkdir”
- criar arquivo: “echo hello > hello.txt”
- deletar arquivos: “del”
- deletar repositório com os arquivos (remove directory): “rmdir”

## Aula 03 - tópicos de funcionamento do Git

SHA (Secure Hash Algorithm): (Algoritmo de Hash Seguro) é um conjunto de funções hash criptográficas projetadas pela NSA;

A encriptação gera conjunto de caracteres identificador de 40 dígitos;

É uma forma curta de representar um arquivo;

“openssl sha1”

### Objetos internos do Git:

BLOBS, TREES e COMMITS

Blobs contém metadados no Git;

Tree armazena blobs;

Commit: aponta para uma tree, parente, autor, mensagem e timestamp (tbm possue um sha1);

## Aula 04 - Chaves SSH e Tokens

- Chave SSH> validação da máquina pelo GitHub
- Token de acesso pessoal

## Aula 05 - iniciando o Git e criando o primeiro commit

No Git Bash “git init”

Com o arquivo criado > Git Bash no repositório > “git add *(todos os arquivos do repositório)” > “git commit -m “comite inicial””

git add “file”

## Aula 06 - Ciclo de vida dos arquivos no Git

git init: criando um repositório

untracked —> unmodified > modified > staged > unmodified...

todos os arquivos que vão para o repositório local tem que estar commitado

“git status” o estado dos arquivos

## Aula 07 - GitHub

Criar repositório = no GitHub criar um novo repositório > copiar a url > abrir o Git Bash no repositório local > “git remote add origin <digitar a url>

[README.md](http://README.md) feito em Markdown

git remote -v (verifcar infos do GitHub)

## Aula 08 - resolvendo conflitos no GitHub

git push origin master

- como baixar repositório do GitHub: botão code > copiar url > Git Bash > “git clone <url>”