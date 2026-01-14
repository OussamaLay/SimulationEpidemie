# SimulationEpidemie

Ce projet est réalisé par :
  - Elmehdi SASSI
  - Oussama LAYAIDI


Le fichier `diagUML.dot` est utilisé pour dessiner le diagramme de classe, en utilisant l'extention `DotUML`.

Il suffit d'installer l'extention `DotUML` sur Visual Studio Code, ouvrir le fichier `diagUML.dot`, clique droit sur le code, cliquer sur `Open DotUML Preview to the side`, et puis une fenètre affichera le diagramme complet.


Pour exécuter tout le projet depuis le répértoire principal :
```bash
  $ javac -d ./bin ./src/*.java
  $ java -cp ./bin App
```


### Modélisation Multi-Agent en Java pour simuler la propagation d'une maladie :

  - Développement d'un modèle multi-agent pour simuler la propagation d'une maladie dans une population.
  
  - Conception d'un diagramme de classe pour la structuration du modèle.
  
  - Implémentation d'un code avec des fonctionnalités avancées, dont la gestion de l'espace toroïdal et des interactions entre agents.
  
  - Utilisation de la stochasticité pour le déplacement des individus et la probabilité d'infection.
  
  - Initialisation du modèle avec 20 000 individus sur une grille de 300x300, incluant des statuts, des paramètres de durée de vie, et un placement   aléatoire des agents.
  
  - Génération de fichiers CSV pour chaque itération du modèle.
  
  - Analyse des résultats via un notebook Jupyter, incluant la lecture des fichiers et l'affichage graphique des moyennes sur 100 réplications.
  
Ce projet a permis d'approfondir mes compétences en modélisation multi-agent, en conception de diagrammes de classe, en programmation avancée, ainsi qu'en analyse et visualisation de données avec l'utilisation de notebooks Jupyter.
