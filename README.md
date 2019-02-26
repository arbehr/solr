# solr

1. Instalar Solr: https://tecadmin.net/install-apache-solr-on-ubuntu/ , mudando a versão para 7.7.0 ou a última que estiver disponivel no site
2. Subir o servidor com o comando:
   
   <br /> sudo -u solr bin/solr start
   
<br /> Obs: É preciso estar na pasta do Solr onde existe a pasta bin. 


3. Adicionar os cores pro Solr com os comandos

   <br /> sudo -u solr bin/solr create -c Document
   <br /> sudo -u solr bin/solr create -c DocumentDto
   <br /> sudo -u solr bin/solr create -c DocumentTinyDto
   <br /> sudo -u solr bin/solr create -c Files
   <br /> sudo -u solr bin/solr create -c User

4. Subir o projeto como de costume(Maven clean package e rodar o spring boot)
