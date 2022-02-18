# Objetos internos / Criando um Commit:evergreen_tree:



## Objetos internos 



### Blob

No Git, o conteúdo dos arquivos é armazenado em objetos binários grandes chamados _blobs_.

Os _blobs_ são apenas conteúdos, não registram os metadados.



### Tree

É basicamente uma lista de diretórios, referindo-se a _blobs_ e também a outras _trees_.



### Commit

Mostra um _snapshot_ do repositório, assim como outros metadados, como autoria, mensagens, _timestamp_, entre outros.





## Criando um Commit



### Comando "git init"

Cria um novo repositório do Git.



### Comando "git add"

Adiciona uma alteração no diretório ativo à área de _staging_, para que a alteração possa ser incluída no próximo _commit_.



### Comando "git commit"

Cria um _commit_, ou seja, permite guardar o estado do repositório naquele momento.



