# scrapyLBC

## Description

Création du Repo pour la connexion du site [Leboncoin.fr](https://www.leboncoin.fr) via [Scrapinghub.com](https://www.scrapinghub.com).

Pour extraire les données, scrapyLBC utilise le framework collaboratif et opensource [Scrapy](https://github.com/scrapy/scrapy).

## Installation

Pour télécharger et exécuter le script dans un shell :

```shell
git@github.com:Sigri44/scrapyLBC.git
```

## Getting started

Lancer le spider scrapyLBC.py en utilisant la commande runspider :

```shell
scrapy runspider scrapyLBC.py -o data.json
```

Les colonnes peuvent être écrites dans un fichier json ou csv:

```
'Url':
'Titre'
'Prix'
'Surface'
'GES'
'Classe énergie'
'Auteur'
'Téléphone'
'Remarques'
```

## Requirements

 * Python3
 * Scrapy==1.4.0

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
