# sc_elasticsearch
Biblioteca externa para acesso ao Elasticsearch 6x no Scriptcase v9.

 ### Instalação
 
  ###### Baixe o repositório no formato .zip
  ###### Crie uma biblioteca externa no Scriptcase com o nome 'elasticsearch' 
  ###### Faça o upload do arquivo .zip para a nova biblioteca, ative e salve.
  
 ### Uso
 
  ###### Crie uma nova aplicação e insira o código:
  ###### sc_include_library("sys", "elasticsearch", "vendor/autoload.php", true, true);
  ###### $client = \Elasticsearch\ClientBuilder::create()->setHosts(['localhost:9200'])->build();

### Documentação

 ###### Scriptcase: https://www.scriptcase.net/docs/en_us/v9/manual/07-tools/05-external-libraries/
 ###### Elasticsearch-PHP: https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/index.html
