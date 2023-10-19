Ce projet a pour objectif de refondre un site web similaire à Indeed en utilisant le framework Symfony.
C'est la première fois que j'utilisais symfony

Installation :

Clonez le dépôt sur votre machine locale :
git clone https://github.com/QUsOK/Job_board.git

Installez les dépendances avec Composer :
composer install

Créez la base de données et exécutez les migrations :

----- ATTENTION -----
Le fichier /config/packages/doctrine.yaml qui appel la base de donnée doit être créer et ajuster à votre système

Une fois cela fait :
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate

Enfin démarrer le server :
php bin/console server:start
