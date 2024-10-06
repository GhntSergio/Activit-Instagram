# Projet de Suivi d'Activité Instagram avec Selenium

## Contexte

Instagram est une plateforme de médias sociaux populaire où les utilisateurs interagissent en regardant des vidéos, en les likant, et en se connectant fréquemment. Afin de mieux comprendre son propre comportement sur la plateforme, ce projet utilise **Selenium**, un outil d'automatisation de navigateur, pour surveiller les interactions sur Instagram.

## Objectifs

- **Suivre le nombre de connexions** à votre compte Instagram.
- **Mesurer le temps total passé** sur Instagram.
- **Compter le nombre de vidéos regardées** pendant la session.
- **Calculer le nombre de vidéos likées** pendant la session.

## Prérequis

- **Python** installé sur votre machine.
- **Selenium** pour l'automatisation du navigateur.
- **WebDriver** approprié pour votre navigateur (par exemple, [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) pour Google Chrome).

## Démarche du Projet

### Configuration de Selenium

1. **Initialiser le navigateur** et naviguer vers Instagram.
2. **Se connecter au compte Instagram** en utilisant les informations d'identification fournies.

### Surveillance de l'Activité

1. **Suivre les interactions** de la session en détectant les vidéos vues et les vidéos likées.
2. **Compter et enregistrer** le nombre de fois où vous vous connectez et le temps total passé.

### Collecte et Rapport des Données

1. Après la fin de la session, **calculer le temps total passé** et afficher les statistiques collectées.

## Explications

- **Initialisation** : Le script démarre une instance de Chrome et accède à Instagram.

- **Connexion** : Le script entre les identifiants de connexion et se connecte à votre compte.

- **Surveillance** :
  - La fonction `check_activity()` surveille les vidéos vues et les likes toutes les minutes.
  - La variable `connection_count` est incrémentée à chaque vérification pour suivre les connexions.

- **Reporting** : À la fin de la session (interruption avec `Ctrl+C`), le script affiche le nombre total de connexions, vidéos regardées, likes, et le temps total passé.

- **Avertissements**
Assurez-vous de respecter les conditions d'utilisation d'Instagram et les règles de confidentialité lorsque vous collectez des données. L'utilisation abusive d'outils d'automatisation peut entraîner la suspension ou le blocage de votre compte.

**Note** : Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une issue sur le dépôt GitHub.

## 📜 Licence

Ce projet est sous la [Licence MIT](https://github.com/GhntSergio/All-projets/blob/main/Activit%C3%A9%20Instagram/LICENSE.md). Voir le fichier [LICENSE.md](https://github.com/GhntSergio/All-projets/blob/main/Activit%C3%A9%20Instagram/LICENSE.md) pour plus de détails.


Ce README utilise des sections claires et structurées pour présenter le projet, avec des instructions sur la façon de configurer et d'utiliser le script. Assurez-vous d'ajuster les liens et les noms en fonction de votre propre dépôt GitHub et des détails spécifiques de votre projet.
