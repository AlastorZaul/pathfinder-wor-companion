# WOTR Companions

Guides de build pour les compagnons de **Pathfinder: Wrath of the Righteous**, en français.

Site en ligne : à définir (GitHub Pages, une fois le dépôt créé).

## Contenu

### Compagnons
- **Vue d'ensemble** : les compagnons relevés sur la page Companion Builds du wiki Fextralife, avec leur classe recommandée.
- **Ember**, **Delamere**, **Arueshalae**, **Woljif Jefto**, **Sosiel** : build détaillé, avec ordre de montée de niveau, dons, sorts, équipement, points forts et points faibles.
- **Daeran**, **Regill**, **Greybor** : build résumé. Les niveaux ne sont pas précisés dans la source.

### Builds
- **Builds par classe** : pages de build du wiki (Eldritch Knight, Inquisitor, Magus, Monk, Rogue, Warpriest, Bloodrager, Arcanist), builds d'archers et guides mis en avant.

## Structure du dépôt

```
index.html          Accueil
companions.html     Vue d'ensemble des compagnons
builds.html         Builds par classe
<compagnon>.html    Une page par compagnon détaillé
style.css           Style commun à toutes les pages
theme.js            Bouton clair / sombre et menu mobile
.github/workflows/  Déploiement automatique sur GitHub Pages
```

Chaque page reprend la même barre de navigation. Quand tu ajoutes une page, pense à l'ajouter dans la barre de navigation de toutes les autres, et dans l'accueil.

## Compagnons à compléter

Camellia, Seelah, Lann, Wenduag et Nenio n'ont qu'une description de classe sur la page Companion Builds, sans build détaillé. La page annonce 15 compagnons ; seuls 13 ont été relevés. Les deux restants sont à identifier.

## Déploiement

Le site est déployé automatiquement par GitHub Actions à chaque push sur `main` (voir `.github/workflows/pages.yml`). Si le déploiement est en attente, il faut l'approuver dans l'onglet **Actions** du dépôt.

## Sources et limites

Les données viennent de :
- **Wiki Fextralife** : page Companion Builds, page Builds et guides de build par compagnon.

Limites à garder en tête :
- Plusieurs guides datent de septembre 2021 et ne correspondent peut-être plus à la version actuelle du jeu.
- Les niveaux et les ordres de dons ne sont pas tous vérifiés en jeu.
- Les pages de classe du wiki ne donnent pas de build précis, seulement une entrée par classe.
- Le guide de Woljif Jefto cite trois attributs dans son en-tête pour un texte qui en utilise deux ; le point est à vérifier.

Chaque page indique ses sources en bas.

## Avertissement

Guide communautaire non officiel. Aucun lien avec Owlcat Games ni avec Paizo. Pathfinder: Wrath of the Righteous est une marque de ses détenteurs respectifs.
