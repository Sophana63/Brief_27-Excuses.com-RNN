# Brief_27 - Excuses.com

## 1. Installation des librairies

Pour installer les librairies nécessaires, vous pouvez utiliser le fichier requirements.txt. Pour cela, utilisez la commande suivante dans votre terminal:

```
pip install -r requirements.txt
```

<br>

## 2. Création d'un réseau RNN

Dans cet exercice, vous allez créer un réseau de neurones récurrents (RNN) pour prédire l'évolution du statut professionnel d'une personne, année après année. Chaque séquence correspond à 10 années consécutives, où chaque année décrit une situation professionnelle, comprenant 3 composantes :


- le salaire,
- le nombre de personnes sous sa responsabilité,
- la taille de l'entreprise.

<br>

## 3. Classification d'électrocardiogrammes

Dans cet exercice, vous devrez classer les séquences d'électrocardiogrammes en cinq catégories différentes. Il s'agira de prédire la catégorie à laquelle appartient chaque séquence. Les données sont des séquences de battements de cœur, et certaines des catégories correspondent à des dysfonctionnements cardiaques.

<br>

## 4. Prédiction de la pollution de l'air

Dans cet exercice, vous devrez prédire la pollution de l'air pour le lendemain, en utilisant des données météorologiques. Vous utiliserez plusieurs couches RNN pour cela, et apprendrez à préparer des données en temps réel, qui peuvent ne pas être dans le bon format.

<br>

## 5. Prédiction de la pollution de l'air avec des séquences de longueurs variables


Dans cet exercice, vous allez prédire la pollution de l'air correspondant à chaque jour d'une séquence de données météorologiques. Contrairement à l'exercice précédent, vous ne disposez pas des valeurs de pollution chaque jour mais vous devez les prédire. De plus, vous allez traiter des données un peu plus complexes, car les séquences auront des longueurs différentes.