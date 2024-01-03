# WeatherApp - Application Météo  

Une simple application météo construite avec Laravel qui utilise l'API OpenWeatherMap pour afficher les conditions météorologiques actuelles d'une ville donnée.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Composer](https://getcomposer.org/)
- [PHP](https://www.php.net/)

## Installation

1. Clônez le projet depuis le dépôt GitHub :

    ```bash
    git clone git@github.com:jeanluckawel/weather.git
    ```

2. Accédez au répertoire du projet :

    ```bash
    cd weather
    ```

3. Installez les dépendances avec Composer :

    ```bash
    composer install
    ```

4. Copiez le fichier d'environnement et configurez vos paramètres :

    ```bash
    cp .env.example .env
    ```

    - Ajoutez votre clé API OpenWeatherMap dans le fichier `.env`.

5. Générez une clé d'application Laravel :

    ```bash
    php artisan key:generate
    ```

6. Exécutez le serveur de développement :

    ```bash
    php artisan serve
    ```

7. Visitez [http://localhost:8000](http://localhost:8000) dans votre navigateur.

## Utilisation

- Saisissez le nom de la ville dans le champ de recherche et appuyez sur le bouton pour obtenir les conditions météorologiques actuelles.

## Configuration supplémentaire

- Vous pouvez personnaliser le style et l'interface utilisateur en modifiant les fichiers Blade dans le répertoire `resources/views/weather/`.

## Auteur

[jean luc Kawel]

## Licence

Ce projet est sous licence [MIT](LICENSE).
