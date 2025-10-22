# symfonySite1

https://symfony.com/download :
wget https://get.symfony.com/cli/installer -O - | bash
export PATH="$HOME/.symfony5/bin:$PATH"
symfony new --webapp symfonySite1
symfony serve

https://getcomposer.org/download/
https://packagist.org/

-- Créé premiere page / controller
./bin/console make:controller (name:DefaultController ; test:no)


Mèttre a jour la BD : symfony console doctrine:schema:update --force
Nouvelle Classe/Table : symfony console make:entity
Ajouter un Controller : symfony console make:crud / Depuis une classe
