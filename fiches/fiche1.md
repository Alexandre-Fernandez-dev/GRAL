# Fiche de Lecture

Titre: A unification algorithm for typed λ-calculus
Auteurs: G.P. HUET
Date: 1973-1974  
Lien: http://www.sciencedirect.com/science/article/pii/0304397575900110

## Résumé

Ce papier présente deux algorithmes qui recherchent l'existence d'un unifieur pour deux formules du λ-calcul typé d'ordre ω.
Le premier algorithme utilise les règles α et β de la λ-conversion tandis que le second utilise une règle η plus simple pour l'implémentation.
Ces deux algorithmes utilise des procédures nommées SIMPL et MATCH pour construire un "matching tree"
SIMPLE prends un "disagreement set" et retourne un noeud du matching tree.
MATCH prends un terme "flexible" et un terme "rigide" de même type et retourne ensemble fini de substitutions.
Le document est assez long (31 pages), et un point important est donné a la définition du lambda calcul et aux preuves que leurs algorithms sont corrects.
Des arguments sont donnés quand aux performances et à la complexité de leurs algorithmes. Leur arguments se basent sur le fait que ce sont des algorithmes de décisions (qui évaluent les situations les plus favorables en premier) et sur le fait que leur recherche n'est pas redondante.
Ils affirment donc que leurs algorithmes sont plus efficaces que les autres algorithmes existant à cette époque.

## Références
1. P. B, Andrews, Resolution in type theory (1971).
2. A. Church, A formulation of the simple theory of types (1940).
3. J. L. Darlington, A partial mechanization of second-order logic (1971).
4. J. L. Dartington, Automatic program synthesis in second-order logic (1973).
5. G. W. Ernst, A matching procedure for type theory (1971).
6. W. E. Gould, A matching procedure for ω-order logic (1966).
7. J. R. Guard, Automated logic for semi-automated mathematics (1964).
8. J. R. Hindley, B. Lercher and J. P. Seldin, Introduction to Combinatcnry Logic (1972).
9. G. P. Huet, Constrained resolution: a complete method for type theory (1972).
10. G. P. Huet, Unification en théorie des types (1973).
11. G. P. Huet, The undecidability of unification in third order logic (1973).
12. G. P. Huet, A mechanization of type theory (1973).
13. D. Jensen and T. Pietrzykowski, Mechanizing ω-order type theory through unification (1973).
14. C. L. Lucchesi, The undecidability of the unification problem for third order languages (1972).
15. T. Pietrzykowski, A complete mechanization of second order logic (1971).
16. T. Pietrzykowski and D. Jensen, A complete mechanization of ω-order type theory (1972).
17. G. A. Robinson and L. T. Wos, Paramodulation and theorem proving in first-order theories
with equality, (1969).
18. J. A. Robinson, A machine-oriented logic based on the resolution principle, (1965). 

## Référencé par

[Cité 808 fois:](https://scholar.google.fr/scholar?hl=en&as_sdt=0%2C5&q=A+Unification+Algorithm+for+typed+lambda-calculus+inria&btnG=)
- A framework for defining logic - R Harper, F Honsell, G Plotkin 1993
- The calculus of constructions - T Coquand, G Huet - 1988
- An efficient unification algorithm, A Martelli, U Montanari - 1982
- Canonical forms and unification - JM Hullot - 1980
- Uniform proofs as foundation for logic programming - D Miller, G Nadathur, F Pfenning, A Scedrov - 1991
- Implementing mathematics - RL Constable, SF Allen, HM Bromley, WR Cleaveland... - 1986
- Isabelle : A generic theorem prover - LC Paulson - 1994
- ..

## Adéquation au Projet et Avis Personnel

Ce document me semble intéressant car c'est un papier assez anciens, théorique et est très cité, cependant, étant théorique, il peut être compliqué à intégrer dans le cadre de GRAL, et à implémenter pour le projet. Il semble très complet sur son sujet et donner des lemmes et théorèmes importants, mais manque d'étude de complexité poussée et d'application pratique.
