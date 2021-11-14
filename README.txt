{\rtf1\ansi\ansicpg1252\cocoartf1561
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 TimesNewRomanPSMT;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\csgray\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\tx9316\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\pard\pardeftab720\ri-340\partightenfactor0
\cf0  README du programme 
\i \cf2 haz_w2v
\i0 \cf0 \
\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\
Ce readme a pour but d\'92expliquer l\'92utilisation du programme SGNS (Skip-Gram avec \'e9chantillonnage n\'e9gatif) en ligne de commande. \
\

\i\b _Objectif_\'a0
\i0\b0 \
\
Le programme permet \'e0 l\'92utilisateur de faire d\'e9rouler l\'92apprentissage sur un corpus de choix, ainsi de saisir les hyperparam\'e8tres de son choix. 
\f1 \
\

\f0\i\b _Lecture du fichier
\i0 _
\f1 \

\b0 \
- 
\f0 Mettez le code 
\i \cf2 haz_w2v.py
\i0 \cf0  et le corpus \'e0 utiliser dans le m\'eame dossier.\

\f1 - 
\f0 Ouvrez le Terminal et allez dans le dossier ci-dessus.\

\f1 - 
\f0 Saisir la commande 
\i python \cf2 \cb3 haz_w2v.p\cf0 \cb1 y
\i0  
\i nom_du_fichier. \

\i0 - Notez qu\'92il y a un espace entre les deux segments de commande, et que le fichier devrait \'eatre en format .txt. \

\b \

\i _Manipulation des hyperparam\'e8tres_
\i0  
\b0 \
\
- Pour utiliser les hyperparam\'e8tres par d\'e9faut, r\'e9pondez non (\'91N\'92) et puis oui (\'91Y\'92).\
- Pour saisir vos propres hyperparam\'e8tres, r\'e9pondez oui (\'91Y\'92) et\'a0:\
    \
(1)	Saisir une ou plusieurs valeurs pour chaque hyperparam\'e8tres. Mettez bien un espace entre deux valeurs et assurez que les valeurs ne d\'e9passent pas les marges recommand\'e9es dans les parenth\'e8ses. 
\f1 \

\f0 (2)	V\'e9rifier les hyperparam\'e8tres que vous avez saisis avec l\'92affichage des r\'e9sultats.(3)	Pour les remodifier, r\'e9pondez oui (\'91Y\'92). Sinon, r\'e9pondez non (\'91N\'92) et d\'e9clenchez l\'92apprentissage.\
\
- Pour terminer l\'92apprentissage, r\'e9pondez oui (\'91Q\'92) aux questions concern\'e9es.\
\

\i\b _Enregistrement des r\'e9sultats_
\i0\b0 \
\
Chaque apprentissage termin\'e9 produit un fichier 
\i result.csv
\i0  qui enregistre \
les valeurs et les r\'e9sultats concern\'e9s. \
\
Deux fichiers textuels 
\i neg_nom_du_corpus.txt
\i0  et 
\i pos_nom_du_corpus.txt 
\i0 sont cr\'e9\'e9s dans le m\'eame dossier du programme au cours de l\'92apprentissage sur un nouveau corpus.\
\
S\'92il s\'92agit d\'92un corpus d\'e9j\'e0 appris qui doit \'eatre r\'e9appris, mettez les deux fichiers en .txt dans le m\'eame dossier du programme pour gagner du temps. Les exemples pr\'e9-stock\'e9s par les auteurs se trouvent dans le lien ci-apr\'e8s : https://bit.ly/3A3eoxQ. \
\cf2 \cb3 \
\pard\pardeftab720\sl360\partightenfactor0
\cf2 \expnd0\expndtw0\kerning0
_
\i\b Pr\'e9-requis
\i0\b0  
\i\b mat\'e9riel
\i0\b0 _ \
\
\pard\tx9461\pardeftab720\ri-410\sl360\partightenfactor0
\cf2 Le mod\'e8le Word2Vec SGNS peut fonctionner sur le Google Colab et sur un ordinateur avec un minimum de 4 Go de m\'e9moires vives. Notez que l\'92apprentissage sur un grand corpus exige davantage de m\'e9moires vives. Il sera id\'e9al de l\'92ex\'e9cuter sur le GPU. D\'e9pendances logicielles: L\'92ex\'e9cution du Word2Vec n\'e9cessite Pytorch pour g\'e9rer l\'92optimisation des param\'e8tres du mod\'e8les et les calculs sur les tenseurs. En outre, cela exige l\'92installation d\'92un certain nombre de biblioth\'e8ques Python, notamment, tqdm, NumPy et Pandas. Par souci de compatibilit\'e9 des fonctionnalit\'e9s et des biblioth\'e8ques, il est recommand\'e9 d\'92installer Python 3.7 ou des versions plus r\'e9centes. \
\pard\pardeftab720\sl360\partightenfactor0
\cf2 \
\pard\pardeftab720\ri-340\partightenfactor0
\cf0 \cb1 \kerning1\expnd0\expndtw0 Bon apprentissage
\f1 \'a0
\f0 !\cf2 \cb3 \expnd0\expndtw0\kerning0
\
\pard\pardeftab720\sl360\partightenfactor0
\cf2 \
Auteurs : Wei HU, Zong-You KE & Vo Tuan Anh AN\cf0 \cb1 \kerning1\expnd0\expndtw0 \
\pard\pardeftab720\ri-340\partightenfactor0
\cf0 \
\
\
\
}