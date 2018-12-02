# Versionando com Tags

Defini um marcador para os commit's.

git tag

$ git tag -a 1.0.0 -m "Readme finalizado"

-a --> Anotated

-m --> Message

$ git push origin master --tags
O comando subirá as novas tags para o repositório remoto.
Note que na página do repositório a nova tag irá refletir na atualização do **release**

$ git tag 
--> Mostra as tags criadas
