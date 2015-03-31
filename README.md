Le Code Civil français, sous Git
================================

Introduction
------------
Voici un petit hack, résultat d'une après-midi de code : le code civil sous Git.

Si l'on considère les lois comme un ensemble de textes modifiés par les différentes assemblées de l'Etat, on peut les considérer comme un ensemble de fichiers texte créés de manière collaborative.

Les membres du gouvernement, et des différentes assemblées, travaillent en collaboration sur ces fichiers, qui, une fois votés, sont inscrits dans le Code (ici Code Civil).

Mais il y a une autre catégorie de gens qui, depuis plus de 50 ans, travaillent sur des fichiers texte de façon collaborative, et excellent à cela : les développeurs. Ils ont créé des outils extrêmement efficaces de collaboration et de tracking pour travailler sur du code source. Le plus populaire en date étant Git.

Git permet non seulement de visionner les sources à un instant T (snapshot), mais surtout de visualiser facilement les changements dans ces sources (commits). Dans l'analogie du Code Civil, cela permet de tracker très rapidement les changements apportés par une loi.

Combinons tout cela à la philosophie Open Source, et la seconde partie de l'analogie est faite : modification de code source de façon ouverte et publique.

Finalement, le Code Civil, c'est une partie du code source de la France. Et le code source, ça va sur un source control. Point.

Exemple
-------
Voici par exemple le commit qui autorise le mariage pour tous : [b805ecf05a86162d149d3d182e04074ecf72c066](https://github.com/steeve/france.code-civil/commit/b805ecf05a86162d149d3d182e04074ecf72c066)

C'est quand même plus lisible que, par exemple (cf http://www.assemblee-nationale.fr/14/ta/ta0120.asp) :
> À l’article 165 du même code, le mot : « devant » est remplacé par les mots : « lors d’une cérémonie républicaine par ».

Note technique
--------------
Les dates Git étant basées sur l'epoch Unix (01/01/1970), les changements avant cette date sont tous datés au 01/01/1970, avec secondes incrémentales; Le message du commit donne la vraie date.

LICENCE
-------
Tous les fichiers sont sous licence [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).
