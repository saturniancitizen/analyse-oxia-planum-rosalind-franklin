# Oxia Planum : géologie martienne et exploration robotisée

Oxia Planum est une région de Mars choisie comme site d’atterrissage pour le rover Rosalind Franklin. J’ai consacré ce projet à l’étude de ce terrain et à la façon dont les données d’observation orbitale peuvent aider à le décrire dans le contexte d’une exploration robotisée.

## La question du projet

Comment combiner des images et des données topographiques de résolutions différentes pour mieux comprendre le paysage d’Oxia Planum et son intérêt pour l’exploration par rover ?

Pour y répondre, le projet met en regard une mosaïque en couleurs de l’instrument CaSSIS, des images orthorectifiées de la caméra CTX, un modèle numérique de terrain CTX et une grille géographique de carrés d’un kilomètre. Ces produits permettent d’observer le site à plusieurs échelles : les couleurs et textures de la surface, son relief et son organisation géographique.

## Démarche

Le travail rassemble les données, leur analyse dans un carnet contenant le code, les figures produites et une synthèse dans le rapport final. Il relie ainsi la géologie martienne à des questions concrètes de cartographie et de préparation d’une exploration robotisée. Les données orbitales donnent un cadre pour étudier le terrain ; elles ne remplacent pas des observations faites directement à la surface.

Ce projet m’a permis de travailler avec des données géospatiales réelles et de présenter une analyse scientifique sous plusieurs formes : rapport, figures et carnet de code. Les sources des jeux de données et le rôle de chaque produit sont décrits dans le dossier `donnees/`.

## Pour découvrir le projet

- [Rapport final](rapport/rapport.pdf) — le document principal et le meilleur point de départ.
- [Figures](figures/Figures_Oxia_Planum.pdf) — les illustrations réunies dans un seul fichier.
- [Carnet d’analyse (export HTML)](analyses/01_exploration_des_donnees.html) — le code et le déroulement de l’analyse, consultables dans un navigateur.
- [Sources des données](donnees/README.md) — liens officiels vers les produits CaSSIS, CTX et la grille d’Oxia Planum, avec une brève description de chacun.

## Organisation du dépôt

| Dossier | Contenu |
| --- | --- |
| `rapport/` | Rapport final |
| `figures/` | Figures du projet |
| `analyses/` | Carnet d’analyse (Jupyter + export HTML) |
| `donnees/` | Sources et description des données géospatiales |

Les données raster d’origine sont volumineuses. Le dossier `donnees/` renvoie vers leur dépôt officiel de l’ESA plutôt que de dupliquer ces fichiers dans ce dépôt.
