This is my 6th project in the context of data analyst training program cohosted by OpenClassrooms and INSAE-INSEE. 
https://openclassrooms.com/fr/paths/65/projects/147/assignment
En bref: Détecter les faux billets à partir du jeu de données englobant statistiques sur les 6 caracthéristiques (dont 5 quantitatives et 1 qualitatives) des billets.

**Highlights:** 

- Clustering method - K means, 
- Principal Component Analysis, 
- Modelisation via logistic regression, 
- Descriptive statistics


**Prérequis**

Pour ce projet, il sera nécessaire de savoir manipuler des données en R ou en Python. Également, vous devrez effectuer une analyse de **statistique descriptive**, ainsi qu'une **Analyse en Composantes Principales**, une **classification automatique**, et une **modélisation** de type **régression logistique**.

 
**Scénario**
Votre société de consulting informatique vous propose une nouvelle mission au ministère de l'Intérieur, dans le cadre de la lutte contre la criminalité organisée, à l'Office central pour la répression du faux monnayage. Votre mission si vous l'acceptez : **créer un algorithme de détection de faux billets**.

Vous vous voyez déjà en grand justicier combattant sans relâche la criminalité organisée en pianotant à mains de maître votre ordinateur, pour façonner ce fabuleux algorithme  qui traquera la moindre fraude et permettra de mettre à jour les réseaux secrets de faux-monnayeurs ! La classe, non ?

... Bon, si on retombait les pieds sur terre? Travailler pour la police judiciaire, c'est bien, mais vous allez devoir faire appel à vos connaissances en statistiques, alors on y va !

**Les données**

La PJ vous transmet un jeu de données contenant les caractéristiques géométriques de billets de banque. Pour chacun d'eux, nous connaissons :

- la longueur du billet (en mm) ;
- la hauteur du billet (mesurée sur le côté gauche, en mm) ;
- La hauteur du billet (mesurée sur le côté droit, en mm) ;
- la marge entre le bord supérieur du billet et l'image de celui-ci (en mm) ;
- la marge entre le bord inférieur du billet et l'image de celui-ci (en mm) ;
- la diagonale du billet (en mm).

**Votre mission**

**Mission 0**

Afin d'introduire votre analyse, effectuez une brève description des données (analyses univariées et bivariées).

**Mission 1**

Vous réaliserez une analyse en composantes principales de l'échantillon, en suivant toutes ces étapes :

- analyse de l'éboulis des valeurs propres ;
- représentation des variables par le cercle des corrélations ;
- représentation des individus par les plans factoriels ;
- analyser de la qualité de représentation et la contribution des individus.

La variable donnant la nature Vrai/Faux du billet sera utilisée comme variable illustrative.

**Mission 2**

Appliquez un **algorithme de classification**, puis analysez le résultat obtenu.

Visualisez la partition obtenue dans le premier plan factoriel de l'ACP, puis analysez-la.

**Mission 3**

Modélisez les données à l'aide d'une régression logistique. Grâce à celle-ci, vous créerez un programme capable d'effectuer une prédiction sur un billet, c'est-à-dire de déterminer s'il s'agit d'un vrai ou d'un faux billet. Pour chaque billet, votre algorithme de classification devra donner la probabilité que le billet soit vrai. Si cette probabilité est supérieure ou égale à 0.5, le billet sera considéré comme vrai. Dans le cas contraire, il sera considéré comme faux.
