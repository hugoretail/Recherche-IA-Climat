# Development of a REgion-Specific Ecosystem Feedback Fire (RESFire) Model in the Community Earth System Model

## Source

- Zou et al. (2019), *Development of a REgion-Specific Ecosystem Feedback Fire (RESFire) Model in the Community Earth System Model*
- https://doi.org/10.1029/2018MS001368
- Consulté dernièrement le : 6 oct. 2026

## Glossaire

- **CESM** : modèle numérique du système Terre.
- **CLM4.5** : modèle de la surface terrestre utilisé dans CESM.
- **RESFire** : modèle d’incendies régionaux couplé à CESM.
- **Surface brûlée** : fraction d’une région brûlée pendant une période donnée.
- **Rétroaction** : effet en retour d’une perturbation sur le système qui l’a produite.
- **GES** : gaz à effet de serre.

## J'en retiens surtout ça

### Un modèle d'incendies plus réaliste

RESFire améliore la représentation des incendies dans CESM en tenant compte des différences entre les régions. Il prend notamment en compte :

- les conditions météorologiques ;
- la végétation et la quantité de combustible ;
- les causes naturelles et humaines d’allumage ;
- la propagation des feux ;
- les émissions produites par les incendies ;
- les changements de végétation après un feu.

L’objectif est de représenter les incendies comme une composante interactive du système climatique, et non comme une simple émission imposée au modèle.

### Les rétroactions entre climat, feux et végétation

Les incendies dépendent du climat, mais ils peuvent aussi modifier le climat et les écosystèmes.

Ils peuvent notamment :

- émettre du carbone et des aérosols ;
- modifier le rayonnement et les nuages ;
- détruire ou transformer la végétation ;
- modifier la quantité de combustible disponible pour les feux futurs.

Ces effets peuvent renforcer ou limiter l’activité des incendies selon la région et l’échelle de temps considérées.

## TODO

### Approfondir les rétroactions climat–feu

Étudier comment les émissions des incendies, les aérosols et les changements de végétation peuvent modifier les conditions climatiques et le risque de nouveaux incendies.

### Comparer avec le modèle de référence

Comprendre précisément quelles améliorations de RESFire expliquent ses meilleures simulations de la surface brûlée par rapport à CLM4.5.

## Approfondir

- Article de suivi sur l’utilisation de CESM-RESFire : https://acp.copernicus.org/articles/20/995/2020/