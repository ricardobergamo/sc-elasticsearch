# sc_elasticsearch
Biblioteca externa para acesso ao Elasticsearch 6x no Scriptcase v9.

 ### Instalação
  ##### Baixe o repositório no formato .zip
  ##### Crie e configure uma biblioteca externa no Scriptcase com o arquivo .zip (https://www.scriptcase.net/docs/en_us/v9/manual/07-tools/05-external-libraries/)
 
 ### Uso
  ##### Crie uma nova aplicação e insira o código:
  ##### sc_include_library("sys", "elastic", "vendor/autoload.php", true, true);
  ##### $client = \Elasticsearch\ClientBuilder::create()->setHosts(['localhost:9200'])->build();
