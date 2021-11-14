README du programme haz_w2v
———————————————————————————

Ce readme a pour but d’expliquer l’utilisation du programme SGNS (Skip-Gram avec échantillonnage négatif) en ligne de commande. 

_Objectif_ 

Le programme permet à l’utilisateur de faire dérouler l’apprentissage sur un corpus de choix, ainsi de saisir les hyperparamètres de son choix. 

_Lecture du fichier_

- Mettez le code haz_w2v.py et le corpus à utiliser dans le même dossier.
- Ouvrez le Terminal et allez dans le dossier ci-dessus.
- Saisir la commande python haz_w2v.py nom_du_fichier. 
- Notez qu’il y a un espace entre les deux segments de commande, et que le fichier devrait être en format .txt. 

_Manipulation des hyperparamètres_ 

- Pour utiliser les hyperparamètres par défaut, répondez non (‘N’) et puis oui (‘Y’).
- Pour saisir vos propres hyperparamètres, répondez oui (‘Y’) et :
    
(1)	Saisir une ou plusieurs valeurs pour chaque hyperparamètres. Mettez bien un espace entre deux valeurs et assurez que les valeurs ne dépassent pas les marges recommandées dans les parenthèses. 
(2)	Vérifier les hyperparamètres que vous avez saisis avec l’affichage des résultats.(3)	Pour les remodifier, répondez oui (‘Y’). Sinon, répondez non (‘N’) et déclenchez l’apprentissage.

- Pour terminer l’apprentissage, répondez oui (‘Q’) aux questions concernées.

_Enregistrement des résultats_

Chaque apprentissage terminé produit un fichier result.csv qui enregistre 
les valeurs et les résultats concernés. 

Deux fichiers textuels neg_nom_du_corpus.txt et pos_nom_du_corpus.txt sont créés dans le même dossier du programme au cours de l’apprentissage sur un nouveau corpus.

S’il s’agit d’un corpus déjà appris qui doit être réappris, mettez les deux fichiers en .txt dans le même dossier du programme pour gagner du temps. Les exemples pré-stockés par les auteurs se trouvent dans le lien ci-après : https://bit.ly/3A3eoxQ. 

_Pré-requis matériel_ 

Le modèle Word2Vec SGNS peut fonctionner sur le Google Colab et sur un ordinateur avec un minimum de 4 Go de mémoires vives. Notez que l’apprentissage sur un grand corpus exige davantage de mémoires vives. Il sera idéal de l’exécuter sur le GPU. Dépendances logicielles: L’exécution du Word2Vec nécessite Pytorch pour gérer l’optimisation des paramètres du modèles et les calculs sur les tenseurs. En outre, cela exige l’installation d’un certain nombre de bibliothèques Python, notamment, tqdm, NumPy et Pandas. Par souci de compatibilité des fonctionnalités et des bibliothèques, il est recommandé d’installer Python 3.7 ou des versions plus récentes. 

Bon apprentissage !

Auteurs : Wei HU, Zong-You KE & Vo Tuan Anh AN
