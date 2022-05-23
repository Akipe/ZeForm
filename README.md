# ZeForm

Le but de ce projet est d’aider l’administratrice dans la gestion des inscriptions, en automatisant le processus.

Vous trouverez plus d'informations dans [le cahier des charges](docs/cahier_charge.md) et dans [les cas d'utilisations](docs/cas_utilisation.md).

Le projet est développer en langage *PHP* avec le framework *Slim*.  
Pour plus d'informations, voir le fichier [docs/technologies.md](docs/technologies.md).

## Initialisation du projet
```bash
git clone https://github.com/mdevoldere/ZeForm.git # Téléchargement du projet
cd ./ZeForm

composer install # Installation des dépendances

# On démarre notre serveur de développement
# accessible à http://localhost:8080
composer start
# Ou
php -S localhost:8080 -t public
```
