# problema 1 - b
    tar -xzf challenges.tar.gz

* descompacta a pasta challenges.tar.gz

# problema 2 - b
    cd challenges

* muda o diretório para "challenges"

# problema 3 - b
    ls

* lista os conteúdos do repositório

# problema 4 - b
    mkdir foo

* cria um novo repositório chamado "foo"

# problema 5 - I 
    mkdir -p foo/bar/1/2/3

* cria um novo diretório com estrutura foo/bar/1/2/3

# problema 6 - b
    rm-rf foo

* apaga o repositório foo e todos seus conteúdos

# problema 7 - b
    echo "Hello World"

*  printa hello world

# problema 8 - b
    echo Hello World > hello.txt

* cria um arquivo hello.txt com Hello World dentro

# problema 9 - b 
    touch empty.txt

* cria um arquivo vazio 

# problema 10 - b
    rm empty.txt

* apaga o arquivo empty.txt    

# problema 11 - I 
    : > empty.txt

* 2° maneira de criar um arquivo vazio

# problema 12 - I
    printf ' ' > empty.txt

* 3° maneira de criar um arquivo vazio

# problema 13 - b 
    cp hello.txt goodbye.txt

* copia hello.txt para goodbye.txt

# problema 14 - b
    mv goodbye.txt hello_copy.txt

* renomeia goodbye.txt para hello_copy.txt

# problema 15 - I
    diff hello.txt hello_copy.txt

* prova que os arquivos são iguais

# problema 16 - b
    cat hello.txt hello_copy > 2_hellos.txt


* concatena os dois arquivos
    cat 2_hellos.txt
* conferir

# problema 17 - b  
    pwd 

* mostra o caminho completo do diretório

# problema 18 - b
    ls -l

* lista os conteúdos do diretório, mostrando as permissões para cada arquivo

# problema 19 - b 
    echo "Hello World " >> restricted.txt

acrescenta Hello World ao final de restricted.txt