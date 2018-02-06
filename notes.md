---
title: Notes
permalink: notes.html
---

# Notes 

Je publie ici les notes que je prends quand je travaille sur les différents papiers. Je décris généralement les principaux concepts et termes utilisés dans ce projet. 

### Domain-Specific Language / Langage dédié

Un DSL est un langage de programmation créé dans le but de répondre à un besoin dans un domaine précis. La différence entre les langages dédiés et les langages de programmation classiques est parfois floue. En effet, un langage classique permet déjà de créer des structures de données et des fonctions complexes modélisant de facon réaliste les cas auxquels nous sommes confrontés dans l'industrie. Les DSL sont petits, généralement déclaratifs, et offre une solution à un domaine particulier. **Dans beaucoup de cas, les implémentations de programmes en DSL sont une abstraction qui cachent une routine classique.**

D'où provient dont le besoin pour les DSL ? Le document P7 apporte des éléments de réponses dans sa partie 3 "Risks and Opportunities" :

- Le projet dépend énormément des développeurs, et il est possible d'automatiser certaines de leurs tâches clés

Un des aspects vraiment intéressants des DSL est le fait de pouvoir libérer les développeurs du besoin de modifier la logique du logiciel.
Ainsi, même des gens qui n'ont qu'une connaissance superficielle de la programmation peuvent travailler sur le projet, avec une notation qu'ils connaissent déjà. Cet aspect des DSL est trés bien expliqué dans [cette vidéo](https://youtu.be/pVIywLXDuRo?t=1m12s) . Ceci est utile quand la participation d'experts du domaine est requise.

- Réduction du nombre d'erreurs dans la logique du logiciel

Lorsqu'un développeur crée un DSL, il définit un ensemble de règles et de cas qui empêchent des erreurs liés à la logique du logiciel d'apparaître (Domain Specific Error Message). Le développement de solutions devient ainsi beaucoup plus fluide et n'est plus ralentit par des problémes causés par des erreurs humaines.

Bien-sûr, il y a aussi des obstacles à l'utilisation des DSL. La création et la maintenance de ceux-ci est élevé. Il faut également former les utilisateurs à utiliser ces outils.

### MPS

MPS est un éditeur projectionnel créé par JetBrains permettant de créer des DSL. Il traduit nos programmes écrit dans le DSL que nous avons créé vers une des plateformes supportées par l'outil. Actuellement, MPS est particuliérement utilisé pour générer du code Java, mais il est également capable de générer du  C, XML, FHTML, PDF, LaTeX, JavaScript, et plus encore. ( [Source](https://www.jetbrains.com/mps/concepts/) ).

### Projectional Editor / éditeur projectionnel

Un éditeur de code classique est un éditeur texte. Ce texte est ensuite lu par un analyseur syntaxique, qui le transforme en arbre syntaxique abstrait (abstract syntax tree, ou AST, en anglais). Un éditeur projectionnel édite directement l'AST.

### Partial Model / Les modéles partiels

Dans l'ingénierie dirigée par les modèles (MDE), il est difficile, voir impossible, de raisonner et de se servir d'un modèle incomplet. Ceux-ci sont vus comme des objets inutilisables : ils sont une étape vers le modèle qui sera finalement utilisé. Les papiers P1 et P6 introduisent l'idée des modèles partiels et leurs principales caractéristiques. Les modèles partiels sont une abstraction de toutes les possibilités de modélisation d'une solution. Ces modèles peuvent être utilisés pour modéliser n'importe quelle incertitude dans un aspect du produit, de la spécification à l'implémentation technique. 

Le papier P2 continue le travail débuté sur P1. Le but ultime de ces papiers est de trouver de meilleurs moyens de gérer l'incertitude dans l'ingénierie dirigée par les modèles : au lieu de la voir comme un poids dont on doit se débarrasser le plus vite possible, on la voit comme un outil permettant de prendre de meilleures décisions.
