Article A47 A-1
----
Les copies mentionnées au quatrième alinéa de l'article L. 47 A présentent des
fichiers "à plat", à organisation séquentielle et structure zonée.

II. Les entreprises peuvent choisir l'une des normes suivantes :

1. Fichiers EBCDIC ou ASCII, sur bandes magnétiques de largeur 0,5 pouce, à neuf
pistes, de densité d'enregistrement 1 600-6250 BPI (densité des informations sur
la bande), à étiquetage normalisé et sans indicateur de séquence de bloc.

2. Fichiers ASCII sur disquettes magnétiques de format 3 1/2 pouces ou 5 1/4
pouces à simple, double ou haute densité d'enregistrement, formatées sous MS/DOS
(système d'exploitation).

Les séparateurs d'article et de champ sont respectivement les caractères Line
Feed et Shift Out représentés en ASCII sous la forme hexadécimale (OA) 16 et
(OE) 16.

III. Le format des données doit être conforme aux spécifications suivantes :

Les nombres entiers codés en numérique binaire (complémentés à deux avec bit de
signe) et les nombres réels codés en virgule flottante sont convertis en code
caractère. Le point sépare la fraction entière de la partie décimale. Les zones
numériques sont cadrées à droite et complétées à gauche par des zéros. Elles
sont signées (1er caractère à partir de la gauche) et non compactées ;

Les zones alphanumériques sont cadrées à gauche et complétées à droite par des
espaces. Seuls les caractères alphabétiques en majuscules peuvent être utilisés.
Les caractères minuscules ou accentués sont donc prohibés ;

Les dates sont exprimées au format AAMMJJ sans séparateur.
