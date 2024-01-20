
# Ontologie des assassins

>Kylian BACHELET, Antoine DEPOISIER & Jules FINCK

## Sujet

Avec notre groupe, nous avons décidé de faire une ontologie d'Assassin's Creed avec les différents personnages du jeu, les jeux de la licence, les différentes périodes du jeu et les lieux dans lesquels se déroulent ceux-ci.

Bien sûr, entre tous ces concepts, différentes relations peuvent exister.

## Déploiement

Le site peut être consulté avec l'URL présente : https://confrerie-des-templiers.fly.dev

Si jamais aucun nœud n'apparaît, il faut attendre quelques secondes et recharger les nœuds, le temps que le back soit à nouveau utilisé. Quand une application n'est pas utilisée depuis un moment, fly.io la met en pause.

Dans le cas où le serveur est inactif, il est possible de faire tourner l'application en local.

Pour ce faire, il faut cloner le repo avec ses submodules, ce qui peut être fait avec les commandes suivantes :

```shell
git clone --recurse-submodules git@github.com:NailykSturm/Confrerie_des_templiers_rendu.git
```

Une fois cloné, vous pouvez lancer l'application en effectuant la commande :

```shell
docker-compose up
```

Le serveur sera disponible à l'adresse suivante : http://localhost

## Exploration des fonctionnalités

Nous avons décidé d'afficher uniquement les nœuds les plus intéressants du nœud sélectionné pour avoir un joli affichage en forme de fleur.

Pour se déplacer d'un nœud à un autre, il faut effectuer un clic droit dessus, ce qui dessinera un nouveau graphe.

Si l'on veut des informations sur un nœud, il suffit juste de faire un clic gauche dessus pour afficher la description du nœud.
