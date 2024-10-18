# IA explicable hybride pour signal - Image

IAehsi est un [Groupe de travail GDR-IASIS](https://gdr-iasis.cnrs.fr/groupes-de-travail/)

## Contexte
Les approches d’intelligence artificielle d'apprentissage profond sont devenues essentielles dans l'analyse et la classification des données signal et image notamment. Bien ces modèles aient produit des résultats impressionnants, ils manquent de transparence. Aussi, d'un point de vue applicatif, les outils d’analyse à base d’Intelligence Artificielle (IA) requièrent une certification pour l’application dans des domaines critiques, par exemple l’imagerie médicale ou la sécurité. Ainsi le domaine de recherche sur l’IA de confiance, ou l’intelligence artificielle explicable (XAI) est en pleine effervescence. 

Pour des données sous forme d’image, expliquer la décision d'un réseau neuronal profond consiste souvent à identifier l'ensemble des pixels d'entrée qui ont le plus contribué à la décision. Pour les signaux mono ou multidimensionnel, il s’agit d’indiquer des intervalles en cours de temps et les dimensions qui ont induit la décision de classification produite, afin de confronter les explications avec les attentes des experts du domaine. 

Ces approches montrent aujourd’hui leurs limites. L’image ou le signal sont de plus en plus souvent considérées comme des sources d’information dans des applications qui utilisent des systèmes experts à base de règles et selon des ontologies des concepts métier. La confiance en les décisions de ces outils passe par l’explication de toute la chaîne décisionnelle. On parle donc d’ « explication hybride ». Aujourd’hui, à la fois sur le plan national et international, ce sujet de recherche est exploré de façon intense dans des communautés de l’IA, Visualisation de l’Information, Signal-Image et Mathématiques de l’IA. 

## Objectifs
Ce groupe de travail a pour objectif principal de fédérer la communauté nationale intéressée par ce sujet. Au delà du GdR IASIS, le GT sera notamment amené à interagir avec le groupement de recherche « Raisonnement, Apprentissage, et Décision en Intelligence Artificielle » [GdR RADIA](https://gdr-radia.cnrs.fr/) et ses GT « Modèles Hybrides d’IA » [MHyAI](https://ziedbouraoui.github.io/gdr-radia-mhyia) et « Explicabilité et Confiance » [EXPLICON](https://gt-explicon.github.io/).

A l'issue du GT (avril 2026) nous proposerons une synthèse de l’état de l’art et des pistes de recherches les plus prometteuses.

## Réalisations
* Co-organisation des « Journées d'Intelligence Artificielle Hybride : de l'intégration des connaissances et de l'humain à l'explication des modèles » ([HyCHA'24](https://hycha24.sciencesconf.org/)) avec les GT [MHyAI](https://ziedbouraoui.github.io/gdr-radia-mhyia) et [EXPLICON](https://gt-explicon.github.io/) du GdR RADIA, l'[IRT System X](https://www.irt-systemx.fr/) et le laboratoire [MICS](https://mics.centralesupelec.fr/) de CentraleSupelec.
  * compte-rendu: (tba)

## A venir

* **Biais dans les données et modèles**: méthodes d’explicabilité pour compenser et corriger les biais dans les ensembles d’entraînement des modèles neuronaux, ou dans les modèles appris sur ces ensembles. Méthodes de génération de données synthétiques contrôlées pour compenser les biais et atteindre des performances comparables ou meilleures à celles obtenues avec des données réelles. Identification et explication des biais liés à des décalages de domaines (*domain shift*). Méthodes d’explicabilités pour le design de modèles neuronaux non-baisés (*fairness-by-design*). Associer mesures de biais et explicabilité.

* **Evaluation des outils d’explication**: (certifier le certifiable) Deux tendances dans des outils d’explication existent aujourd’hui : i)explication spécifique pour une classe, ii) explication agnostique à la classe. La première donne lieu à de nombreux travaux, l’évaluation des méthodes classe-spécifiques et classe-agnostiques passe souvent par la comparaison des deux familles. Or, en ce qui concerne l’explication dans des problèmes de classification pour les images, il est nécessaire d’inclure des aspects psychovisuels dans cette démarche et non pas s’attacher à simplement suivre la variation des scores. Par ailleurs, dans un système hybride à la base d’apprentissage et des règles, il est important de confronter l’explication  avec le jugement par l’utilisateur, donc de pouvoir concevoir de nouveaux  protocoles d’évaluation des méthodes. 

## Animation
* [Jenny Benois-Pineau](https://www.labri.fr/projet/AIV/jennybenoispineau.php) (LABRI UMR 5800)
* [Alexandre Benoit](https://www.univ-smb.fr/listic/presentation/membres/enseignants-chercheurs/alexandre-benoit/) (LISTIC, UR 3703)
* [Hervé Le Borgne](https://hleborgne.github.io/) (CEA LIST). 
