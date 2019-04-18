# sc_elasticsearch
Biblioteca externa para acesso ao Elasticsearch 6x no Scriptcase v9.

 ## Instalação
 * Baixe o repositório no formato .zip (sc_elasticsearch-master.zip);
 * Renomeie o arquivo 'sc_elasticsearch-master.zip' para 'vendor.zip'
 * Crie uma nova biblioteca externa pública no Scriptcase com o nome 'elasticsearch;
 * Edite a biblioteca e faça o upload do arquivo vendor.zip;
 * Ative a biblioteca'elasticsearch' com a opção 'Usar biblioteca' e salve;
  
 ## Uso
 
 * Crie uma nova aplicação e insira o código:
 ##### sc_include_library("sys", "elasticsearch", "vendor/autoload.php", true, true);
 ##### $client = \Elasticsearch\ClientBuilder::create()->setHosts(['localhost:9200'])->build();

## Documentação

 * Scriptcase: https://www.scriptcase.net/docs/en_us/v9/manual/07-tools/05-external-libraries/
 * Elasticsearch-PHP: https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/index.html
