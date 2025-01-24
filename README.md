# BIGDATA_WITH_KAFKA_AND_SPARK

Ce projet illustre le traitement de données volumineuses en utilisant Apache Kafka et Apache Spark. Il est conçu pour démontrer comment ces technologies peuvent être intégrées pour gérer et traiter des flux de données en temps réel.

## Table des matières
- [Technologies Utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exemples](#exemples)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Technologies Utilisées
- **Apache Kafka** : Pour la gestion des flux de données.
- **Apache Spark** : Pour le traitement des données.
- **Scala** et **Python** : Langages de programmation utilisés.
- **Docker** : Pour le déploiement des services.
- **Minio** : Pour le stockage d'objets.

## Installation

### Prérequis
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

### Cloner le dépôt
```bash
git clone https://github.com/Babacarsar/BIGDATA_WITH_KAFKA_AND_SPARK.git
cd BIGDATA_WITH_KAFKA_AND_SPARK
```

### Lancer les services
```bash
docker-compose up
```

## Utilisation

1. Configurez vos producteurs et consommateurs Kafka dans les fichiers de configuration.
2. Utilisez les scripts Python ou Scala pour envoyer et traiter les données.

## Exemples

Des exemples de code et des cas d'utilisation sont fournis dans le répertoire `examples`.

## Contribuer

Les contributions sont les bienvenues ! Veuillez soumettre une demande de tirage (pull request) avec vos modifications.

## Licence

Ce projet est sous licence [MIT](LICENSE).
