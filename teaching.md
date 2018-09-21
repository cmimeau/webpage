---
layout: default
---  

_As my teaching activities are realised in French, this page is written only in French language._

**Summary**  
[Enseignements dispensés au Cnam](#cours)  
[Un outil pour les TP numériques : Jupyter](#Jupyter)  

[← back to home page](./)

## Enseignements dispensés au Cnam<a name="cours"></a>

* **Cours du soir, Cnam Paris** :  
  + Calcul différentiel et intégral (code UE : [MVA005](http://formation.cnam.fr/rechercher-par-discipline/calcul-differentiel-et-integral-208544.kjsp))  
→ Matériel de cours disponible [ici](http://maths.cnam.fr/spip.php?article318)  
  + Analyse et calcul matriciel (code UE : [MVA101](http://formation.cnam.fr/rechercher-par-discipline/analyse-et-calcul-matriciel-208548.kjsp))  
→ Matériel de cours disponible [ici](http://maths.cnam.fr/spip.php?article416)  
  + Apprentissage des logiciels de calcul (code UE : [STA002](http://formation.cnam.fr/rechercher-par-discipline/apprentissage-des-logiciels-de-calcul-1004085.kjsp))  
  + Analyse numérique matricielle et optimisation, Travaux pratiques (code UE : [CSC106](http://formation.cnam.fr/rechercher-par-discipline/analyse-numerique-matricielle-et-optimisation-travaux-pratiques-207977.kjsp))  
  
* **Cours alternance, Cnam Saint-Denis (DUT et Ecole d'ingénieurs du Cnam -EiCnam-)** :  
  + Outils mathématiques (codes UE : MAA111, MAA118)  
  + TP d'initiation aux méthodes numériques (codes UE : USMES1, MAA11A)  
  + Simulations fluides, thermique (code UE : MEA136)  
  

## Un outil pour les TP numériques : _Jupyter_<a name="Jupyter"></a> ![Logo Jupyter](/assets/images/jupyter.png)

### Les carnets _Jupyter_

**Qu'est-ce qu'un carnet Jupyter ?**  
Un carnet Jupyter (notebooks en anglais) se présente sous la forme d'une feuille de texte ou de calculs manipulable à travers un navigateur web. Ce carnet se subdivise en cellules, des zones indépendantes pouvant contenir l'ensemble des éléments suivants :
  - texte html ou Markdown  
  - formules au format LaTex  
  - figures, graphiques  
  - tableaux  
  - vidéos  
  - images  
  - et surtout du **code exécutable** : les langages disponibles sous Jupyter sont multiples : Python, R, C, C++, matlab, ...  

De plus ce document unique peut ensuite être exporté au format pdf ou html ou bien encore être présenté sous la forme de transparents de cours dynamiques. Les carnets Jupyter représentent donc un format idéal pour les TP numériques, que ce soit pour l'enseignant (rédaction de sujets de TP, de transparents/poly de cours, de feuille d'exercices, ...) ou pour les élèves (rédaction de comptes-rendu de TP ou de rapports sur document unique contenant l'ensemble des supports, dont du code executable).

**Et en pratique ?**   
→ Vidéo de [démonstration](https://www.youtube.com/watch?v=Duicsycntdo) d'utilisation d'un carnet Jupyter  
→ Tester directement Jupyter en ligne, sans installation, sur [try.jupyter.org](https://mybinder.org/v2/gh/ipython/ipython-in-depth/master?filepath=binder/Index.ipynb) (attention, il y a souvent saturation du serveur. De façon générale, une installation de Jupyter sur votre machine est vivement recommandée)  
→ Pour installer Jupyter, télécharger la distribution [Anaconda](https://www.anaconda.com/download) pour Python version 2 ou 3 (contenant nativement Jupyter ainsi que d'autres applications Python comme l'IDE Spyder)  
→ Exemples de carnet Jupyter (en Python 3) à télécharger [ici](assets/images/Detection_de_contours_et_de_droites_dans_une_image.ipynb) et à tester dans Jupyter (en cliquant sur l'onglet *Upload* en haut à droite)

### Le projet _JupyterHub_ au Cnam

Afin de faciliter l’accès et l’utilisation des carnets Jupyter lors des cours/TP réalisés au Cnam, une équipe de 6 enseignants-chercheurs accompagnée d'un ingénieur a mis en place un projet visant à héberger un serveur [JupyterHub](https://jhub.cnam.fr/) unique (machine virtuelle) au sein de l'infrastructure informatique du Cnam. Ainsi les élèves ne sont désormais plus contraints à l’installation de logiciel tiers sur leurs propres ordinateurs et plus aucune installation n'est nécessaire sur les machines physiques des salles de TP du Cnam. Les ressources de calcul sont distribuées sur le serveur JupyterHub. Il suffit d’une connexion internet pour y accéder et les utiliser (seuls les enseignants-chercheurs et les élèves du Cnam ont accès à ce serveur).

**Les membres du projet JupyterHub** :
* Rafik Abdesselam (AuPEN, Ingénieur en technologies de la formation)  
* Amélie Danlos (EPN 1, Bâtiment Energies)  
* Simon Marié (EPN 4, Ingénierie mécanique et matériaux)  
* Raphaël Fournier-S'Nieotta (EPN 5, Informatique)  
* Chloé Mimeau (EPN 6, Mathématiques et Statistiques)  
* Josselin Noirel (EPN 7, Chimie Vivant Santé)  
* Régis Gallon (EPN 8, Intechmer)  

![Equipe JupyterHub](/assets/images/equipe_Jhub_ok.png)


[← back to home page](./)
