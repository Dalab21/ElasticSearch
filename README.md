# ElasticSearch:

L'objectif de ce workshop est de prendre en main la stack Elastic (Elasticsearch & Kibana) en mode local avec des requêtes simples et d'autres d'agrégation plus complexes.

## Contexte du projet
En tant que développeur en intelligence artificielle, Programmer la collecte de données depuis plusieurs sources dont un Big Data pour un projet en intelligence artificielle.

Le logiciel de supervision urbaine de l’entreprise intègre parmi d’autres fonctionnalités une API de recherche d’adresses postales via des requêtes SQL. L’API se connecte à une base de données MSSQL contenant les adresses postales d’une localité et permet donc d’interroger cette base. L’équipe de développement souhaiterait implémenter et tester une méthode autre que les requêtes SQL. L’outil en question est ElasticSearch, un moteur de recherche et d'analyse NoSQL qui utilise Apache Lucene, une bibliothèque open source écrite en Java qui permet d'indexer et de chercher du texte. Elasticsearch est le serveur de recherche le plus utilisé chez les professionnels en juillet 2022 (https://db-engines.com/en/ranking/search+engine). L'indexation et la recherche des données s'effectue à partir d'une API REST. Les données sont conservées sous format JSON.

Le DataSet sera la Base d'Adresses Nationale Ouverte, ou BANO, qui est une initiative d’OpenStreetMap France et a pour objet la constitution d’une base libre la plus complète possible de points d’adresse à l’échelle de la France.
