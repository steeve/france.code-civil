Le Code Civil français, sous Git
================================

Introduction
------------
Voici un petit hack, résultat d'une après-midi de code: le code civil sous Git.

Si l'on considere les lois comme un ensemble de textes modifiés par les différentes assemblées de l'Etat, on peut les considérer comme un ensemble de fichiers textes créés de manière collaborative.

Les membres du gouvernement, et des différentes assemblées, travaillent en collaboration sur ces fichiers, qui, une fois votes, sont inscrit dans le Code (ici Code Civil).

Mais il y a une autre categorie de gens qui, depuis plus de 50 ans, qui travaillent sur des fichiers texte de façon collaborative, et excelle a cela: les développeurs. Ils ont crees des outils extrêmement efficaces de collaboration et de tracking travailler sur le code source. Le plus populaire en date étant Git.

Git permet non seulement de visionner les sources a un instant T (snapshot), mais surtout de visualiser facilement les changements dans ces sources (commits). Dans l'analogie du Code Civil, cela permet de tracker très rapidements les changements apportes par une loi.

Combinons tout cela a la philosophie Open Source, et la 2e partie de l'analogie est faite: modification de code source de façon ouverte et publique.

Finalement, le Code Civil, c'est une partie du code source de la France. Et le code source, ca va sur un source control. Point.

Exemple
-------
Voici par exemple le commit qui authorise le mariage pour tous: [b805ecf05a86162d149d3d182e04074ecf72c066](https://github.com/steeve/france.code-civil/commit/b805ecf05a86162d149d3d182e04074ecf72c066)

C'est quand meme plus lisible que, par exemple (cf http://www.assemblee-nationale.fr/14/ta/ta0120.asp):
> À l’article 165 du même code, le mot : « devant » est remplacé par les mots : « lors d’une cérémonie républicaine par ».

Note technique
--------------
Les dates Git étant basées sur l'epoch Unix (01/01/1970), changements avant cette dates sont tous dates au 01/01/1970, avec secondes incrémentales; Le commit message donne la vraie date.

LICENSE
-------
Tous les fichiers sont sous license [Creative Commons](https://creativecommons.org/licenses/by/4.0/).
