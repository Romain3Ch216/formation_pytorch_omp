# Atelier Pytorch à l'Observatoire Midi-Pyrénées - les bases pour être autonome

#### 3 novembre 2022 de 9h à 17h à l'OMP (salle Coriolis)

### Objectifs

A la fin de la journée, vous serez capables de : 

 * Comprendre dans le détail et manipuler les objets de base de PyTorch :
   * Tenseurs ```torch.tensor``` (transposer, concaténer, multiplier, dupliquer...),
   * Paramètres ```torch.nn.parameter``` (caluler et rétro-propager le gradient par rapport à certains paramètres...),
   * Modèles ```torch.nn.Module``` (créer vos modèles, charger des paramètres pré-entrainés, fine-tuner...)
   * Modules ```torch.nn.modules``` (créer vos propres couches...)
 * Définir un ```torch.utils.data.Dataset``` adapté à votre application,
 * Sauvegarder les paramètres de votre modèle,
 * Optimiser votre modèle sur GPU,
 * Définir vos propres fonctions de régularisation,
 * Définir différents hyper-paramètres (comme le *learning rate*) pour différents paramètres de votre modèle,
 * Utiliser différentes fonctions objectives pour différents paramètres.
 
 ### Organisation de la journée

La journée (9h-12h30 / 14h-17h) sera sous la forme d'un TP (sur vos machines) avec une alternance de parties *magistrales* et d'exercices pratiques.

### Prérequis

 * Etre autonome en python,
 * Si vous n'avez jamais utilisé PyTorch, avoir visualisé le cours Fidle https://www.youtube.com/watch?v=XvaxqXD3B9k (jusqu'à 1h09),
 * Avoir installé les bibliothèques nécessaires comme expliqué ci-dessous.
 
### Téléchargement des données 

Nous aurons besoin des données téléchargeables au lien suivant : https://nextcloud.isae.fr/index.php/s/WmjQPyH3g2EK33x

### Installation des bibliothèques python et téléchargement des notebooks

Si vous ne souhaitez pas installer les bibliothèques en local, vous pouvez suivre l'atelier à partir des notebooks google Colab dont vous trouverez les liens au début de chaque jupyter notebook.

Sinon, nous vous recommandons d'installer Anaconda (https://docs.anaconda.com/anaconda/install/) qui inclut Jupyter Notebook. 

Une fois installé, vous pouvez créer un environnement virtuel en exécutant les commandes suivantes dans votre terminal:

```
conda create -n atelier_pytorch_omp python=3.8.5
conda activate atelier_pytorch_omp
```

Vous pourrez ensuite cloner le répertoire et installer les dépendances nécessaires comme suit :

```
git clone https://github.com/Romain3Ch216/atelier_pytorch_omp.git
cd atelier_pytorch_omp
pip install -r requirements.txt
```
Pour vérifier votre installation, vous pouvez ouvrir un notebook et exécuter les premières cellules :

```
jupyter-notebook partie_1.ipynb
```

### Public concerné

Stagiaires, CDD, Doctorants, Post Docs ou tout autre personnel permanent.

**Atention**, cet atelier n'est ni une formation à Python, ni un cours de machine learning ni un atelier pour des utilisateurs expérimentés de PyTorch.
