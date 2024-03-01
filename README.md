# SIMPLON DEV IA | Brief 13

## Le facteur et le MNIST

### Contexte

Depuis plus de 30 ans, la Poste utilise l'OCR (Optical Character Recognition) pour reconnaître le code postal sur les courriers envoyés. <br>
Vous êtes facteur (et développeur IA à vos heures perdues) et vous souhaitez étendre ce système à la reconnaissance d'adresses entières.

### Structure du projet

```bash
project/
│
├── .gitignore
├── README.md
├── mnist.ipynb    # Main notebook, with model trained on MNIST dataset
├── mnist_fashion.ipynb    # Notebook with model trained on fashion MNIST
└── recon.ipynb    # Notebook testing our first model (MNIST trained) on personal images and drawings
```

### Notes

Dans le premier notebook, après avoir cherché les paramètres optimaux pour mon modèle, j'ai testé d'autres paramètres en suivant un tutoriel, améliorant les performances du modèle (finalement sauvegardé pour la suite du projet.

En ce qui concerne les images et dessins, le modèle renvoie des résultats très proches les uns des autres, peu importe l'image fournie. <br>
Les probabilités calculées varient légèrement, mais 5 est toujours renvoyée en tant que prédiction car il s'agit de la probabilité la plus haute parmi les 10 options. (en attente de correctif)
