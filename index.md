# IFT3150 : Projet d'informatique

Ceci est la page du projet d'informatique (IFT3150) de [Tanguy Invernizzi](https://about.me/tinvernizzi), réalisé à l'Université de Montréal, sous la tutelle de [Michalis Famelis](https://michalis.famelis.info).

## Semaine 1 : 16 au 23 Janvier 2017

Il as été décidé lors de la premiére rencontre que les premiéres semaines seraient consacrées à la lecture des papiers relatifs au domaine traités dans ce projet. Les papiers étudiés sont :
- P1 : [Partial models: A position paper](https://famelis.files.wordpress.com/2009/12/paper.pdf) par Michalis Famelis, Shoham Ben-David, Marsha Chechik et Rick Salay
- P2 : [Partial Models: Towards Modeling and Reasoning with Uncertainty](https://famelis.files.wordpress.com/2009/12/icse121.pdf) par Michalis Famelis, Rick Salay et Marsha Chechik
- P3 : [MAV-Vis: A Notation for Model Uncertainty](https://famelis.files.wordpress.com/2008/06/icsews13mise-id4-p-16167-preprint.pdf) par Michalis Famelis et Stephanie Santosa
- P4 : [PEoPL: Projectional Editing of Product Lines](https://www.htwsaar.de/ingwi/fakultaet/personen/profile/benjamin-behringer/PEOPL_ICSE_2017.pdf) par Benjamin Behringer, Jochen Palz et Thorsten Berger
- P4 :[FeatureIDE](http://wwwiti.cs.uni-magdeburg.de/iti_db/publikationen/ps/auto/MeinickeTS+16.pdf) par Jens Meinicke, Thomas Thüm, Reimar Schröter, Sebastian Krieter, Fabian Benduhn, Gunter Saake et Thomas Leich

Pendant cette premiére semaine, je me suis concentré sur les papiers concernant les modéles partiels. Ceci m'as amené à ajouter deux documents à ma liste de lecture : 
- P5 : [Reasoning about Consistency in Model Merging](http://www.cs.toronto.edu/~chechik/pubs/lwi10.pdf) par Mehrdad Sabetzadeh, Shiva Nejati, Marsha Chechik et Steve Easterbrook 
- P6 : [Managing Design-Time Uncertainty in Software Models](https://famelis.files.wordpress.com/2008/06/famelis_michail_201606_phd_thesis1.pdf) (chapitre 3) par Michalis Famelis 

### Les modéles partiels

Dans l'ingénierie dirigée par les modèles (MDE), il est difficile voir impossible de raisonner et de se servir d'un modéle incomplet. Ceux-ci sont vus comme des objets inutilisables : ils sont une étape vers le modéle qui sera utilisé au final. Les papiers P1 et P6 introduisent l'idée des modéles partiels et leurs principales caractéristiques. Les modéles partiels sont une abstraction de toutes les possibilités de modélisation d'une solution. Ces modéles peuvent être utilisés pour modéliser n'importe quel incertitude dans un aspect du produit, de la spécifications à l'implémentation technique. 
Le papier P2 continue le travail débuté sur P1. Le but ultime de ces papiers sont de trouver des meilleurs moyens de gérer l'incertitude dans l'ingénierie dirigée par les modèles : au lieu de la voir comme un poids dont on doit se débarasser le plus vite possible, on la voit comme un outil permettant de prendre des meilleures décisions.