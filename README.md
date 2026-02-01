# Modélisation stochastique — Intégrale d’Itô & outils de modélisation (CM1–CM5 + TD)

Ce dépôt regroupe les supports de ma partie du cours **Modélisation Stochastique** (École Centrale de Nantes), consacrée à l’**intégrale stochastique d’Itô** et à un **toolkit de calcul** pour la modélisation de phénomènes aléatoires dépendants du temps, avec une attention particulière aux exemples **financiers**.

L’objectif est double :
1) fixer les **définitions** et les **résultats-clés** (brownien, filtration, martingales, intégrale d’Itô, variation quadratique, formule d’Itô, covariation, formule produit, exponentielle stochastique) ;  
2) fournir une boîte à outils **directement opérationnelle** pour manipuler des modèles stochastiques (notamment en finance : log-retours, GBM, actualisation, martingales).

---

## Contenu du dépôt

- **Transparents (Beamer) CM1–CM5**  
  Slides du cours magistral, incluant (selon les chapitres) des *beamer notes* pour les preuves et des indications “quoi écrire au tableau”.

- **Manuel / poly de référence (PDF/LaTeX)**  
  Texte complémentaire aux transparents : définitions, propositions, preuves courtes, recettes de calcul et exemples.

- **TD (feuilles d’exercices) + corrigés**  
  Trois séances (2h + 2h + 2h), conçues comme une progression :
  - **TD1** : rappels brownien/filtration, conditionnement gaussien, martingales (réflexes).
  - **TD2** : intégrale d’Itô, isométrie, lois gaussiennes, conditionnements, martingales associées.
  - **TD3** : toolkit (produit/covariation/exponentielle) + mini-projet finance (GBM : loi, moments, actualisation).

---

## Organisation pédagogique (9h CM + 6h TD)

- **CM1 (2h)** : filtration et information, brownien, conditionnement, martingales, motivation “pourquoi un nouvel intégral ?”
- **CM2 (2h)** : construction de l’intégrale d’Itô (processus simples prévisibles → extension L²), isométrie, martingale
- **CM3 (1h)** : variation quadratique et covariation, règles de calcul (dW)² = dt
- **CM4 (2h)** : formule d’Itô et applications (dont GBM et log-prix)
- **CM5 (2h)** : toolkit : produit (intégration par parties), exponentielle stochastique, EDS linéaires, intuition risque-neutre

---

## Public visé et prérequis

Ce support s’adresse à des étudiants ayant déjà vu :
- probabilités de base (variables aléatoires, espérance, variance),
- notions élémentaires sur les lois gaussiennes,
- un minimum de calcul différentiel / intégration.

Les preuves restent au niveau “outil” : l’accent est mis sur **la compréhension des mécanismes** (filtration → adaptation, trajectoires irrégulières → Itô) et sur la **maîtrise des calculs**.

---

## Utilisation

- Les sources sont principalement en **LaTeX** (Beamer + article).
- Chaque dossier (CM/TD/manual) est compilable indépendamment.
- Les macros sont écrites de manière “robuste” lorsque possible (pour éviter des conflits de commandes entre fichiers).

> Suggestion : commencer par le **manuel** et utiliser les **transparents** comme fil conducteur ; les TD servent ensuite de consolidation.

---

## Remarques & contributions

- Les retours (typos, clarifications, suggestions d’exercices) sont bienvenus via *issues* ou *pull requests*.
- Si vous réutilisez ce matériel, merci de conserver la mention de source et le contexte pédagogique.

---

## Licence

Sauf indication contraire, le contenu de ce dépôt est fourni à des fins **pédagogiques**.  
(Option : préciser ici une licence type CC BY-NC-SA 4.0 si vous le souhaitez.)
