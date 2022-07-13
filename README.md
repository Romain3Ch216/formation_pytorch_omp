# Atelier Pytorch à l'Observatoire Midi-Pyrénées - les bases pour être autonome

#### 3 novembre 2022 de 9h à 17h à l'OMP (salle Coriolis)

### Objectifs

A la fin de la journée, vous serez capables de : 

 * Comprendre dans le détail et manipuler les objets de base de PyTorch :
   * Tenseurs ```torch.tensor``` (transposer, concaténer, multiplier, dupliquer...),
   * Paramètres ```torch.nn.parameter``` (caluler et rétro-propager le gradient...),
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
 
### Installation de PyTorch et de Jupyter Notebook

Nous vous recommandons d'installer Anaconda (https://docs.anaconda.com/anaconda/install/) qui inclut Jupyter Notebook. 

Une fois installé, il suffit d'exécuter les commandes suivantes dans votre terminal:

```
conda create -n atelier_pytorch_omp python=3.8.5
conda activate atelier_pytorch_omp
pip install -r requirements.txt
```

### Public concerné

Stagiaires, CDD, Doctorants, Post Docs ou tout autre personnel permanent.

**Atention**, cet atelier n'est ni une formation à Python, ni un cours de machine learning ni un atelier pour des utilisateurs expérimentés de PyTorch.
