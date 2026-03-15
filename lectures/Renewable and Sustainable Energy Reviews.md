# Renewable and Sustainable Energy Reviews

## Source

Référence : Zeng et al., “A review of future weather data for assessing climate change impacts on buildings and energy systems”, *Renewable and Sustainable Energy Reviews* 212 (2025) 115213. DOI: https://doi.org/10.1016/j.rser.2024.115213

Consulté dernièrement le : 15 Mars 2026

## Glossaire

- **Scénario (RCP / SSP)** : “histoire possible” du futur (émissions/politiques/développement) utilisée pour lancer des simulations. Ce n’est pas une prédiction.

- **Modèle climatique global (GCM/ESM)** : gros modèle qui simule le climat de toute la planète, mais à résolution assez grossière.

- **Modèle climatique régional (RCM)** : modèle plus fin, sur une zone (Europe, Amérique du Nord…), souvent utilisé pour mieux voir les phénomènes locaux.

- **Downscaling** : méthode pour passer de données climatiques trop “grosses” à des données météo utilisables localement et à l’heure (ex. 3 h → 1 h).

- **Correction de biais** : “calibrage” statistique pour que les données simulées ressemblent mieux aux observations.

- **Morphing** : façon simple de fabriquer une météo future en “décalant” un fichier météo actuel avec des tendances issues des modèles (pratique, mais pas top pour les extrêmes).

- **Fichier météo « typique » (TMY/TRY)** : une année “moyenne” qui représente bien le climat habituel… mais pas les canicules/vagues de froid.

- **Fichier météo « extrême » (DSY, design days, événements)** : fichiers construits pour tester/dimensionner en conditions sévères (résilience, surchauffe, pointe).

- **Données « chronologiques »** : longues séries (souvent ~30 ans) sur une période future (ex. 2041–2060), utiles pour statistiques et extrêmes.

- **Incertitudes** : on ne sait pas “exactement” le futur ; il y a (i) l’incertitude de scénario (choix humains), (ii) l’incertitude des modèles, (iii) la variabilité naturelle du climat, et (iv) l’incertitude liée aux traitements (downscaling, correction de biais).

- **HVAC** : chauffage/ventilation/climatisation.

- **PV** : photovoltaïque.

- **DNI/DHI** : deux façons de décomposer le soleil (direct et diffus) utiles pour la simulation PV.


## J'en retiens surtout ça

- En une phrase : l’article explique **comment fabriquer/choisir des fichiers météo “du futur”** pour tester l’impact du changement climatique sur les **bâtiments** et les **systèmes énergétiques**.

- Pourquoi c'est compliqué : les climatologues sortent souvent des données “climat” (pas très fines dans le temps et pas toujours les bonnes variables), alors que les modèles de bâtiments/énergie ont besoin de **données météo heure par heure** (température, vent, soleil, humidité, etc.).

- L’idée générale (la “chaîne”) :
	- On choisit un **scénario** (scénario futur possible).
	- Un **modèle climatique** produit des projections (mais souvent trop grossières).
	- On les **adapte** (downscaling + parfois correction de biais) pour obtenir des fichiers météo utilisables.

- Deux façons de passer du “climat” à la “météo” locale :
	- **Approche plutôt physique** (modèles régionaux) : meilleure pour les phénomènes locaux et les extrêmes… mais coûteuse, donc pas toujours dispo partout.
	- **Approche plutôt statistique** (ex. morphing) : plus facile/rapide… mais peut rater ce qui nous intéresse le plus (canicules, vagues de froid, événements rares).

- Les auteurs insistent sur le point qu'**il n’y a pas un “meilleur fichier météo futur” unique**. Ça dépend de la question.
	- Pour une **moyenne annuelle** (tendance de conso) → un fichier “typique” peut suffire.
	- Pour la **pointe** (pics de demande) ou la **résilience** (tenir en canicule, panne, etc.) → il faut des données **extrêmes** ou des séries longues.
	- Pour dimensionner un **HVAC** → il faut surtout bien représenter les **conditions de design** (proches de la réalité future à court terme).
	- À grande échelle (réseaux, régions) → il faut des données **cohérentes spatialement** (même événement météo qui “se déplace” de ville en ville).
	- Pour PV/éolien → la production dépend beaucoup du **soleil** et du **vent** ; les “années typiques généralistes” sont souvent mal adaptées.

- Niveau “méthodo” à retenir : quand on présente des résultats, il faut être clair sur **ce qui crée l’incertitude** :
	- le scénario (choix humains),
	- le modèle (différents modèles donnent différentes réponses),
	- la variabilité naturelle,
	- et les traitements (downscaling/corrections).

- Ce qu’ils recommandent pour la communauté : plus de collaboration climat↔énergie, des **standards** (format, bonnes pratiques), des plateformes de données, et de la recherche pour mieux convertir des sorties à pas 3h/6h/jour en données exploitables.

## Approfondir

- Check si depuis cet article des standards ont bien été mis en place.
- ...