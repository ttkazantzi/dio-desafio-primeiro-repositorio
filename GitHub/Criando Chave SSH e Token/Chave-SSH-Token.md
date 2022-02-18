# Criando uma Chave SSH / Token :closed_lock_with_key:



## Criando uma Chave SSH



1.  No Git Bash, executar o comando "ssh-keygen -t ed25519 -C" + e-mail

   

2.  Não é necessário escolher local ou colocar senha

   

3.  Usar comando "cd /c/Users/__/ .ssh/" para acessar o diretório onde a chave foi salva

   

4.  Usar comando "cat id_ed25519.pub" para mostrar a chave pública

   

5.  Nas configurações da conta do GitHub, acessar a página "SSH and GPG keys"

   

6.  Adicionar a chave pública gerada no Git Bash

   

7.  No Git Bash, usar o comando "eval $(ssh-agent -s)"

   

8.  Usar o comando "ssh-add id_ed25519"





## Criando um Token



1.  Nas configurações da conta do GitHub, acessar "Developer settings" e depois "Personal access tokens" e "Generate new token"

   

2.  Adicionar nota, selecionar data de expiração e marcar a opção "repo"

   

3.  Clicar em "Generate token"

   

4.  Salvar o token em um local seguro

   

5.  O token não poderá mais ser visualizado no GitHub



