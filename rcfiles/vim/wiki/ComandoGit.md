
Comandos git

##update local repo with github updates

    git pull origin master

##Shallow clone

    git clone --depth 1 https://github.com/voyeg3r/dotfiles

##como ver o que mudou em um arquivo

    git log --follow -p --  bin/get-1000-phrases.sh

## acessar uma linha específica de um arquivo do github 

    https://github.com/atomaka/dotfiles/blob/master/Makefile#L10

    Como visto acima basta colocar no final da url #Ln  "onde n é
    o número da linha"
