# Sign Language MNIST Classifier

Un projet de classification des gestes de la langue des signes (Sign Language MNIST) utilisant un modèle de deep learning avec Keras et TensorFlow.

---

## Description
Ce projet vise à entraîner un modèle pour reconnaître les gestes de la langue des signes à partir du jeu de données **Sign Language MNIST**. Le modèle est entraîné et évalué en utilisant des notebooks Jupyter, et peut être utilisé en temps réel pour la détection de gestes.

---

## Structure du projet
```
Sign-Language-MNIST-Classifier/
├── data/
├── models/
├── notebooks/
├── src/
├── label_map.txt
├── requirements.txt
└── README.md
```

---

## Prérequis
Pour exécuter ce projet, vous aurez besoin des bibliothèques suivantes :
- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Kaggle (pour télécharger le jeu de données)

Installez les dépendances avec :
```bash
pip install -r requirements.txt
```

---

## Installation
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/AbdelkaderHamdi/Sign-Language-MNIST-Classifier.git
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
3. Téléchargez le jeu de données Sign Language MNIST depuis [Kaggle](https://www.kaggle.com/datasets/datamunge/sign-language-mnist) et placez-le dans le dossier `data/`.

---

## Utilisation
1. **Entraînement du modèle** :
   - Ouvrez le notebook `Sign_Language_MNIST.ipynb` et exécutez les cellules pour entraîner le modèle.
   - Le modèle entraîné sera sauvegardé dans `models/sign_mnist_model.keras`.

2. **Évaluation en temps réel** :
   - Ouvrez le notebook `Evaluate_real_time.ipynb` pour tester le modèle en temps réel.

---

## Résultats
- Le modèle atteint une précision de **93%** sur le jeu de test.
- Exemples de prédictions en temps réel disponibles dans le notebook d'évaluation.

---

## Contribution
Les contributions sont les bienvenues ! Ouvrez une issue ou soumettez une pull request.


---

## Contact
Pour toute question, contactez-moi sur [LinkedIn](https://www.linkedin.com/in/abdelkader-hamdi/).
```
