# Les Lorientais Morts pour la France

Mémorial interactif des enfants de Lorient tombés au champ d'honneur, de la Première Guerre mondiale aux conflits de la décolonisation. La page propose une carte des lieux de décès, une frise chronologique, une répartition par conflit et par catégorie, ainsi qu'une recherche par nom ou par commune pour retrouver un aïeul.

**Démo en ligne :** https://sylvaino.github.io/Lorientais-morts-pour-la-France/

Cette version est **autonome et embarquable** : un seul fichier HTML (`index.html`) à intégrer en iframe sur n'importe quel site externe.

```html
<iframe src="https://sylvaino.github.io/Lorientais-morts-pour-la-France/"
        title="Mémorial des Lorientais morts pour la France"
        style="width:100%;height:1400px;border:0" loading="lazy"></iframe>
```

## Source des données

**Ville de Lorient** — via le portail open data `sdem.huwise.com` (Opendatasoft / Huwise)
Jeu de données : *Lorientais morts pour la France — Ville de Lorient, analyse par commune*
Dernière mise à jour des données : 2019

## Technologies

- HTML / CSS
- AngularJS + [ods-widgets](https://github.com/opendatasoft/ods-widgets) (Opendatasoft) pour les visualisations connectées à l'API
- Fond de carte [OpenStreetMap](https://www.openstreetmap.org/)
