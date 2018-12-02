# GitHub Course

Arquivo da aula de Git e Github para iniciantes.

Este é um repositório teste para ver como o git funciona.

Saiba mais em [willianjusten.com.br](http://willianjusten.com.br)
Gostou do curso? Quer mais? ajude com uma doação, até um café é válido =)


Alterações feitas no arquivo, pode ser retirada utilizando o comando - git checkout.

***Revisando como desfazer alterações nos arquivos, utilizando o comando [git checkout]***

Arquivos alterados que foram "Add" podem ser retornadas da área de unstage com o comando reset HEAD.

**git reset**

--soft  --> Reseta o commit realizado, retornando os arquivos para a área de unstage.

--mixed --> Reseta o commit realizado, retornando os arquivos para a área de modified.

--hard  --> Reseta o commit realizado, apagando todas as alterações feitas nos arquivos 
            e limpa a informação do commit no log.

***Entendendo o funcionamento dos BRANCHES***

**-> Criando um novo branch**
[comando:] git checkout **-b** <nomeDoBranch>