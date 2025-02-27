# *what-is-machine-learning*

### Introduction

Dans ce projet il nous ait demandé de faire de la veille sur le machine learning . Il faut choisir 2 aspect du machine learning sur 17 qui nous a été donnés . j'ai décidé de choisir l'apprentissage supervisé et la calssification supervisée. 


### Qu'est ce que le Machine learning ? 

Le machine learning (apprentissage automatique) est un domaine de l'intelligence artificielle . Le but est d'entrainer des modèle ( algorythme ) avec énormement de donnée afin qu'il puisse prédire d'autre données comme par exemple une intelligence artificielle qui a été entrainé a reconnaitre une pneumonie à partir de plusieurs radiographies de poumon ( avec et sans pneumonie ) dans ce cas c'est du machine learning avec apprentissage supervisée . 


## L'apprentissage supervisé :

### introduction :
L'apprentissage supervisé est un type d'apprentissage en machine learning , le modèle est entrainé avec des données dites étiquetées. C'est-à-dire que les données en entrée sont associés à une sortie attendue . L'algorithme apprends en ajustant ses paramètre pour minimiser l'écart entre ses prédictions et les vraies sorties attendues . L'algorithme d'apprentissage supervisé le plus connus est la descente de gradient.  

### Les étapes :

1 : Le jeu de données avec les entrées et leurs sortie attendue.

2 : la phase d'apprentissage où le modèle ajuste ses paramètres en fonctions des erreur qu'il fait .

3 : Une fois que le modèle est entrainé on passe à la phase de test en lui donnant des entrée sans lui donner la sortie attendu afin de voir si ses prédiction sont correct.

4 : lorsque les Tests sont concluant , le modèle est utilisé afin d'avoir ses prédictions . 

### les données : 

Nous allons prendre pour exemple un algorithme qui lit des radio de poumons afin de savoir si le poumon est atteint de pneumonie ou pas. 

![Poumon sain](picture\radio_poumon_sain.jpg)

![Poumon atteint de pneumonie](picture\paumon_pneumonie.jpeg)

Voici deux type de données , le premier avec une etiquette " sain " et le deuxieme avec une etiquette " pneumonie " . Au fur et à mesure que l'algorithme regule ses paramètres en voyant toutes les données qu'on a à lui montrer , il pourra prédire si le poumon que nous venons de lui montrer est atteint de pneumonie ou s'il est sain.

### Conclusion : 

L'apprentissage supervisée est à utiliser lorsque l'on a un jeu de données étiquetée . Si le jeu de donnée n'est pas étiquetté , nous utiliserons alors un apprentissage non supervisé.


## La classification supervisée : 


### introduction 