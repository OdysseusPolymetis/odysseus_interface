# ParaLogos

[en] An online alignment of several French translations of Homer's Odyssey

[fr] Un lecteur en ligne de traductions de l’Odyssée.

Cette interface javascript prend en entrée la sortie HTML du logiciel Odysseus sur ce site, et met en valeur l’information sous la forme de colonnes synchronisées. L’idée peut être transposée mais le code est très lié à la structure de l’Odyssée, à la division en chants et à une politique de nommage des fichiers. Structure du projet :

* **html/** fichiers de chapitres de l’odyssée selon le format codeLivre_{no chapitre}.html
* **biblio.js** métadonnées des livres structurées en json

Interface pour l’instant tout javascript sans dépendance à une librairie javascript ou à un langage serveur type Javascript. Démonstration : http://odysseuspolymetis.github.io/paralogos/

# TODO

* Prioriser ce TODO
* Renommer Odysseus.js en Paralogos.js ?
* Expliquer un peu plus de quoi il s’agit sur la page d’accueil (légende des couleurs)
* Mettre à jour et vérifier biblio.js.
* Faut-il afficher toutes les traductions dès l’accueil au public ou juste une sélection ? (implémentrer cette sélection)
* Ajouter une colonne après la colonne active (et pas tout au bout)
* Glisser/déposer les colonnes
* Meilleures couleurs pour les happax
* Vue vers ou sans vers
* Côté Odysseus, conserver les clitiques « elle avait pris le aspect de… » (bof)
* Vue pour la publi conservant l’apparence en vers (côté Odysseus, passer les / avec un balise <br/> ?)

# DONE

* isoler biblio.js
* écriture plus modulaire de l’objet Odysseus.js
