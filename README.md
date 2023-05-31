# Comandos básicos git

Lista dos comandos básicos do git, clonar, commitar, desfazer e etc.

## Clonar o repositório

`git clone https://github.com/fernandomk6/comandos-basicos-git.git`

## Prepara os arquivos para serem "commitados"

`git add . ` adiciona todos os arquivos novos/modificados ou 
`git add readme.md` para adicionar apenas um arquivo.

## Restausa o arquivo para o último commit (desfaz alterações)

`git restore readme.md`

## "Commita" as alterações

`git commit -m "mensagem do commit"`

## Envia os arquivos para o repositório

`git push -u origin main`

## Limpa os comandos do terminal

`clear` 

## Atualiza o repositório local de acordo com o repositorio online

`git pull`

## Traca de brach 

`git checkout NOME_DA_BRANCH`

## Verifica diferenças antes de adicionar (git add .)

`git diff`

*Apertar a tecla Q (quit) para fechar.*

## Unir/fundir/mesclar duas branchs (merge)

`git merge NOME_DA_BRANCH_A_SER_MESCLADA`

Caso esteja na branch main, e execute `git merge another_branch`,
a branch main, passará a ter todas os commits e alterações que existem
na `another_branch`.

