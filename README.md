# mds_sql

##Requete 1

Afficher le titre des films (dans une colonne "Titres films") qui ont comme id de genre 1, 2 ou 3 et dont leurs titres finissent par la lettre E (case insensitive).

##Requete 2

Faire une requete qui affiche le titre (titre_film), la durée du film (duree_film) et le résumé (resume_film) de tous les films qui sont dans la table film du cinéma.

##Requete 3

Faire une requete qui affiche le titre des films en minsucule de la table film du cinema qui ont un id compris (exclu) entre 42, et 84. La colonne titre en minuscule devra s'appeler "titres_min".

##Requete 4

Faire une requete qui affiche le titre en majuscule de tous les films dans la colonne titre et les date de fin d'affiche dans la colone date_fin_affiche, ordonnee par date de fin d'affiche decroissante.

##Requete 5

On aimerait afficher le titre de tous les films en sha1, dans la colonne "Titres_SHA1" et en MD5 dans la colonne "Titres_MD5".

##Requete 6

Faire une requete qui affiche le nombre de films qu'il y a dans la table film (nombre_films) dont la première lettre est un B (case insensitive).

##Requete 7

Faire une requete qui selectionne le titre (titre) des films contenant dans leur titre la chaine de caracteres 'the' independament de la casse (case non sensitive, la requete doit matcher The thE etc..). Il faudra aussi que le genre des films soit egal à 2.

##Requete 8

Afficher le titre (titre), date_debut_affiche (date_debut), distrib_id (distrib_id), le nom du distributeur (nom_distrib) de tous les films dont le nom contient 'day' independement de la casse (cad que le titre peu contenir "DaY", "dAy" et tous ses dérivés). Si le film n'a pas de distributeur, il ne faut pas l'afficher. Il faut enfin ordener les resultats par date_debut_affiche descendant.

##Requete 9

Faire une requete qui compte tous les films associes qui ont des id de genre compris entre 3 et 5 (inclu). La requete affichera le nombre de films qu'il y a dans ce genre et le nom du genre. Il y aura donc les colones "nom genre", "nombre films" et "minutes totales".