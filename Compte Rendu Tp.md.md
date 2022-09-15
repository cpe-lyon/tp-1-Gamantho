# Compte rendu TP 

## Exercice 2 

### Manuel :

**Question 1 :**
 On cherche à comprendre l'utilité de la commande which,
on va donc utiliser le manuel de linux. On rentre la commande -man which, la commande which nous permet d'afficher le chemin du fichier dans l'environnement actuel.

**Question 2 :** 

**Question 3 :** 
On nous demande comment quitter le manuel, il suffit simplement d'appuyer sur la touche q du clavier.

**Question 4:**
On nous dit que chaque section du manuel à une première page qui représente le contenu de la section, pour afficher la page d'introduction de la section 6 on utilise la commande -man 6 intro. La section 6 est attribué au jeux de linux.

### Navigation dans l'arborescence des fichiers :

**Question 1**
On doit se rendre dans le dossier /var/log, pour cela on va utiliser la commande -cd /var/log.

**Question 2**
On nous demande de revenir dans le dossier var e utilisant un chemin relatif, on utilise donc la commande -cd ..

**Question 3**
On doit revenir dans le dossier personnel pour cela on utilise la command -cd ~ .

**Question 4**
Pour revenir au dossier précédent sans utiliser de chemin on utilise la commande -cd - .

**Question 5**
Pour accéder au dossier root on utilise la commande -cd /root, l'accès est refusé.

**Question 6**
On nous demande d'essayer la commande -sudo cd /root, la commande est refusé car cd est builltin du coup sudo ne peut pas le trouver.

**Question 7**
On nous demande de créer plusieurs dossier et fichier, dans un premier temps on va créer un dossier avec la commande -mkdir et créer un fichier un l'intérieur de ce même dossier on utilise donc la commande -touch pour créer le fichier.

**Question 8**
Il est impossible de supprimer le "fichier1" car il n'arrive pas a le trouver. Il faut donc lui indiquer le chemin complet,
-rm dossier1/fichier1.

**Question 9**
La commande pour supprimer un dossier est : -rmdir.

**Question 10**
On essaye de supprimer le dossier 2 avec la commande 
-rmdir dossier2 or ce n'est pas  possible car le dossier n'est pas vide.

**Question 11**
Pour supprimer le dossier2 avec son contenu inclus on utilise la commande -rm -rf dossier2

### Commandes importantes

**Question 1**
On peut afficher l'heure et la date avec la commande -date

**Question 2**
Avec la commande -ls on peut afficher tout les fichier visible, la commande -la nous permet d'afficher les fichier visible et caché. Les fichiers cachés commencent par un point.

**Question 3**
Le programme ls se situe dans /usr/bin/ls

**Question 4**
On test la commande -man ll pour savoir si le manuel a une entrée pour ll.

**Question 5**

**Question 6**
La commande ls permet de lister les fichiers présent dans un dossier

**Question 7**
On peut utiliser la commande -bash pour avoir le chemin d'accès relatif du dossier courant.

**Question 8**
La commande -echo 'bip' > plop nous permet de faire un bip système et de créer un fichier avec bip.

**Question 9**
La commande -echo 'bip' >> plop nous permet de faire un bip système et de créer un fichier avec bip. Le fichier contient 3 fois le mot bip.

**Question 10**
 La commande -sleep 10 | echo 'toto' s'exécute normalement et nous affiche toto en sortie de commande.

**Question 11**
La commande -file sert à déterminer le type d'un fichier en parcourant son contenu.

**Question 12**
On peut observer que le lien phy est une copie du fichier original qui s'actualise après chaque changement, si on supprime original le fichier lien phy reste toujours disponible.

**Question 13**
Pour la modification le système reste pareil que la question du dessus mais si on supprime le fichier de création a savoir lien_phy le contenue de lien_sym est supprimé aussi.

**Question 14**
On peut arrêter le défilement avec les commande : Ctrl X

**Question 15**

**Question 16**
La commande -dmesg permet de scruter les processus de démarrage linux

**Question 17**
Il contient des chemins relatifs, on peut afficher la page du manuel avec -man passwd

**Question 18**
On peut trié avec la commande -sort

**Question 19**
On peut utiliser la commande -user ou -who pour lister les utilisateurs

**Question 20**

**Question 21**

### Découverte de l'éditeur de texte nano

**Question 1**
 

**Question 2**
-sed -i 's/kernel/noyau/g' syslog

**Question 3**

