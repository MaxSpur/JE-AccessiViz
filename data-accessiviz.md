# Cartes et rejeu d’itinéraires pour l’atelier sur l’accessibilité urbaine à Toulouse

Le jeu de données décrit l’accès aux destinations à Toulouse et dans les communes alentour, sur une grille de 50 m. Le [guide de l’atelier](https://www.maximspur.com/accessiviz/) explique les indicateurs, présente les cartes et leurs versions PDF A3 et propose un rejeu interactif des itinéraires.

## Télécharger les données QGIS

| Projet | Archive ZIP |
| --- | ---: |
| Marche seulement | [108,2 Mo](https://www.maximspur.com/accessiviz/toulouse-walking-only.zip) |
| Marche et transports sans attente | [80,2 Mo](https://www.maximspur.com/accessiviz/toulouse-no-wait-transit-only.zip) |
| Les deux modes dans un seul projet | [176,9 Mo](https://www.maximspur.com/accessiviz/toulouse-walking-and-no-wait-transit.zip) |

Décompressez l’archive, puis ouvrez `workshop.qgs` dans QGIS. Les **thèmes de carte** du panneau des couches permettent d’afficher les résultats à 5, 10 ou 15 minutes. Les archives contiennent aussi des couches de contexte et un dictionnaire des données.

## Comprendre le scénario sans attente

Le scénario suppose que l’on peut embarquer dès l’arrivée à l’arrêt, y compris lors d’une correspondance. Il compte les trajets à pied, le temps à bord et les temps de correspondance. Pour chaque catégorie, le modèle retient le trajet le plus rapide, y compris à pied. Les nombres de destinations accessibles, le choix de destinations et l’accès selon le rang sont disponibles pour la marche.

Sources cartographiques et horaires de transport. [OpenStreetMap](https://www.openstreetmap.org/copyright) et [Tisséo](https://transport.data.gouv.fr/datasets/tisseo-reseau-transport-urbain-toulousain)
