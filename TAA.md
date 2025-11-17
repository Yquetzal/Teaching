TAA - 2025/2026

# Présentation de l'UE

L'objectif de cette UE est d'aborder quelques aspects important de l'apprentissage automatique (machine learning)
L'UE est divisé en 3 grandes parties:
 * La première partie concerne les techniques "classiques" de machine learning, elle abordent des questions comme la gestions de données non équitablement distribuées (sampling, etc.), l'ensemble learning et les méthodes de boosting, etc.
 * La deuxième partie concerne le deep learning. Elle est constituée d'une introduction au deep, surtout pour les étudiants de Bio informatique, puis par un cours de deep avancé.
 * Enfin la troisième partie concerne un cours de MLops (pour Machine Learning Operations), un ensemble de pratiques qui visent à industrialiser, automatiser et fiabiliser le cycle de vie des modèles de machine learning.

# Programme
| Jour/Date | Heure       | Type        | Enseignant | Contenu |
|-----------|-------------|-------------|------------|------------|
| L 22/09   | 9h45-13h     | CM+TP          | Rémy       | ML rappels ([Slides](https://cazabetremy.fr/Teaching/data_class/2025/slides/Supervised%20Learning.pdf),[TP](https://cazabetremy.fr/Teaching/data_class/2025/TP/TP_ML1.pdf)) |
| L 29/09   | 9h45-13h     | CM+TP          | Rémy       | Classification, Regularization, Ensemble Learning, XGboost ([Slides](https://cazabetremy.fr/Teaching/data_class/2025/slides/Supervised%20Learning%20-%202.pdf),[TP](https://cazabetremy.fr/Teaching/data_class/2025/TP/TP_ML2.pdf)) |
| L 17/11   | 8h00-11h15     | CM+TP          | Rémy      | Imbalance, sampling, Feature selection ([Slides](https://cazabetremy.fr/Teaching/TAA/featureselection.pdf),[TP](https://cazabetremy.fr/Teaching/TAA/TP3.pdf))|
| L 24/11   | 9h45-13h   | CM+TP(BioInfo)          | Louis     | deep - intro |
| L 05/01   | 9h45-13h     | CM+TP          |  Louis    | deep 2 |
| V 09/01   | 9h45-13h     | CM+TP          | Louis      | deep - avancé |
| L 12/01   | 9h45-13h     | CM+TP | Thomas     | MLops 1 (amont: méthodes, apprentissage, etc.) |
| J 15/01   | 9h45-13h     | CM+TP | Thomas     | MLops 2 (aval: déploiement, mise en production, Dash)|
| L 19/01   | 9h45-13h     | CM+Présentations | Louis      | CM éthique + Présentations  |
| J 22/01   | 9h45-13h     | Présentations | Louis      | Présentations  |



----
# Données
### Machine Learning 1

* [cars_synth_clean.csv](https://cazabetremy.fr/Teaching/data_class/Datasets/cars_synth_clean.csv)

----
# Examen
L'évaluation se fait par un projet et un examen final écrit.


----
# Details partie MLops:
Cours 1: Ce premier cours introduira les objectifs et les méthodes du MLOps : techniques à la croisée en l’ingénierie logiciel et l'apprentissage automatique. Ces techniques permettent d'exploiter au mieux les ressources (données et calcul) pour aller vers une industrialisation d'un service basé sur du machine learning. 
Les objectifs seront :
1) de connaitre ce qui motive la mise en place d'une démarche de MLOps (notamment la différence entre la construction d'un modèle jouet, vs un modèle déployé pour une utilisation large). 
2) de comprendre les différentes étapes de la démarche d'une mise en place
3) d'identifier des outils qui permettent d'accompagner ces étapes.

Un focus sera donné sur la partie amont de la conception d'un modèle de machine learning, ie. son apprentissage. Un focus sera fait sur la sélection de modèle avec l'introduction des outils tels que MLFlow et Ray Tune qui permettent d'accompagner l'exploration de modèles. L'objectif de cette partie pratique sera de savoir mettre en place un procédure d'exploration des hyperparamètres d'un modèle et de savoir choisir celui qui a les meilleurs performances.

Cours 2: Dans ce cours, on s'intéressera plus à la phase aval de la conception d'un outil de machine learning, c'est à dire son déploiement et sa mise en production.
Nous introduirons dans ce cours quelques contraintes liées à la mise en production d'un modèle de machine learning. Nous nous intéresserons aussi à la surveillance des dérives d'un modèle en production.
Les objectifs de cette partie théorique seront de pouvoir mener des réflexions, en amont de la conception d'un modèle de machine learning pour sa conception.
D'un point de vue pratique, nous illustrerons l'utilisation de Dash comme exemple pratique pour le déploiement d'un modèle par une interface en ligne.
