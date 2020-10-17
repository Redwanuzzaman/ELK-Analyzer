## Installation Part

### Install Elasticsearch

wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -

sudo apt-get install apt-transport-https

echo "deb https://artifacts.elastic.co/packages/7.x/apt stable main" | sudo tee 

/etc/apt/sources.list.d/elastic-7.x.list

sudo apt-get update && sudo apt-get install elasticsearch

echo "deb https://artifacts.elastic.co/packages/oss-7.x/apt stable main" | sudo tee /etc/apt/sources.list.d/elastic-7.x.list

wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.9.2-amd64.deb

wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.9.2-amd64.deb.sha512

shasum -a 512 -c elasticsearch-7.9.2-amd64.deb.sha512 

sudo dpkg -i elasticsearch-7.9.2-amd64.deb

Configure : /etc/elasticsearch/elasticsearch.yml

For more information: https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html#install-deb

**Configure : /etc/elasticsearch/elasticsearch.yml**

**Modifications: (uncomment these lines)**

cluster.name: my-application
node.name: node-1
network.host: localhost
http.port: 9200
