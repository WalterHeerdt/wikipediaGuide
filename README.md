# # Application Wikipedia de géolocalisation

Cette application est conçue pour afficher l'introduction de la page Wikipedia d'un lieu en fonction de la géolocalisation du smartphone. Si la géolocalisation n'est pas disponible, l'utilisateur peut entrer manuellement le nom du lieu.

## Prérequis

- Python 3.x
- Les bibliothèques `geopy` et `wikipedia-api`

## Installation

1. Clonez ou téléchargez ce dépôt sur votre machine.

2. Installez les dépendances en exécutant la commande suivante :

pip install geopy wikipedia-api

markdown
Copy code

## Utilisation

1. Naviguez vers le répertoire du projet.

2. Exécutez le script principal :

python wikipedia.py

markdown
Copy code

3. Si la géolocalisation est disponible, l'introduction de la page Wikipedia du lieu sera affichée.

4. Si la géolocalisation n'est pas disponible ou si vous souhaitez rechercher un autre lieu, vous serez invité à entrer manuellement le nom du lieu.

5. L'introduction du lieu sera affichée à l'écran et enregistrée dans un fichier PHP appelé `information.php`. Ce fichier sera créé s'il n'existe pas ou mis à jour avec de nouvelles informations si nécessaire.

## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet ou signaler des problèmes, veuillez soumettre une demande d'extraction ou ouvrir une issue.

## Licence

Ce projet est sous licence MIT. Veuillez consulter le fichier [LICENSE](LICENSE) pour plus de détails.
