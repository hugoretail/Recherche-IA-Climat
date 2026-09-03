# Renewable and Sustainable Energy Reviews

## Sources

Référence : https://pure.mpg.de/rest/items/item_3029184_9/component/file_3282959/content

Consulté dernièrement le : 2 sept. 2026

## Glossaire

- **Earth System Science** : Discipline qui étudie la Terre comme un système intégré, en s'intéressant aux interactions entre l'atmosphère, les océans, la biosphère (végétation, cycle du carbone) et la surface terrestre. L'article aborde les défis spécifiques à cette discipline pour l'application du deep learning, notamment la nécessité de modéliser des relations spatio-temporelles complexes, multi-échelles et multi-sources..
- **ANN** : Un algorithme computationnel qui simule la manière dont les signaux sont transmis entre un réseau de neurones via des synapses. Dans un ANN classique (feedforward), l'information circule uniquement vers l'avant, tandis que dans un ANN récurrent, l'information peut boucler entre les différents nœuds, créant des dynamiques complexes comme une forme de mémoire dans les données..
- **Geo Spatial Data** : Données associées à une localisation géographique précise (coordonnées, pixels d'image satellite, etc.), utilisées pour étudier des phénomènes terrestres. Le papier souligne que le machine learning est de plus en plus utilisé pour extraire des motifs et des connaissances à partir de l'univers en pleine expansion de ces données géospatiales.. 
- **Evapotranspiration** : Processus combinant l'évaporation de l'eau depuis les sols/surfaces et la transpiration des plantes, un flux d'eau clé du cycle terrestre. Le papier mentionne que des développements en machine learning ont permis pour la première fois de quantifier de façon purement data-driven la photosynthèse terrestre globale et l'évapotranspiration de l'eau..
- **PByte**: 1 PByte is 10^15 bytes
- **Lambertian surface** : Hypothèse en vision par ordinateur selon laquelle une surface réfléchit la lumière de façon uniforme dans toutes les directions. Cela signifie que l'intensité perçue ne dépend pas de l'angle entre la surface et la source lumineuse, ce qui conduit à l'hypothèse classique d'une intensité constante d'observation d'un point 3D au cours du temps..
- **Physical model** : Modèle représentant un concept physique dont les caractéristiques ressemblent aux attributs physiques réels du système modélisé.

## J'en retiens surtout ça

Ce papier de recherche fait un état-de-l'art sur l'application du Deep Learning / Machine Learning à l'étude du système Terre avec des données.

### 1. Introduction

- Prédire la météo ça ne peut se faire que sur quelques jours. Prédire sur des mois ? Très compliqué.
- On a **énormément de données**, mais lesquelles garder ? Comment les interpréter ? En temps réel ? Le traduire au grand public ?

### 2. State-of-the-art in geoscientific machine learning

- Quelles variables considérer dans la construction / l'évaluation d'un modèle ? Pour incendies, quantité d'un gaz dans l'atmosphère, ...

### 4. Deep-learning challenges in Earth system science

- Les données récoltées de la Terre par nos machines (satellites, antennes, ...) récupèrent jusqu'à >100 PByte de volume de  données.
- De nombreux défis (voir les 5 points).

## Datasets

- CMIP-5 and CMIP-6

## Approfondir

Regarder ce que sont les datasets utilisés. Ce papier étant sortit en 2019, voir ce qu'il a donné par la suite : qui l'a cité. Y a-t-il eu des mises à jour de ce papier par d'autres auteurs ?