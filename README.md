# Test geojson

Test de modification collaborative d'une carte via modifications d'un fichier geojson.

## Pour afficher la carte collaborative et naviguer dans ses points

La carte collaborative peut être visualisée sur UMap avec ce lien : http://umap.openstreetmap.fr/fr/map/test-geojson_198164#7/46.823/4.631

Cette carte UMap contient un calque qui charge dynamiquement les données du fichier `test.geojson` de ce dépôt.
Pour l'exemple, il y a aussi un autre calque avec quelques points supplémentaires.


## Pour modifier les points, en supprimer ou en ajouter (via le fichier test.geojson de ce dépôt)

Ouvrir dans l'outil web geojson.io le fichier `test.geojson` de ce dépôt, en cliquant sur ce lien : http://geojson.io/#id=github:swergas/test_geojson/blob/master/test.geojson&map=7/46.672/2.104

Une fois les modifications faites dans l'interface utilisateur, sauvegardez-les vers ce dépôt principal :

* Sélectionner tout le contenu du JSON (CTRL-A), puis le copier (CTRL-C)
* Aller sur ce dépôt github, se connecter à son compte
* Cliquer sur "test.geojson" dans la liste des fichiers, puis cliquer sur l'icône de crayon
* Remplacer tout le contenu du fichier par ce que vous allez coller (CTRL-A puis CTRL-V) et sauvegarder les modifications. Cela va créer un fork du dépôt vers votre compte, ainsi qu'une pull request qui contiendra les modifications faites à ce fichier.

Si vous détectez qu'il y a trop de lignes qui sont modifiées, et que ces modifications ne sont que du formatage, vous pouvez  reformatter le contenu du JSON, par exemple en l'ouvrant dans SublimeText et en faisant CTRL-ALT-J.
