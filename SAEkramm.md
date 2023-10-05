# Solutions Libres de Collecte, Centralisation et Présentation de Logs

Les logs sont des enregistrements cruciaux pour surveiller, diagnostiquer et sécuriser les systèmes informatiques. De nombreuses solutions libres existent pour collecter, centraliser et présenter ces logs. Dans ce document, nous examinerons plusieurs solutions de collecte, de centralisation et de présentation de logs.

## Collecte des logs :

La collecte et le traitement des logs est une étape primordiale, que ce soit en termes de sécurité ou pour le bon fonctionnement des applications métier.

Il existe plusieurs types de logs :

-   Logs locaux
    
-   Logs de Conteneurs
    
-   Logs de Serveurs Web
    
-   Logs de Base de Données
    
-   Logs de Messagerie
    
-   Logs d’Infrastructure
    
-   Logs d’Applications Spécifiques
    
-   Logs Réseau
    
-   Logs Cloud

&nbsp;
Les logs peuvent permettre plusieurs choses :

-   Suivez le comportement et la vie des utilisateurs,
    
-   identifier et résoudre les problèmes de sécurité,
    
-   Aide à améliorer le diagnostic des pannes et des erreurs,
    
-   Analyser et comprendre les fonctionnalités de l'application ou du service,
    
-   Pour expliquer une erreur dans un système, un service ou une application métier,
    
-   Soyez averti lorsqu'une panne se produit.

## Centralisation des logs

Les logs sont stockés de façon locale sur des fichiers de la machine. Cependant un problème peut vite se présenter : lorsque l’on assure le monitoring de plusieurs applications, ainsi que plusieurs serveurs, on peut vite finir par être submergé.

  

La centralisation des logs est donc une solution qui va consister à rassembler tous les logs d’un groupe de machines sur la même plateforme. Cela permet d’avoir toutes les informations avec une interface unique.

  

Ce processus de centralisation se décompose en plusieurs étapes :

-   La génération des logs : vous choisissez les logs à produire selon les objectifs et besoins du projet.
    
-   La collecte : les logs sont ensuite envoyés vers une plateforme commune. La transmission est définie par des règles et réalisable avec des protocoles spécifiques.
    
-   Le filtrage : vous analysez et filtrez les différentes metrics et variables pour répondre aux besoins spécifiques du monitoring.
    
-   La présentation des données : cette étape permet de créer des dashboards personnalisés regroupant les données synthétisées, pour permettre de lire et comprendre les données des logs


## ELK Stack

Outil d’analyse de logs composé de 3 logiciels open source, développés par la société Elastic : Elasticsearch, Logstach et Kibana

Communauté Associée : Grande communauté open source.

Elasticsearch va permettre d’extraire les données, Logstash normalise toutes sortes de données temporelles et Kibana apporte un insight.

ElasticSearch est un moteur de recherche et d’analyse qui utilise le format JSON. Son objectif est d’extraire efficacement les données à partir de sources de données structurées ou non structurées en temps réel. Elasticsearch utilise Lucene pour fournir les capacités de recherche en texte intégral les plus puissantes disponibles dans n'importe quel produit open-source.

Logstash est un outil pour la saisie, le traitement et la sortie des données logs. Sa fonction est d’analyser, filtrer et découper les logs pour les transformer en documents formatés à destination d’Elasticsearch.

 
Kibana est un tableau de bord interactif et paramétrable qui permet de visualiser les données stockées dans ElasticSearch. Kibana apporte un insight sur les tendances et les modèles sous toutes formes de diagrammes et courbes. Ce dashboard peut être partagé et associé à des visualisations de données pour une communication rapide et intelligente

## Conclusion

Le choix de la solution de collecte, centralisation et présentation de logs dépendra des besoins spécifiques de votre environnement. ELK Stack offre une puissante capacité de recherche et de visualisation

Il est essentiel de prendre en compte la complexité de la configuration initiale, les ressources requises et les fonctionnalités spécifiques pour prendre une décision éclairée. Chacune des solutions a une communauté active qui peut fournir un support et des extensions utiles pour répondre aux besoins de votre infrastructure.
