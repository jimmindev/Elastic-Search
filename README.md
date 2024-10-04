# Getting started with the Elastic Stack and Docker-Compose test

This repo is in reference to the blog [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose)

Please feel free to ask any questions via issues [here](https://github.com/elkninja/elastic-stack-docker-part-one/issues), our [Community Slack](https://ela.st/slack), or over in our [Discuss Forums](https://discuss.elastic.co/).

Pull Requests welcome :)



commande CURL : 
curl -X GET "https://localhost:9200/dep25/_search" -H "Content-Type: application/json" -u elastic:changeme --cacert ca.crt -k -d '{
  "query": {
    "match_phrase": {
      "voie": "Pi\u00E9mont"
    }
  },
  "size": 200
}'


