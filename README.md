# IFT 3700-Travail Final, Nettoyage des données

# Ozer Guney

# Contenu du dossier 'projet' 

Le projet contient 3 dossiers, 1 fichier jupyter notebook 'main' et un fichier csv 'countries of the world' contenant tous les pays du monde filtrer à partir des 40 fichiers csv.

Le dossier 'Données Brutes' contient les 40 fichiers csv qui ont été nettoyé manuellement pour gagner du temps, certains noms de pays contenaient par exemple (details), [Note], (OPEC), (more info), etc. Certains avaient des erreurs de formatage comme des virgules. Ils ont été supprimé.
Dans la deuxieme colonne, certaines valeurs n'avait pas la bonne syntaxe comme 0.5-1.0, dans ces genres de cas, nous avons pris la moyenne des deux valeurs et nous avons remplacé la valeur par la moyenne.
Il y avait aussi d'autres petites erreurs comme des espaces en trop, des points en trop, etc

Le dossier 'Données Nettoyées' contient les 40 fichiers csv nettoyés avec du code. Les lignes contenant des valeurs vides, des valeurs manquantes, des % et des < ont été supprimées
Certains noms de pays ont été aussi changés pour correspondre au nom des pays dans le fichier countries of the world.



# Comment exécuter le code

1) Avec Jupyter notebook

a. Ouvrir le projet dans un IDE comme PyCharm ou Visual Studio Code

b. Ouvrir le fichier main

c. Executer un par un les cellules 

d. Le fichier finale va apparaitre dans le dossier 'projet'

2) Avec Colab

a. Ouvrir le fichier dans Colab

b. Il faut donner le chemin du dossier qui contient les données qui est dans votre Google drive 

c. Ensuite executer un par un  les celulles

d. Le fichier finale va apparaitre dans le dossier 'projet' dans votre Google Drive
