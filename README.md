# Atelier Pytorch à l'Observatoire Midi-Pyrénées - les bases pour être autonome

#### 3 novembre 2022 de 9h à 17h à l'OMP (salle Coriolis)

### Objectifs

A la fin de la journée, vous serez capables de : 

 * Comprendre dans le détail et manipuler les objets de base de PyTorch :
   ** Tenseurs ```torch.tensor``` (transposer, concaténer, multiplier, dupliquer...),
   ** Modèles ```torch.nn.Module``` (créer vos modèles, charger des paramètres pré-entrainés, fine-tuner...)
   ** Modules ```torch.nn.modules``` (créer vos propres couches...)
 * Définir un ```torch.utils.data.Dataset```,
 * Sauvegarder les paramètres de votre modèle,
 * Optimiser votre modèle sur GPU,
 * Définir vos propres fonctions de régularisation,
 * Définir différents hyper-paramètres (comme le *learning rate*) pour différents paramètres de votre modèle,
 * Utiliser différentes fonctions objectives pour différents paramètres.
 
 ### Organisation de la journée

La journée (9h-12h30 / 14h-17h) sera sous la forme d'un TP (sur vos machines) avec une alternance de présentations *magistrales* et d'exercices pratiques.

### Prérequis

 * Etre autonome en python,
 * Avoir installé Jupyter Notebook et Pytorch (voir ci-dessous la procédure) OU avoir un compte Google (pour utiliser Google Colab).
 
### Installation de PyTorch et de Jupyter Notebook

Nous vous recommandons d'installer Anaconda (https://docs.anaconda.com/anaconda/install/) qui inclut Jupyter Notebook. Pour installer PyTorch, nous recommandons de créer un environnement conda (https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) et d'y installer PyTorch en suivant le guide suivant : https://pytorch.org/get-started/locally/ .

### Public concerné

Stagiaires, CDD, Doctorants, Post Docs ou tout autre personnel permanent.

**Atention**, cet atelier n'est ni une formation à Python ni un atelier pour des utilisateurs expérimentés de PyTorch.
